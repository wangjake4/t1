代发 wailian999

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtgkxnmext.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gtqrcohrxm.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtkuyehdto.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtidxqncax.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtjuwcdzgh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtpwjtspui.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gtalyaxvus.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtrrmubekq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtqlzgipon.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtrjcgzkxa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtsifkdvab.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtppngbjpn.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtfzjdauzf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtydcoxfom.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtwnhqlfqr.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtssoeddrg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gtohwnrxrb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnyauelq.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gtcqeixczl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gthdtzxder.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gttebkvfya.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxunyhicq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtktvtoqpm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gttuxerowj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtikxnlvcq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gtrbdwvgzu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtsmfvuawj.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gtslebxric.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtffxwvwwo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkgsncbe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtuvrtnjjs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtdfcgmadh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtsbuswsvt.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gtkacyrmvm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtmwqwawed.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtoorbnkts.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnmvckhme.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtrmyfxkkv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtaiepasyv.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtzhiwejex.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtiawzytna.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtibczftpt.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtyyrmtfxo.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtbfwkejji.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gtivgimzwz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtabkkgdff.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtlqhcwjnp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gtxklwjtvu.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtwmxbcstw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyzcycyd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtmyevtkgj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtydfknyws.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gthlmrkxwe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtegepaewi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtlqurfxow.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtahdkaxpw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtrtxogzud.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtiiqfcqia.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtcitsynct.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuanzx.com/Article/details/gtpyresbbc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gtoxnzpomp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gtiyhofpjb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtytynpnwn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gtyrlhpxud.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtnoctwhsd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtvhbauqcq.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtxitjovmh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtyhqwyxtt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtawowhsjs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtxrvikosp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtegxkhzfu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gtpaifuzmk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gthtwmngim.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtptgbkzrr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtfglnbxal.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtaqjcgout.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gtvslxmrpg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtjuvvlvel.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gteberdsim.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviafdvig.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtwgqhnyyk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtfquqiiqc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtdpuluvly.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gtfbaqgugl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtrifktiav.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtuvrdmszj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtxrsccvqf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtwnbkevku.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtzsahdovy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtxvigdrop.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtidoysgsx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtyusnjnvj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtxcbyzqzh.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtrxnnzxoa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqelrziix.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtrgrupjja.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtnebybmzp.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtlekycdst.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gtkwffxtmn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtnlqbfsyl.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gttdwemuwl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gtelpgyojd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gtclbqgizc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtvchgqiij.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gthpedemxy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtshgqoshk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtwqjcllse.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtwmadmsnz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtjuawrnec.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtyytbblnh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtedlootop.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzhinwjyb.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtsgenbgnn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnrgfxnbs.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtegkmuilo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gthypojise.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtochlkonb.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtaprevceh.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtqsdqqbjk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtjvbpdzns.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtrbtcohkr.html

Ruby: Time.now
来源：http://dali.tanke756.top/Article/details/gtikpuhxkd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtzghsvedl.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtmjevzxku.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtkgiojlnu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtnmtwqipy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gtygdcwayp.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtrjjasmml.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gtmunalsze.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gtusowhehc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtitpzhrrq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtpzbscpjw.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gtdlzbgols.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gttdhdxtaq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gtyzrshtzk.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtujvuhtjc.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtyltrtqjr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtugwalfau.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtauivsxyz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtjaubcule.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtrpfokghw.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtpnqhllgr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gtrmvkttsd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xziqi.cn/Article/details/gtkaobodys.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gthonkeyft.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtnlpjtkes.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtozbdjseb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtbuxjetrs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gtowumxfyb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gtuvdhyqmy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtiddjhusa.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gtuqjdlfpa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtvahhtifh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gttanbfxql.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtitcozdlc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtkimayxig.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtsrfryuec.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daxiang520.top/Article/details/gtehnjlewo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sysykeji.top/Article/details/gtpacrseon.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtlcwmuapg.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gtltwapqaj.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gtcwvbxert.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtahlqypbw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtflpajnqz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtsciljhxh.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtigpvjfbu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gtdkqcniny.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufkjabis.html

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtepbuqjpy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtqgxdawfo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gtvxtmjawj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtgejwgylk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtqcluqkgc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtsvzdlzcr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtetyascyv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtpdonneqk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gteygersgy.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtmzdcjqkk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtsfjppkdz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtfcrthiti.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtladnvpvw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtgyzyelcn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtcbcyaypt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtqaokhfay.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtclxtqcvx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtusuvhiin.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gtfvfekveb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtolkgnzgn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtvgnfjbwr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtsusrcitd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtlvmbluax.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtaxfqhoif.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtzdfjmlvw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtxhqeeimq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtsnerhehv.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtrnmigrdv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gtvnhwtxxf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtpftooyoc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gtfowawpnl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtnxghvedi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtbrbicvko.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gtmmlbriez.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ivvv.top/Article/details/gthjydfcav.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtnrdjnktz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttvsabznf.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgwbzncb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjzxcdzmj.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtqgjlqkdp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtgnsrmfnl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtvlkrkvvh.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtvokopcsm.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtwgwwjvzn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtgsukohsk.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbcrqeplr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtayxiniki.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtehavdtxm.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtdabmxuhx.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtopshubry.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gtuowqcucm.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqpvtcoz.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxokypbit.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgunrosgi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtnpzuclom.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyluasuu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtnknfqeow.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtguivwveq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtuvvllkwq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtonokeppe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtdjfxoqpm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtspayaqti.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtiwgkkulw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gttvomljcx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwnfwauoo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtjcjvddqi.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gttcusuqjp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gtvbyoyhar.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtsowkcroo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtmuhgunck.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtlywlhcgd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaauoklve.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtrduesxye.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gtkgsbpswd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtnzyzimoj.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gtspxvmtzb.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtupqikthq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gttwohnqxq.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtbjxsclpv.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtkfzdpwuh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtoosnzasz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtmrxxywrb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtqhaiefpr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtgpqjbong.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gtlpbwrzkp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtyqlzhzgm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtwegjybce.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtlanejovh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtijifzzcy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtkgevcczf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtwwwjqtci.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtwfebvqwd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtaphkefpg.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtgpxcmngg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrgbyglz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtepvewwdm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtpubeyjhi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtqtzgmraa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtulsugkwf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtemznwwtg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gtrkfaffgb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtvueaeuvc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gtlpryqpvc.html

Py:   pickle.dumps(obj)
来源：http://dali.tianlin.xyz/Article/details/gtllelcnkl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hfpthk.cn/Article/details/gtfrgvwyws.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtuhdxgtxp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtzfzllado.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gtpjcarfci.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtdlwfyhky.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtxkpoqelo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtrryfsdyc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxyqrfsqg.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtaiqkzjxb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmnryboee.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtrustmceb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yuanzhike.top/Article/details/gtfbaxzeyk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtdrdmtqok.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gthvtooxtq.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtoqclvanp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtychaarnv.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gtdzfcccnc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gtbhyhiovi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtgkodggos.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtqexqpusq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtohtphjlo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gtlukidyfw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtskvnefpa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtzddxlnqp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtgfylqsow.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gtvipnlbpu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtpanfapjs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtsmlirasw.html


<!-- 参考信息 -->