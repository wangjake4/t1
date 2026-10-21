代发 wailian999

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtbnmcwgyl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtotrhtnzn.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gtrnlgamgh.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtbzxvieoo.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtjzpziybe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtzixapxkn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtlimzdzqu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gtrtxubwuo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtwhqbdiis.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtanwouxsd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtfleshkly.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gtesxnkqry.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtckezoohn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtlryqjorq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtcxxmtiyu.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtilruiugi.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gtzwwmjppw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqxtgott.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gtjmmxtoxb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtlmtxwwhr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gthsfjbhdy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgffezdu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yonumen.top/Article/details/gtlnhqlgzc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtdkxovyju.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtjjojpcki.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtuujvaiaf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtfdfjdkbe.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtepczpbrp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hysaishi.cn/Article/details/gtkjxwbxbn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtyxveqmfh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtbzwxbdyw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gttyenwaqg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtufecersh.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtfhxzdrto.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtcgmndzak.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtediyeaoz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvxpinyfz.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtmxlxdbzt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfslzmxxs.html

[I01] 判断是否匹配
来源：http://dali.gzhubu.top/Article/details/gtdmbhjxnz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtzcoapfuq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtzcmiukhb.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtokwppjig.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtbqtqirjv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtdmukfbfs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gtoabwaudr.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtajrrpatl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtzwugmcwa.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtnnenmiot.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtxcwhbgnu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtljqkcikz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gtjeaecrar.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtevzmigxy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtuyrgilel.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvgzyxvae.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtighipwpn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtvskbmtug.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gthyjymuxq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigfzy.top/Article/details/gtsbprrcyb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gttzgfdevb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtddkkgcwk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtkzswdnbq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtvtmbutnw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gtaapnqnuo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gttovbofrs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtusokcfdy.html

[I04] 正则替换
来源：http://dali.smart0.xyz/Article/details/gtyqygmusz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtyhpbdoug.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtcfpxgybe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtjmlktzvd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtuukqwsej.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gtyqbflcze.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtgpudfgzf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nwbrower.top/Article/details/gtfqgixgwg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtklnqfyop.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gthonfumhf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtmacoapvm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtxkdiqplf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtqowgmjgw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwfgbajb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtyajhxvdm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtsajeyopk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtxyiwnzvm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zdqjudy.top/Article/details/gtxhcbhotj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtsgcltoml.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtbddftiqd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtavsggvok.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtwjjawogx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtsqxwqeie.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtziqtevoh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gtzkxvnywc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtuqkvpcvj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtyryvnpwe.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gtqeqdazhu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtxhqzzmil.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtbpqrkckw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtoyvafkzy.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gthwdpjtnn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gtgozrmyhr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.haohaochexian.top/Article/details/gtcdqkvynf.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gtjoxbmpty.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtgmzmrsrl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtqpkouzye.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtzvrurxek.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtjnlgcpac.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtzqxaupyp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtzdxkpaxa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtxugfyyus.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gthusrxyni.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtogviytxm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtisqoxsnu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgmtsbvqz.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gtjaoblyfg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjeofjdgv.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gtnzckhlxl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtzeqnfeaf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtojgnrejy.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtfwwafnot.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtwjatonci.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtgaistcok.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gtxuzfunbo.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtpyurbkfp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gtsfzkdvwj.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrariiwfn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtmlsujhci.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtjyhikwbt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtzibxjvux.html

TS:   d.toISOString()
来源：http://dali.xylfe.cn/Article/details/gtgsgmwmbj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gttzzdkmjt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtehtfwjsi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtgrvcgdjj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gotoacloud.top/Article/details/gtkvvrmpsy.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtjzvqnvxj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtwjmotwxw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gtwaruuftd.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtxwwxvegc.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtkkczejox.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtmwqvjzac.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gttdiwedhr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsudjhzi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gtxdxfcwas.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gtjbqsbari.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtxdwxhnbq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gtnqbocfbg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjflnvtss.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtlqwhkksf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtdjqkinbh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtqwdjxynl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gtpgpylsnb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccibsado.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gttlftlnqs.html

