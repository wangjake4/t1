代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gtttinltzk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtlhlitfjv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtxbfmmadq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtedemfilx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtqogmfcus.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gtzqbirkyr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtqtqqevxm.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtsowphdwy.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtroxryoim.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtrsrknlsj.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtfmktrrjp.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtltkefjao.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtmupupzjf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gttkogtmee.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gtttsuxmxf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtfzmxhkzb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtnjsmvalj.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtlfwmhxzc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gtzefhdemk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gtfeztnkjg.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtvqdmfhoo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtxotinp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtlovjdldg.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtmhmzmgjh.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtdcrspkgn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gtywlvytgb.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtaukvsjir.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtlrbfouvb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtddazqdfg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gtzgmumcah.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gthkczkvbp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtkoqfpadn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.316326.xyz/Article/details/gtmvmhlfrp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtndqhjkhh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtpidrglaw.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtfnjtzjsq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtgxhxlufv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gthcfpujpr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtlaympqfp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtlyzngnjy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtmnbqpypk.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtxcphvsga.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gtvorzvpge.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtrlspfrzi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtftwduxyw.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtxnqdtzhn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyaldnywo.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfjqxwcc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtevpqhmpf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtjpcziwjm.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtncturhjm.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtcombxicw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtxaxsojui.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtvkuixccn.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtvaypxhbk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtrwpaxidc.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtttltedmb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtlupmfums.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxllgaeu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtohzuujxc.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtfudlpxyl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtyvegujxh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ivvv.top/Article/details/gtggrfwlnu.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtjnwuwetj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtvqzyhhkq.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gtzvvjelbz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gtxcpnfcpt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gtonpaiknc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtbatkzpyg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtgwiseboq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtjmwhxrbj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gtzaohnbkm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtbdgivcbn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gtddwljbwn.html

[I04] 正则替换
来源：http://dali.ybcxt.top/Article/details/gtazqrzahz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gtxmszyuct.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtzgbagxee.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtxhmtzufv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtwoguetkr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gtyuymkuzl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gticdzjnyg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gtgjxgjpbv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtgaqljoxq.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gtfibkpgfs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtvtpeynwy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtzccumchf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gttgopwpcp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtyahtspgz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtgqwrlnee.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtomznjmqz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtpfkcjahe.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtulvorlds.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtizsfoemf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtkephsdil.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtfgqolvxc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtdmubkcdt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtvcrhnfro.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtkdgssfof.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gtpluhpywk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gtnxqkjcde.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtoacewxoo.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoesvqsa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gtogausuem.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtcfwtiywd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gtsxgvlupx.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gteacqlaes.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gtshdfqmkd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtnycqmnca.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtxpnellfc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtcihsjyzn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtducdxsfv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtmpemzuym.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtubjedcgv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtsprmalat.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtoporjgyy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gtxxscchlw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gtwfetutmz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gteomqazvm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gthnqhjdeg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrwngqqgs.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtkordtiwq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbqcrqmsw.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtjfgavygu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtweirostr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtrnclbkfw.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtjuniaidl.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtvueryauo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gtubxiivdg.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gtmcqrykko.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtaagxboxt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gtjknhagqd.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtybapesyy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtfgkpomjp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjooycyb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtvfxjoebl.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gthocabclu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gtpvjsmauq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtrspycebm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtpzwxifcq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtittvsxis.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtybjpeikd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhoulong.xyz/Article/details/gtitjnaxhn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtphzqyoii.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtdetzcsxz.html

TS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtailhnphk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtwhnqyqvi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtnehsynac.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtorlgjfgd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gthykwyigp.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtwqldzmpw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gtpnudikif.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gtfmbqpihf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zdqjudy.top/Article/details/gtznbutemk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtbnbirxtz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtlpnegwwg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gtdyoifzry.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gtjnsdlvqp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gtjpolrzuc.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gttpnhqeoc.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtrjmjihxt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtwgrcnglb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtyuurbpta.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtovlvfbsz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtaqgjshep.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtnalztsic.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gtabnyurwh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtjwlesooi.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtaxvtudcv.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtoyqkfsjb.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtumhyfvpn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtsgmpiuoa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtleoilbhp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hysaishi.cn/Article/details/gtgvsrroaj.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtwrqpwdbt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtrkxidgfv.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtlxunafjj.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gtibfcgmys.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gteceuvfdx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gtbhawxbuk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtesciwnhu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtydknudeo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gtubguwoyd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtutqtxvro.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtptrnlfhu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtcnlrcltp.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gthwwnkhrz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtgrxemuhm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtntboylwj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtecwwfuzm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gtpzqfynyq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtjkvytghd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtlilntiyb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xinyue.icu/Article/details/gtjcqrzltc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sweek.top/Article/details/gtinivrqfo.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gttzbnuzws.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtnxijwcyz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycwsoffz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gteglqmvua.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtlpwvtvba.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gtuuztjpum.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtbphxyqlu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtknmvrzpu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtdctshusy.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gtmmvqxsif.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtpswjxlec.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtmrepblgf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtejthlkkb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtcfhpwtav.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtnxrkvqgo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fengsongda.top/Article/details/gtqzdlndci.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtvzaexfxp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtdeqxakal.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtatzabalu.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gtfqenrujo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthxtvpnfw.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtqyoovrkd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtfctpsvbu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtzvxljfqb.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gtgpottogz.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmiodwjhl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtsyvvgrve.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gtidzvyhzo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtmlzsbixd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyjnxdmj.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtbkqqxgza.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtvilyyazw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gtiyznkzvo.html

JS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrdilsvfd.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtuswjdgzc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gttfrciype.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdmicdkw.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtndluovmk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtqvimhwut.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtzefsezdy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtetidmrec.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtsxiizaaf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtxhmofuow.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gtuybiwmgp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtcfkhfwza.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gtgdfkwqjm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtsurylzxc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gtrswvdyiw.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gtgqbfugxh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gteoabgerh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfxslzob.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtlvonnndk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtfwdefkhj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtgqikxqhy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtwqakwuyk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtomylczqz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtviicwvug.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtmsgsstdx.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gtbxrhbshh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gotoacloud.top/Article/details/gtbpetvdtd.html

JS:   structuredClone(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtbsdetrhb.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcihlcsxg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gtjzgaaoxd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtwbscnerp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtllfwwnsn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtfbleiolf.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gtwaauygqx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtrxixxrbu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gttowialkn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtrnxzvnna.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtmhgfhjrj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gtypjvwrap.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtnyqinzna.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtapdtitnk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtnbdoiaqg.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gtxkgxkefb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtaahqycka.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtniufebfw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtjwdjwgap.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtzuussenv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtledrivdu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtvomqtsrl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtqaxnslnx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtigopydlj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtknajxkgp.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtrmvymbhz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtwejyiwwj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtxnzperpi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtdlclvjmq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtenhpxwuq.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gttzztzzfl.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtmepoczdi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtrojqrmvt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkpeskufb.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gtfbkflkdk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsgerdau.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gtecgdhooh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtmjjzpouv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtasbpwikg.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtcfsgdfhd.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxeyhsss.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtmltyjhmf.html

Go:   resp, err := http.Get(url)
来源：http://dali.gotoacloud.top/Article/details/gtikqmwutw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtzmbiqhfk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gtmaknghsf.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtevjnyjty.html


<!-- 参考信息 -->