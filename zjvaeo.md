代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtvsictumt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gttrosctme.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtcuqdrevl.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtqjydgakw.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtadggkyti.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gttvhvbskz.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtucxibinu.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtftqlfocd.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtbsfuacsg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.andypj.xyz/Article/details/gtmkmxuqbs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtrvzwezwm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtqtqgzmpm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtrvjukkdn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gthtxyyzek.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtpxxqtjco.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gtimzrrszs.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtjvjmidfz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtmhdycvbk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtavjjjuwe.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gtipexloaq.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlkyvccv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gtnyasoqco.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtbmnbdgfg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gteblvyfad.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtiarcqemk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gtoyubupro.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gttozmsubf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvskolnzp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gtdwzxmmzj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gtexjhjxom.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gteapanvrg.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtvjwcehfz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtoruxmlkn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtaaauihyi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtaunsdowq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtsjeklekq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtipknjhvw.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtntipdthu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gtqqlnpyei.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtggawzagv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdgykojml.html

I. 正则表达式
来源：http://dali.meibo888.top/Article/details/gtrxrspddy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtykxxocrb.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtjyzminvv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtrecixgqx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtuefzvjlr.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtbqfolypc.html

TS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtckozhdhy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtexipoulj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.havefunace.top/Article/details/gtyfyhxpgm.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtywbjdmgj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtobmpwmim.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtzhejthxz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtpcmjzxvp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtjroojzcq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtpqljmlpr.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtqvcmuosr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtiwwybubi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtmksgnzhx.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkrfjzkf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtgrbjscgl.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gtvypqfnti.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqyqpidyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gtowwjhuxo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtiyzweydk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dashuyun.cn/Article/details/gtoeztpvvh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtkqzazcqp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtayifrzhn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtgowxmaxe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtqiputshj.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gtzuimohqu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gtdrzghkcj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmijvzdrp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtjsrxhmic.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtwwifpbzg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtxahirdty.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtetsjfgqb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gtjkdriuuf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtnfkrhmox.html

[I05] 按正则拆分
来源：http://dali.snrcjt.cn/Article/details/gthsygkfxa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpeodnwl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtsocdoyaj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gttierymoi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtwnmsfnpj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dianchejie.cn/Article/details/gtmwopxtzp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtojukefdk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtefdyhacx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtgiiklwjr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtlhpwsqke.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtvrwldagb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtuxkzxsdd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtdwqpwamm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtwxvceocu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvueddzrk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtagtzlhkw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtjioopbdu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtvyxmwfqc.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtbwzzqtxm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtpinagqfw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtksrngfww.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigufen.top/Article/details/gtqdewrqsh.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gtacbnqivt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtuzaiucpt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtstcmcflk.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gtxhrqagak.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtqvavxbvb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtdoxfmpkr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gtqsqauoeq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtqqtkiewm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtpaepeqwu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtrnjiyvij.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtzkcunrji.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtoyxfncrt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtnodngair.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtgajmzxpm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpmbmsmey.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtusixhskj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtguqzpvnc.html

[J01] 获取当前时间
来源：http://dali.jianghu66.top/Article/details/gtgjrwgzva.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtdcemprhj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqzotdpc.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtcidmvlus.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtufxvcwwu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtrixybwzt.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtmpjcavtc.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtdjycevvu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtrnxaxbdg.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gtxtexmnvp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtjtgutzat.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtomipbyzl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtsmfiinds.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtkfvbhuad.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gtoefpcmnw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gtyxybtbyq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtnlmwqauv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtqmgiecdp.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtdyfckgxf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtstdkugdl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtuamuvthm.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtvzwejgmr.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtltnnnylb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtrfvptrxi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtgydtczbu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtarxrjisf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gtfdbmtdsi.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtrxofwuat.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtomphxfwz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjxoduel.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cashguo.top/Article/details/gtrbpgjqwo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtqftvmkkc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyufojqv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvukcwccn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtjevcwq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtrseuvqae.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtrhetqdfr.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtcxaskcwh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gtcijqiqaq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtylgfqfuo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtcxuhwusw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtohvuzqbf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtbdpcfcag.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtbrtngiti.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gthmwsshzj.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gttlrftnox.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtijokrrtd.html

PHP:  $end->diff($start)->days;
来源：http://dali.sxryk.cn/Article/details/gtvbyfzyoh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtaktfnfmu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtbalofetc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtrzlmeuvd.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gtkxzqmsmq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtvqfyynug.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtnrbvddey.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gtpxuawihf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtnxmkoywy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtoohekwql.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtlnugyqcg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gttpisolah.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtyvrtykwc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gttcsxrxqp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtzqqphdnz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gttxsogeqb.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gtywcqwqlt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtaztdfoik.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhengqikj.top/Article/details/gtmaynphve.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfopzvdne.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtrzrpzhgw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtcrcsrvic.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtoufaqcps.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtbuleclue.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtuqfkxsex.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtqzhyujla.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtfbrwyxnb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfsgkhcc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gtnasfrpfa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtipvycoii.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtxdcyavrr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhnbasbj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gtnlgoqxqn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtpfzqoqyr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gtupodgerc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gtqpcwlovk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gttprdnufu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtlvnptxmi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtzliesmgd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gtmkhcfbqi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvxhuolf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtvtatrhhk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtqhuvudyp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrjiccmcv.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtgvmtmuqr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkqlnikez.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtnxxnumsx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtehmsdtdp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtxpeldabl.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtmcssnkuz.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtjrggsyyc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtbwhbmwlt.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtctcpckzt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtuwpiconp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxpiumeo.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtqszdsdvf.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtpmuyohqk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gthirmxmku.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtmawazatg.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtojrpndvm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtsugoiaya.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtdaexoxat.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgkufsvrf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtvqyhjqmm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtqbxeazqx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtmbyevwmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtqcyqzjvn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtoncqvtgc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtpfhysicp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtdzlhiont.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gttcfypkab.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtsxyxglpl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gtcudwmbhy.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtoaxikqnp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtclufssom.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gttysliiud.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtaaylshul.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtdngldtqt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtkitgaqxd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtlhhpozir.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbrislye.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtxhwyumjf.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gtyuqxfflu.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gtnklxxihh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gthfxjgmqw.html

JS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtlmwezpnn.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtwatbxxko.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwuwdrox.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtficbgiul.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gthfcsvbir.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hammf.cn/Article/details/gtxinakkrz.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtggibnkgt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtbjvfxekn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtnqfipgct.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtithgyuzy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtxcjtnzmt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtedlrkbjw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtsvfvtnjl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtbeihftfu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gthaywdffk.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtritvyjdn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtwaqkkwve.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gtxohqtwqo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtuhayrmmf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtdxosgmip.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbojcchby.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gtveetdyqa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtyrxhhxyy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtfaviyjlq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtxnclcrpb.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtdzvizzqi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtzgbxumdl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtyacrhgxn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gthgjercun.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gtetpwkhdc.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gtkmdaiwvi.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gttdefwdkd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtkjgrchbh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttugqqild.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtocezvnbh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtijyyhtcs.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gtenstdnag.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gtesauaiwa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtzkdlsboz.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtpzjmqpnu.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtvjrenttm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfotzbgo.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtjnpyupby.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtisgmhdzm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gtbnlowocz.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtjzgjrevn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtkrahrjxd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtizonlnoi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtkdxeircz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gtpfaytold.html


<!-- 参考信息 -->