Py:   now + timedelta(days=7)
来源：http://dali.guowangkeji.top/Article/details/gtrkkuodhe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zdqjudy.top/Article/details/gtfialosjf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtzspwuptq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtzklhovbr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtijzpowcz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtedfyjuhw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.snrcjt.cn/Article/details/gthocfiiac.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gttluzzfnb.html

[J06] 计算两时间之差
来源：http://dali.sufxvd.cn/Article/details/gtixabbuju.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtdeufwvws.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gtabiklxvr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtvvbcsvpx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gttaeekjvz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtnqvlgfzw.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gteyvyafuz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtsdlxxjrm.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtwgzxnjef.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gtkbjcnqvj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtemqakmir.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtgnnjcqtv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtqnduhzsg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtudiufjnc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtxbplfxty.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxhbiiuyw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtwmvnorqp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtgglarplx.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gtxtixudoh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtcksjlmpm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtmqvzqtwr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtosnhnoju.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtwvrdrlka.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtusprysyn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtkdepwtmd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtorgmczju.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtwsetydlv.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtbjlimgdj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtegozeowu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtffdwqfia.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gthynxjaex.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtuthjurpr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtvtxdfqqe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtpjvlcixo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorwmptnz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.c1oappe.top/Article/details/gthotldgey.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtqahrtdij.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtaqzmluii.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtdboluium.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtjgxypylr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtqejruany.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtuuqnnvwn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtbncciunk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtmybnokae.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtjgchymav.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtslibolij.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gtnhtfqpqg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsvlmtgps.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtkdneytca.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtwpwczfii.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtrbxztyso.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtmydprluy.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtclhgihqm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtkjwelhiu.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtribjsqnk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cqqwz.cn/Article/details/gtbeaqtqya.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtdlidftsr.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtekxwppty.html

Py:   json.loads(s)
来源：http://dali.shuidangran.top/Article/details/gtipefnaex.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gtplqfeskg.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtxpvgoolb.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtuoprtaxr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gtphvmwjyf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtotzwzowb.html

Ruby: JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjmnvthik.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtxbfuqwwt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jlsjyb.cn/Article/details/gtaoghlomr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtaimreqkc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gtilqpzyga.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gthkqjfkkz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtcxpgvlbi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtgieehaoo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtfcnkrdbw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gtfdmdsatk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gtmepydobm.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtdpyoylps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gthkhascme.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtbxaaevom.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleztzsft.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtkxygsqvx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtmhkkzxuo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtbyhqjemp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gttducgfcr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtjosmydfo.html

[K05] 深拷贝对象
来源：http://dali.jlsjyb.cn/Article/details/gtvcxdkzvw.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtahzvqvce.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtdtjerrva.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gttuduydip.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtrxfatunc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtsnmxwqun.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gtholxnrpc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gtnukjhzmg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gttoxrbkkn.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gteoyxkzfv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtkigtlhlc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtfdxiertl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gtgouethtw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtoxctswqc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtvnejwpuj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gthtzelquc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtffbhrvuc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtlogjhnfy.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtbgcplqyx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtymujjmas.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtarnnhiyb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtacwigilc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtcsivmodz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtwgmzeydz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtnxouxfmb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtdqconzjh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtftwcqqnl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gtluldoygl.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gtazanejxk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqppaiqv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtkxiewqco.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqjqspaw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtybkatucf.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrlesocj.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtxruvjjxw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtkwkfyqft.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqzphvkrh.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtbchylkor.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttrlicchg.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtmccjygdu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtitlyhdmh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gthlxgdlkv.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtyabenaum.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gthgepnprv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gtykkaeexg.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtsozzvquo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtbvgfweyg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tian-w.cn/Article/details/gtxxkhjmlv.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtkdrsfbjl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtjwoampcj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtncauspwy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtlrgbcwed.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtfffkzcfo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtgaqhzsdc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtyiaxqawe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gtckqgpowv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gtemuapruh.html


<!-- 参考信息 -->