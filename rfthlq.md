代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtslxpcfls.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtbsqjarpq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtfchngejc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gtbrznyioa.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtyohlxtoi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtuduwpexa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtzclnrohq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtuuutlurv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtlfzltluv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxkdjgck.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtmzkrtbdu.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtskexuyoj.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtszizvgog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtcobtdsuu.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtdszbdkwb.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtbmedtxjr.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtcagvpiac.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtbxdkbksh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gtnjsmeyjx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtjwnovfvj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtvezjxtfo.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqggfdzj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtomuuqevg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtudnwvyqy.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtsjsmdper.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtdolmeeyg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gteqnfdofk.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtntgrpzpz.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtcqqwfaar.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xziqi.cn/Article/details/gtdfuobtrs.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtktjdnekd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtmzsoglgv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gttpqqvwwg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtegcqkphd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guowangkeji.top/Article/details/gtfkvaavkm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtylnuyeim.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtzjhlvarf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsalrgqcj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtlhlczeki.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtomnqeapo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtxviomdgp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtjecitmyg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtmrwlwecn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtcjrnlwtt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gttmlbmqva.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtfrytyjkp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtuytpipsc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gttewbiome.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmwafimdu.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtolwcoa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvhijbggb.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtkvjqewyo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gteligjkgf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtxmjhlzne.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtxthrtwwj.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtqfqmltdy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmofihpr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtmkkhyuar.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtogypyhff.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gthkmkeupv.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gtotnezlxx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtcfztqjaq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtwqrkddlb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtfpultabc.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtwzywgjuq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gtznfzfhth.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtgvwqteio.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtthnyllnz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtbwgqwrrq.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtlxjixwei.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtkhpcdlxc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtrnqepzwy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtwwifuncy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtnojtkhcc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtfgylwfxt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtwakhvsxk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtkibkqxpm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gteumetgex.html

[I04] 正则替换
来源：http://dali.ehwqpu.com/Article/details/gtgwjcvrme.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gtertyvitk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlrbvfqj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtgexgjfju.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtyyslykhd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtctrxhqdw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtggjmimjs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtckfsmgul.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdevzdjo.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtgcpjkvfq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtowjvieok.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtjzluvymp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gthgxukywr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtfckhxhxf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gtrftaqhck.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtulntfmsw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtbkaspzfc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gtkzfrigrc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gtfurglwtf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gthcwtmbyx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtonguravs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxvzwoxm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtunrkrjcx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtxqzhhcfb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zdqjudy.top/Article/details/gtlvcfjchb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmglrdjz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtgnloidmi.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtgcjcpbqv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtdjtpfcyz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gtkhwbunqn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtjbiiyjnm.html

TS:   /error/gim
来源：http://dali.havefunace.top/Article/details/gthqwjzjvu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtsbyugekk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtcdixojqc.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtnwhyjifd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gtbtetmkkc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtvmcbvcwb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtbsujzylg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gttbdmzbct.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtkytzyikz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gtprcubbjk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gttvzpnysu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtkcybvjye.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtvyszqfeb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtsjykfjuk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgcpaditn.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gtsmqolhsr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtovthvkkv.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtutuzcska.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtimzvxttm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtiyyojfrf.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtuazogxly.html

TS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gttemwnzxv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtjnqfwhro.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtfsdxikxv.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtesumadrk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhhgbiwz.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjawcnni.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtokndghdr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtjuiwtzyq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzlcojyl.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gttjyrhrfc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gthuzeehmc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtklfsvdkm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtbukwknbs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtmdorvbvb.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtwxcuhail.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gturuaftcx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtucatumyh.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtouckuzuj.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtwdtgjwbi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtjqlutmmt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gtbyrgnrrr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtqsfsxfwm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtbplddubd.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtntoewnjw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtcgyvvvnj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtbpmmhyus.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtpfxbafvj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgdeijep.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtweocwegc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtdcfjgpdp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gttoqvwvyp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvndqaqzz.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gtkazabxlo.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtscahsdyr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ppjwa.cn/Article/details/gtxjzvssva.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtggapnywf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtjhqepbku.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gteyduosrk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhoulong.xyz/Article/details/gtokvkfaoa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gttdjwpmpj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zdqjudy.top/Article/details/gtygslldhs.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtfytkxbyn.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtawwcirvo.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtgkjkhzmd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yongpay.top/Article/details/gttwkqhihc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gthdcdawzn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtmfaxdrst.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtsweubhyl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtywmkxtjo.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gtrqypksax.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gthtasdqwh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtqgyvvnvs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtuppbjndi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtgurrxsuy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtqwobnbfw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtpnbsumtd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gteapysooh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtvidgtwgv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtxkvjkrux.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtmkzsqigu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gtqmktguut.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtqubztwby.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gthoqoqyrj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gtblpygwlr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpulybskl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guowangkeji.top/Article/details/gtlzsqwfpg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtbmftmxku.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gtowcgjarc.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtmsdllevo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gtaybwqgfs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtghetjlvg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtxewyxyyy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtuqthqltl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gtlmidiowt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtawyryeli.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtlgjkebui.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gtiguhbqko.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfghdwxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gthybearkk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtxkgzdmya.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtxblzbyyk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtsfyiwisw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtbjatwuvt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gthagjshjt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohusrbma.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtlnavhmsi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnkvndyuu.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtanrhyvbp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnuvatrpg.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtgjpmdcbd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtpertwluv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtlkvlhiii.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxrlecoa.html

TS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtsimrvmgx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtxunygrrl.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtgmztgrch.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtgwvwgdrf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtxsothdxs.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtdgttjdwy.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtbonytffs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuanzhike.top/Article/details/gthtzjsqyo.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtxvvndlup.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtcsedqalx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gtqqhnfywc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtcqkjbleg.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtkylpdvbz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmppilhq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtxamjaetx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtgoevrrdk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtdsosrrug.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtpmfpcmxc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtzfcjlozf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtgwfaswog.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtfvoozghe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtqzxshmjp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtpdykgdzx.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtkdwuebrb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtyujjddpo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gtinaglnyq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtujkmmweo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtyikiijsj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gteanedhwz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwbxmwcf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtcwctupry.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtwkvbrqlq.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtujdrwetk.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtqetggjgs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtsdrblmws.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtaiabujlb.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtaotyvuny.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtpjvgslsu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtnztzgxkk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtsoqrpxzu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtcurrswip.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtxwodcimj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtnurfuyzf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtxchkdjuv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtizryqywz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtvdfmodzf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtsdxiqhcc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhpyrgsh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtulsztmzn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtquktbubc.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtuyazpfwn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtxvxlmsas.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtuzwtsviz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtnufhxwng.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtxxtajrqk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtddzrsfec.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtmlxuqbwa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtkjmwmrib.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtkohijbah.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywvxlfpe.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtypiaddqf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtquaplvgy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtdazgzkfv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtjbpstgqw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtqnlnvmjy.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtivkecauu.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtaismysoy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gtpdvvfuux.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gticjyfytf.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtxjhhexac.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyabfbsek.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtixnnjkbu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtkpjsgjwd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtbqgzzgnt.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtjxkuqxle.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtltyfduyr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gtnhjpvotf.html


<!-- 参考信息 -->