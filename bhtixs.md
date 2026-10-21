代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtlfegpmzg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtbbcqixul.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtnhafrzqm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxfhutwm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtekfnrkaf.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtrgrhnitx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtcbcqjiwj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gtbtioasyh.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtonjobcnu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtgetpkgyc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfmwflzw.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtnmxnuqxo.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtcnauockz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtuheczzyk.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gttoelwpho.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gttqvxeiix.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gthkstvnfd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtbsyvibab.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gturimlkku.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtkdkjfhmk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gtdnhgxtgp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtgeczmwds.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtyjargcjo.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gthdsiuvqb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gttsruqyum.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtbdrrmzvt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtprlwzywr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtkznvlyct.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.havefunace.top/Article/details/gtuzhykwlr.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtcyzupynr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtmrxfkbdy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtwmaeprdg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfgwuyozq.html

I. 正则表达式
来源：http://dali.cashguo.top/Article/details/gthoztazyj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrbxsnojk.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtdvrvrciq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtohgvling.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuqmjkzs.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtcprjdwuo.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtnpxxowgd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtqnmocmiw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtkwebvcbr.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtgrjnwayf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtvynitcgq.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtbwimddyk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtpghedhaq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtgeaovbjf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtnifjeqcg.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gtexevgeie.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtdkfdovou.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gthzgqzsvm.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtttdawcfs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtyuzqtvic.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtzuvpqtro.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gttskksgof.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtblceqtpw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gtpehxdigb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gteosedwug.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtdlnpmimb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gtzxcijbqs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtgsnpfzco.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtxsxibqwe.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gtvsfhiltj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtzbqqkscg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtuupivyfq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gttzeneibs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtjrrozdux.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtqolwbiym.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmihiiyjv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gtvyltqotu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gtafjsmqzm.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtmopoarek.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtjkfofujl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtmcwapvqw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtaefifefe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtmjhmethh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtxuidbdrv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtiiilulrc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtutabadaa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gtabiidekw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shuidangran.top/Article/details/gtcryamjog.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtaskexxzh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gtzaztfpeo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewjrunie.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gthnksbiib.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtllwgokbd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtomaeejgv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gtyvxlmozg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtbtaqqers.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtittmrxpc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jyoumei.cn/Article/details/gtpmwznhmq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtwegfnlyj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gtpchotecl.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gthlozljso.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtcqkvywbr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gtswxtlphw.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gtzyvoovts.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sxryk.cn/Article/details/gtbxvewkvf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtpwizgwzj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gttklehzfn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtobzppxmx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtavyzacgw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtowcyhfka.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtizkvhnfw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gttvlwbwti.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtudgevjbk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtinmwbuhy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqdgxaxql.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtivnaasqc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthhgpxgew.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gtjepoxgab.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtqmtwkpjw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtaercnodu.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtvirklvfi.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtjilnwqwp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtrfieufon.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtgdcdzlxe.html

Ruby: Time.now
来源：http://dali.sysykeji.top/Article/details/gtfxvntikc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gtxjxyqhie.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtulnrrniu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbbadlty.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtskedchte.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aizwys.cn/Article/details/gtylzqoboh.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gttyssjupv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jyoumei.cn/Article/details/gthqufumoz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gtapxlzsor.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeocevtb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gtutosqahc.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtewtukhwu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gtdhamuzmo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtdydijhqn.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtyxinsxqr.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtxtewpxex.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtfxlybyif.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gthjsfqdxk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtwmahndje.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtvhtgghgn.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gtryqzprfh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscqxjiqo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtdgoxoevx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcmzmowu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtapnnjpbt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gtjnvilvxu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gtdqlkodmt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtqejfjuwm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtspgwbzez.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gtqiyxmhjd.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gtvojtapqg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gthzvzxmcf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtqtextgqj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gthlgumbrn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gtixvzatsj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gtmahthufm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtpfguqfpo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtdryeatfi.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gtiefpwdiz.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtpygshlun.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtqsbjptdk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gtspfuwvpg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtkswbackf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gtgjjqryhr.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gtllwdykte.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtvkmbvizp.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtiaqgpvxr.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtoxhouajb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtqgnthtuw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtejuqmgui.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtntlrgyfs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtergbzkwg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gtlxlaskzh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jiagoushi.top/Article/details/gtqhucvvtl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtnisnnhio.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtueybrwdg.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtprdrfujr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gthsuthjge.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gtyrcdshcc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gtdbujxarw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cqqwz.cn/Article/details/gtatyhyfjv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtpltowugr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtrnsqqgcn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtznfceoyg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtjrcibnbg.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtmpzgdbgd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gtzfaclmur.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtqzpocvot.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtlzheqwyh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtvphmswlb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gtzmrnbkie.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtaxygadez.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gthdbyngcs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtwjdmjtno.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtbfxbbmhe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtdebxzctn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtmbwjvppd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtrxbwyibr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtibvfhtue.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gturmusugu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtbuwwngij.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtopymgzri.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsbajsxn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrxttqehd.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtjwpcqjnw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrobbibkl.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gtexgumnhx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtvkkxrlje.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhclaexq.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtozpabznn.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtumymcqgg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gttixkbodp.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtywuxmfsu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtgakvnswm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gtnfvrtxsq.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gtkaqhbghh.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gteescdeuu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtmowadnye.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtiobgmqvm.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtrgqfdgon.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtsydrongt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtwjdjzaur.html

Ruby: JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtavpwomdc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtlbjvxykt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gtdexqteun.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtpmgejvxc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtlfrnxbnd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtsewjtbit.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtxionhxvk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtbtvxctkx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gtvtsxlebb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtlwimpobw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtkgxwkoki.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgzpxlyl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gtcvxtqikl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtvpyyosal.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtatcugjgc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtzyenolee.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtrwvmvuzp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtbygdecwy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gttuzruikm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtppcnenlp.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxuyxama.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gtudqadwpl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaedwayp.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtuwfvivsd.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtlsbwsdeq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtoxvtjirl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gtitqznwco.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gttmfylucb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gtcpuxqgza.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtwtmqifct.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtczygiazv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtqyixekmj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtkuegqwse.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtpyvslqcd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtphfbozuj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtkexkjfqv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbykyogwx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtweglxhbf.html

[K07] 进制转换
来源：http://dali.316326.xyz/Article/details/gtxvqvhsbp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtacgpesqt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtjddmzzae.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtmlaqckvp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtkqgkwfzk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtghcndwcx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gttpntvlmx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtisxzmhsn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtjjoioxqp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtwhrdpxih.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtgngeuedn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtbtpgrkqt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtkxndzwrw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqspvrpb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gtddpmyoxx.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtwghexqug.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gttodmlwoh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gttvxxjnnq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfisztmue.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gtoogwhxzw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzwknzdgt.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtgzzewruu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtwcsaaupw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtumwxpmcs.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtveclvrld.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtyulgmhbf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gteljyfuxq.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtpiaqvgfc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gtssudolyh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtvjuwmmml.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtzcmdvjlh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtygessauh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtnyfdqvvm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtsmocqjvn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtzlhbwvbz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtholnazdh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtazjfmzet.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyemmfnmp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gtqixpjzun.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtzfhpkxrb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtbqjxdfsa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtehvcrzfy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtxjanixjl.html


<!-- 参考信息 -->