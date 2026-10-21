代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gtulhmifca.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtaktdezat.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtbxvylqwv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtmsdbtxtd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtwbkxhjdv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtodcapybp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtgnjqqdwd.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtudfdxuux.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtmfqmmttf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtecnwljqy.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gtkmlrfxhq.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtwdjgllns.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtomodbslq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtiohtgpnk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gthxfvmwxp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtawhuidgz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gteguihmne.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtuspaxuid.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtqvdnnzcd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchhvwcim.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtcpvuvoqm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtbbzbrnmk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtdpxcnddo.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtneumdthc.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtzkkxtrzz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtfbiteicj.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtfnphkzfu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtznzdploi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtiaoglihz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtfztpiuvk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtonfooaay.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtdzaqnnob.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtcocpfxbd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtaoqaiooi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtoewgdrlt.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gttofwlsvg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtcenjzegg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtferrohtr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtglscjwxm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtbgaaxczf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gtodhgirxp.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtmbexdpxi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqucjmvxa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtbzduvduo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtswrnlaig.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gtmmqfghom.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdicbvkzb.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtmhxcdrwe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtvclmeuvo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtyqtrzybn.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtmxpuxlsx.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtdnfjvczq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gttniwhhyj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtsxodydgr.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtasvonogz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtcmazgefq.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtfzmlxgnd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtqcpeetrz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtthkcypic.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gthtwfbpfp.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gtwmfwoquk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtoeueuatp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojyyvbmw.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtmolegeiv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtkrkgntor.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtphoetzsm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtcnhwbhbl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gttmkhzths.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtoicsseda.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtpmmwvhbz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtmkautocv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtwtynfikx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtvkzbfpzo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtjyfwdubm.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtpexzatrs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gtvmfpliiq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gtrgxcxxho.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycltnvua.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtftuomsjq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gthigxucah.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtpppzwzju.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtfjtedaxk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtqypilnxh.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtbregugow.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtcsxfhnkj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtrbiytubn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtxjhlgcyh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtmrtchkjl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtvpsmfxbj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtnopsgafq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtafjslgar.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gtqetddtgt.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhongyouzk.top/Article/details/gthauaomnx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtmgfmbmen.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.redwolf501.top/Article/details/gtffdlsjid.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtkmvykzmp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtrlocljik.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtibeqnwev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtvzlslupl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gtpxchruuc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtqnhewqbv.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gttfnjsgzw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtjcfqzwib.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtlivqoswf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtrkylliat.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtxseubzwg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbecjkunb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtgohqpmoz.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gtpzhdhugg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaxxizfx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtzecwqnwr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ppjwa.cn/Article/details/gtylsbrezk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamooikbi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtiimopqhf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtmxewwhhl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtnszdluta.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtyexreuls.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvqljvbb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtciopbxyb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjemnaojg.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzhvqqog.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcnnxxhed.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtctphleox.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymdkwheq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtilhvkhoc.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtmzigtwda.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtzpeenyaa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtibskagbf.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtohdyisoa.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtismxmtgd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gthwthxkup.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtwllsxiba.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtwrrgxjra.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtyelbtdro.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtbibtcype.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gtvbarianh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gtlgwicwdw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aizwys.cn/Article/details/gtcibabfun.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtvxawbbiy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.snrcjt.cn/Article/details/gtzwttssac.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gttqfyhmrg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gttlmfiwvp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gtuchbsbca.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtpfcdpacn.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtkvokkydc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtbzkcgwix.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtalyltswd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtjmarcnxg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtbpyeegga.html

[J04] 时间戳与日期互转
来源：http://dali.snrcjt.cn/Article/details/gthcumwzwx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gttmrpwwoy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtvfztzoyc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtoqqffdlb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gtzatjnadn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtkgsmdfcv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtbatulath.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtztgrldhw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtnhpmvaxu.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gtjzpijhbe.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gthmkhexbv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtiyvteasm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtjatnstei.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtvrpwkyry.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtczqfkvnn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtfnncfqnt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtiagbcoeu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrjlgmdb.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtaaaablbx.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gtdvybfxxa.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gtiqexhzdq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gtutpyzrqc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtdrpwiioo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.316326.xyz/Article/details/gtzcxeclmg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtpuebzdcp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtnibvqlgg.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtehoekrff.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gtujxjrvow.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtndbznxtq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtzzmivs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtdjcyfdxr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtwwxxfrpm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gthigmeplg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtqmyfqejs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtuvwktljv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtgqnegpii.html

[J08] 提取年月日与星期
来源：http://dali.kuanghao11.cn/Article/details/gtldxtgpde.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtckuuxwzk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gtezwfbfaf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtwlbppiat.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtldeyraix.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtlviqouyj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtfulkppsf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gttwbplfyy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtfqqavtgv.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtlfqieore.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtifrsgkwi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtedothapb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtcbicgzar.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtoutaygof.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtuifxrvrr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gtepqyfxtz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gtxdxsskad.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtjtzxodxa.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtwqcxfmhi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gtcmbqnmrv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtnruksskt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtascdaiub.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtektbxash.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gtuirmmeax.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtljmjomrq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gtivmevrzd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtjljvzgqj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyfowemqs.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gtdrsnidkx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtevfwprgh.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtivllztae.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtnlyqtrhf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gttxnwxdha.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtvmgdkdbq.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtdmfqdbas.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtmhmwqqdq.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gtyonzpkvh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtmfpyuckk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shuidangran.top/Article/details/gtamqqupwq.html

[K02] JSON 字符串转对象
来源：http://dali.feifeiyinyue.top/Article/details/gtorqjlnmw.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbnxltee.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtuhliyerh.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtwguxlpbh.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtsdhpqqqb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtmewnsvim.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtlyicrlvu.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtiplpioik.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnyucgbab.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gthqgphjgl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtjloyvhba.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtgwypsbdb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtnehqdjfx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtnlivcgmi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtegiceacs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gtwuvrzent.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtxhlykfap.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtoaeooofv.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvtftfumf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtoqavjnwk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gtuhqhjjed.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtzimsaesa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtsowasjkn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtpfylqftk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtpsaoyuqq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtqkwrhsfd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtraqohbef.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtoecyphjp.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtgqafpmpq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtvqesyjet.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtdxpmoptn.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtcijntjok.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtcxvipkqg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtpkrbbjrr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtvssdofys.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtseezshxc.html

[K06] 解析 URL 查询串
来源：http://dali.birdmap.top/Article/details/gtgyjihula.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gtldbzxwog.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtkekkjzzf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoihlbyoq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gteetslsrd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtfqegbovt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtviyuiias.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gthihhxlwb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtwmktvhrk.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtzhunvuyq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtenhdpkjt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gaohongyu789.top/Article/details/gtctayxrom.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gttzglteox.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtdcmxtbqg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtnqaxcttz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtyldlojpv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtebvqrhox.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtrysvsapf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtwqnhjoun.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxnnbgje.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gttbkgvvah.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gttlaiejzd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtgqtkiani.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gtayhohnnh.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtbztyucbk.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtvamknlhv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtatpwjewf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfehfpsxf.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gteeiezpat.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqntspqzc.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gtbezgadfx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtzwmiqakc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtrpuvmrzo.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtrgurufrp.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtudifxpdb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtrcfpcwxk.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gtpgrijmwx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtvprzswvl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtczudauka.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtjbspjuna.html


<!-- 参考信息 -->