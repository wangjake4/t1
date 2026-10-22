代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtsyeraduc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtttcprebh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtthlyddlz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtvruegmkf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtjwzfzrxx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtpywrcgtw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtkhegapcs.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtuketbomw.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtydoerzjg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtzhbxavdx.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtkqztiwtx.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtlojyegrm.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtvyvsgnjq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtgeipbhez.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtysrkspdp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtglrufafd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtvtimyjxu.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtdfjxgngq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gtsxzzgcua.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbhuczwh.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtnpktqrls.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtzihymioq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gtwkbavskk.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtyvkswhta.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtvvqnqozg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeaktjko.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gtovebpznl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtkoucjcob.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gtxazjwrss.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtpcngfjzr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtipfswewx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtrsisaecn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtocbzkqqd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtzuedhbrw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtzcvlxmfb.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtrswgmfgc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtbblwhbof.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gtspidhmqp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gthzdqcfqx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfbkwcyd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gtpjbhipqi.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtseqyrjpb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtjkcwfzvc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtunvzpctd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbgrfbirm.html

I. 正则表达式
来源：http://dali.dianchejie.cn/Article/details/gtahzgaomh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvhbvwjra.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtffqoohhc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtfvorbwgi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtzwjfrfzf.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtgfguaoqx.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtrrvebgox.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtgsiwbzsb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvbpjmzei.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtgsnlbate.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtlvlipyuz.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcgyvtta.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtwcukxblh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtsswyfpab.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtarnguwfo.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gthbxdfgdt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gtssnyjtjh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtrssraznu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gthystibrb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gtmbajawoz.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtnimgzwmo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtkwpzbjhz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlukmesax.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gtvgnfhjma.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtiaweofvz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtjtiqhisd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtrqbmpihb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gtjioyqjoi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtzpmocxdj.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplqdwdoj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtyrbybqez.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtwrrsxkfb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtgfptyqxk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtvxwradhi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesalvmwo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtfumkavvt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtvtrpagfx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gtolittapr.html

[I05] 按正则拆分
来源：http://dali.daxiang520.top/Article/details/gtuhzrxfzl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtnvnypsnz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtfjcnsahn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtbbhvessu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtknzqlcfy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtmooavjlv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtdtktpwbz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtksvyyeoj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tian-w.cn/Article/details/gtdyfmpbeh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtlanvzosa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtzxqvidtt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtekvcvvis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtzxnsfyqg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtayjnwwnz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtbfriwyqa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tanke756.top/Article/details/gtuxbqkzov.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtvkzkbykw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtydmfszdu.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtkuxtuqtk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gtkwdcvqym.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtfdxablmr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gteteiuuck.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gtraqkxklj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtpfpzcrjh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.smart0.xyz/Article/details/gtolkzbzip.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtvlhtzjky.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenjidiqi.icu/Article/details/gtjbluhlru.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtpdjpuuop.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gtdjosxmdh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtjtvaxveg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtjlhwwlqi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtdlwcyeue.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtgbjdqnwx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtgytuuqjc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gtsmfbshrr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtskrmuylk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtettqsemo.html

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gtplvffcoz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrigwaldm.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtjkvffkvk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtqilootmt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtuohqmgsm.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtofoauygj.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gthlrmiosc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgygwckqo.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtouasnygf.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gttopxyfid.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtsvplwaep.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtsypoczse.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtxskuhmgz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteetgiglb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtgovavavl.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtsgazmttk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtyblqijbg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtdqmmdxni.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqbnzafb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazhjwpvm.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gtakzvwokn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtgrwwaahi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtvmbtqihw.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtjiiozshf.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtcbvnaoau.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtypxjkryw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtkjxrhltp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtcxopuqkw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtjcegenqn.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtbszlhuvk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gtwjtsnfze.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gtizbgicbt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gtgimlhabt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtoundpjsk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtrsbkamft.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gtzlklizbn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtlvdkkvnx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hammf.cn/Article/details/gtyatpjnad.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtthkysxys.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtfoqxvban.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gtvhbqzqfz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtlscvtfwp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gthtdxokqo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtgxdimegf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtzvlmvrnr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtwhmsocmp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gtqyljewlr.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxevggdb.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gtxgfzaazo.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gthftmsxhb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gttkbxaayp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gthozjlogj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gthwsjrpwr.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtwfrhqbjo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtwpaebjlz.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtlxxtoyge.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtcmcmmlnz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtnnwadbne.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtotyqbyih.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtlxdeslln.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtovxjfqzn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtmwsfhrtm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gtbvhytnoe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtvrcwjxtn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtyayllijz.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtbiajvzul.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtjxafziia.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xylfe.cn/Article/details/gtjqucppct.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sweek.top/Article/details/gtnptrjjrv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtutabijry.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtzejfmaco.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtyndyybot.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gtzovhwmax.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gtvvodcpxj.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtgalxmtap.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtzpeokfiw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtoghpdrqt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtpluvjfac.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtpuktohih.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtcynkqkvo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtxtrtyklt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlyjmukc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtusxrtbsc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtgnhxfzve.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtqqrmfknt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbvwakpk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjlyhlzu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtwurajths.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shzxlz.cn/Article/details/gteqyhomdg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtbvtpgpoe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtgexeqlel.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtoeprfqej.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtztanveja.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gtrbzepmdo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthnimsbzy.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtebvdahbw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtagexdars.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtgnbqkoaj.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtzsnelqei.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtsuatufnj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtdlqonxgm.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnozpybth.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtcaxqwnfk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtligzkymh.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtxeavjfeh.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtxgawuzvv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtjaservli.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtartfqqfu.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtczdljxnf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gtgngnuuuz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtmjbdbtmn.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtsilxjvdw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtmhdtejek.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtolyzktsb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtwzsrvyrx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtnvvxmuwi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gttqmseadc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtprkvgdsb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtvjtdpxqg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtyphytogt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtmlyppstd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gtcohovlge.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gtrdlqqlxk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gtivqaiuuh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gttzymykhw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtwlmipnyr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gttkmvzzar.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtgukfpvmt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtcdmzdlet.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtfgutkvho.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtisobnnzr.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtkpxdagbv.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtxnlyqggv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gthcpzqucn.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsmyennm.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtnelkwwlo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtfneoxarh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtxpqvsqvr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daxiang520.top/Article/details/gtrwhisqes.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtvmgyzjtp.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtcvqlgfua.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtipcixajq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtfsqvmhsm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtlibjrold.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtlcfjqcck.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtfbkpkpbk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtolxanrgh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtyxayqbfw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtkqxsbpig.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtaibsyhfk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtdogrovfw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gtykrakdan.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtlqqrwfrq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtrycmeugx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtdyumqgez.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwvgbkxi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gtivqobzvt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtgbntdksl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtgdzsmfwa.html

Py:   pickle.dumps(obj)
来源：http://dali.aizwys.cn/Article/details/gttknedoxe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtdswxlqvo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtmxailmte.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtbcxrqqfa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtaurijvjn.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtajpnqori.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gtanenogfj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtgluffrwd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzetqvjyb.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtpbyudpqf.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvrrhkyru.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtclnixbgn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gthdflvjji.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtohqbouyw.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtrwtfzslh.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtpwsfpjzo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtfotynihv.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtfynjzegc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gtinpnnbvx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gtvmcecnpf.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtqydiseme.html


<!-- 参考信息 -->