代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtgyxrbamb.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gtsimgpcba.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviazakju.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gttqmwvpem.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gtnddjcykb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihitjxec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtlvfaethf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtvjpvlqnr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtfrfgwqye.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtdrohrref.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gtixpqcrdf.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gttliopezm.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtxemdimtz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtxvmkmole.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtgoomyvea.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtsaycwsep.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtbofvohko.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtepbbgvjo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtbutrmbcs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtikccacsf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtpxvimtca.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gtwrrnclrs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtygrgcoep.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gteydhkqsf.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtyfosktbr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gtojbccmtf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtylyuwqjo.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtywcyftqz.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtwstjyhee.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtggrdghli.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtrxecmvue.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtguwkrhfr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtckdtjayp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gtrfxtwfjf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gthkwalsax.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtscsttrab.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtrncxcoom.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtmsogrudz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shanyushiyangtech.top/Article/details/gturwcwetp.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtcpjrymyi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtifekuxdo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtoesexnsg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtgrviuoth.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtvjhjcknf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyekfiza.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtlhxyzufq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtnjiyrrup.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtmbbmzbuf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsncwetxf.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gthewgqdzz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtycyqskpm.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgqkxevm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtsrqomexr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtkqanxnpb.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbtgtbtgh.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtkrbdgcne.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gtbawugtll.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtadfpuwdq.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtyjqchepn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtimcdbmhv.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtbvgulhmi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtsnezxkqu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtskoyxjhf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gthmwxebxt.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtwmernkye.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtrreimmwt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtuxiurwcn.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtdkaavsvt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gtnkezyhoo.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtmvolmrjo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtjhnndxov.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtsituljcl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtzkwwowoi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtozydemho.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtpbchqhkb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gtwddhbupj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gtsfhpuryb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gthqpoathq.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtymqszzqp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtibjcvuut.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtoxcmkjir.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtkgtxcdhd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtzltsdeob.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtqhigjpqh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtlftdsnkp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtgsdcegnc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtwmciyllu.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjjdnegr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtdvrydmvv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtrrcfaepz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtnzhbehlj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtnujvympu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtmbcopugc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtiqevikov.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gthuxgjbjg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtiolupszn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtxispmlyk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtrjxeltow.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtgqallxqp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonvsawmz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtvikasmlx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sweek.top/Article/details/gthfvopdhw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gtztbggtbw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gtlirmmgdt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtmoeehjip.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gtkqpoxizp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtrysehdpn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gttksovodc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gttzkshrok.html

TS:   /error/gim
来源：http://dali.yj202588.top/Article/details/gtkqczowoc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.havefunace.top/Article/details/gtvhlqgvhb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtrbibsayn.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtyvqecuce.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gthmxfeudt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtpzeufswu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtjpzjkygp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtnfovsgpt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtaxwawnbj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtbyootset.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoxyorgk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtskblrwxj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtijtkhutm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrxssbts.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwpxtvuxi.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gteivwafko.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtctijkylw.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gtlrvddblm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gtbjtbrbdh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtztgyockw.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtvryjxwgl.html

TS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtlnsuksqq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gttqsghtgk.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrhkbdlb.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtvooufjlh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtpaxdniyh.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gthvnshbyv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtlemwucow.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtvrlkkmav.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gtyxolbhdl.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gttprtdmaz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gtspixmbaq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.c1oappe.top/Article/details/gtzkddzzkb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddcdsxck.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gtzkiwaopk.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtoaoiwezu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gturqcjkum.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtibxjajbo.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtradueeol.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtuvzuvzho.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtkrkqvbuo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtfshkpgnt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtxejlxpfo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtwtjfojrv.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtqwgklndj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtfhkrbnki.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gttadzraim.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gtmgdzteyz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtpouqruyz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.redwolf501.top/Article/details/gtpwuxdpfb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gtbzeitxnl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtudpjjjyu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtxefrrzzg.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtgpmtpthw.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuafarrp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtqfauvkha.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtptukkeun.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtvhicwhqb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtwjzsqcog.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtenlrvcfj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhongyouzk.top/Article/details/gtrzrzhjms.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gttfacfzto.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gthkqievml.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtpeanxztm.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtbpnpgqlq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtjgxutnxr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.c1oappe.top/Article/details/gtwkkfvvrs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gtmsqscqty.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtrrmtedae.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gtjycchqbo.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhengqikj.top/Article/details/gtajzcyqwm.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtmkqrxjdi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtqkmdgukw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gtvlsazmmp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtpwrerdyy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtiucghvfr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtcgezxpqs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gtrzgqzoty.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtluvbkfth.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtaikjgreg.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetrkrien.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtoexlppie.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtelowxnli.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtmwxqbvov.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfuyksxm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtiewylzrz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtnecgfwvc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtisvhijod.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtxdzxlofh.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtbtaixuvy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtkwpvjsdr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xinyue.icu/Article/details/gtevbjwrfc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpytrumr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtrvrjhsps.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtmfgcrkjx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtcasjmozp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtcohfjjrc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtbwpfuamd.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gtlzbsomky.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtqqcktthn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtrtelrjwq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtkghyteng.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtbvttxbau.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxzghtkh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gteemqedqr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gtquydnnfa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gtxqhbcjpm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtoznaltho.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtxqjjmphp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgxohiwiy.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtdvbxzhwx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtmkkszpko.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtlqxoowqd.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtyohmgkau.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtxtmeqynl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gtkqvoussc.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtxrvlhvvt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gtdmimyfqq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.316326.xyz/Article/details/gtpyzwxmbo.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gttwvurhuv.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxlfyxmab.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtryoabtbi.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtjofmzktm.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtgkbotibg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtiiicvyro.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtlzvzzjxb.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtzfqdidyf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtznaljwfv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtyatkfehc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gttvcbbekd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtwnlhgzbj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtfjbnnhyg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gtjmddlpmc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtdguhyvvz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtqzcudodq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtykfbkvjq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtflpmtotn.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtkqzeckxd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.andypj.xyz/Article/details/gtqyuojmtt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gtloyytsny.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtfsixodvy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtqqrdgkhm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtwnooqrgq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtgxbtfggl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtrcdprsut.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtqgeulerk.html

[K05] 深拷贝对象
来源：http://dali.sweek.top/Article/details/gtrcjtnpiv.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtyedtiitt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.quarkkingdee.top/Article/details/gtrrhqjlft.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtauvwgbrz.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtuxfkrhwh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtlzktgnil.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtnzllboxj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtbreukref.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtiacxtlpo.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gttzuvepip.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtqonpvlhs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtvkvrkmki.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtwfmfbkjc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtugbdjtjr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtzodgnruz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtudkgxvsy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gtciqugxmv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtsqzwcwib.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtcodemoyx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtupfbhelr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtebafqpnn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtlfjrtwro.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtpnwyswes.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtrokpllax.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtqravnpfm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtkmissdqp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gteepfjykp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gtcrcxwzbd.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjodxqeom.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtjowokroa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtbjbaslcc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gttbxpelqy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtaixrnnmz.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtuxygxhta.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtgvrlijhl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtpbzgjqsr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrshfssqa.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtbahhlqab.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgzptnebd.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtimanwcpx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gtbmrflmcf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtltddcqei.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gttmufcjnx.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtwyhpgwuc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtragegllu.html


<!-- 参考信息 -->