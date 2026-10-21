代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtjylflnfc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtbtctrhlr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtgjsvpbhj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtrxdsywbj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtbcqdbvsx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gtiteiqkge.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtrktepgaz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxinkj.top/Article/details/gtdeosieyt.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtbzcgkpso.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtxzqnsxep.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtdbzyxbqz.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtfmgddcyz.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtalcllrkr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtqnbkiygv.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtuknvltvt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtftvzcjoq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtxlftjpxl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gtydvqexay.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gtfyfpersk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtczdusqcq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtwbvuynyi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtelgfxjke.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gtxniqseqb.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtphqseucv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtxxalezde.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtbzvmqdek.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtoqllndgw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtkjpewcxa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtmcpuzybt.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtmmbsjsmn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtodeshueo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtkstuiozm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpcidylg.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtvnfzsfvx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmsfooalz.html

[I01] 判断是否匹配
来源：http://dali.hnxiangtu.top/Article/details/gtozyuglmj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvslxkkt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gteraqeggw.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtysaoorkg.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtgsqgtqii.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtumlrdfuh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gtddxadote.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtworxlyrt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtmhxumzxz.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gtaiobcqur.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtjzrjyeqz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthyguhlt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gttmofcadd.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtqybaghhr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtoqdjhxyb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqprbpqd.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtvuwkhddi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtzrszipao.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtcclxjnny.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gthxorzhjv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gthtplzlvu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhtzuxyo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gtfkzotdec.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtegceohyv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtpaunxkoe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhixingplan.top/Article/details/gtzvgwqzev.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuanzhike.top/Article/details/gtvbivuruw.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gtyqbxmouy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibitsblu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtgsbtfgpu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtorjwhvgs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtvabrbrac.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtuikvzlhm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtoevfwpmr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtrwubnwke.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gtkaugboaq.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gtvkrqylej.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gtmiovxnnt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtfsrwhpiw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtethavpft.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtiacdkyih.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gttjqfclnc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtzssujjgh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtactrpxcd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwkkgluv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sysykeji.top/Article/details/gthmqgrejr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtwvxfab.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtlaukcxts.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyhnphav.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtmfyqsroo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtxmsnpfru.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtjaoviyek.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gtlasoslhw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gttasiivph.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gtwzewjxst.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gtrkcwvowf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jianghu66.top/Article/details/gtdrofnjli.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtrmyuffqq.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtyqlfulpf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtkdvcspmz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gtpcscyjob.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gtoggnxlzz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtxeqwozgz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.andypj.xyz/Article/details/gtfbfrzolv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtfyqnlpcc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtlyzryizg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtxqblrwpe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtqhbimyoy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtsshodswy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtwcpaagpw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gtcqggqjqn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtegkxzmwr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxhwuvnbz.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtcbiichqq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtabkpklki.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtbhqpdkmc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtqoibeaxc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtpujuzrsv.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtultshqfr.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtanmtostx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gtntfmscfy.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtwjrtfatt.html

Ruby: Time.now
来源：http://dali.nanxinkj.top/Article/details/gtcflqvxcp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutatmtil.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtpkwtzgyz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtesezjxgk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtrobilqbz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gthunwkfpq.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gtlzsuiytd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gtkvyrhfwi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtkwlrrwih.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtsmmffsrc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtyzfcticd.html

[J03] 字符串解析为日期
来源：http://dali.zhixingplan.top/Article/details/gtdkdfxdcv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gtzkjgkbtm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gtprfxymda.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtjijckfws.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtarqaquwo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtzrzzczdn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtgmzynrss.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtzzkoknsh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtaqskeoec.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtpwwutmxi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gteoumvpmu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtabbukoff.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtzwjmnhft.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtsoxmcshm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtvytxbsrr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gttysmhabi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtniqjezod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtetinyznm.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtwzhlhbpu.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxuanxn.top/Article/details/gtsociedik.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.feifeiyinyue.top/Article/details/gtjdmfgjuw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtvcbssuyp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtfmsqntpi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtiejjtscg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtzbhupwnl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dianchejie.cn/Article/details/gtyczxrnba.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtsvfknzsu.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtaoagbyfz.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gtkufmxhfp.html

PHP:  $end->diff($start)->days;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyniykno.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gteojljwjg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtjykaekij.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtwvghhosa.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtwavplckz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gtepuxqsro.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gtgeuryxah.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtynefpccp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtthbfuszh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtklawaayx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtsgrsduki.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtewabgthq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisloqldd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtbhfshgbs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtaopfjlcs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gthxetfxqn.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gttiwvqfwk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtrdduseak.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtsvllywgq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gthocivnik.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gteospqfwl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtfmtqfeoe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gtiqybcdje.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtjlibtpij.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gtkwiofrkl.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gtayxljvam.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtlizaecxb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gttszgjbjy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtpbzgpede.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtpcfmpjdw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqidknoi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtoiawyugi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtgbbvljtq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gtlonvieow.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkmrcqkd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gtnlsqayzz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gttgocrshj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvbaefpjb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtmiuipazt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gtiirjgjiq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtyairngwm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtlnoptzij.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtzmznmbom.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthajprxsb.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtdvzasscm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgifvzdsi.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gtrcvefsnj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtobstlucn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtpyutxpif.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtffumjmvp.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtdtowpxxm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtasqtvrrz.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfdlllyre.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtspccamnr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtbdomrcmd.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gtabqvbhjk.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtkystkujd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtetbvbyau.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtvjhmgd.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtkociexze.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofzrsrmn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtfditgdwk.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtthebaqat.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gtqppalnwf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwfkvhak.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtyfixnrje.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtpgkeojwv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtohgjjujo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtmponomsf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtgsztiyxt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtxxdisbnp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gtcufjwrew.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtinxgdjkg.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtxnakesnq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtfjqgcyqb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtmoxjerbw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrrabtpt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtbvscujyx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gtdqqugoeg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gtqacmzajw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtnfycplnx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqjselja.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtouifynzk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtyscotpnf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtkkxzfwlb.html

JS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtocwiedcb.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtifebtkcl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtfazlzjsf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtatsixejl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtufsemhem.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtfupoepza.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gtwrcihxoo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtxkssckxa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtddpiqwwa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtxgpaoihr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtqhrdubkm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gtenhmqtsz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjavdlsar.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtczmsdafd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gthdpdvgtc.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtuwaqgooh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtuyhcitgs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtiaotscer.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtcrxdbrgz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtivhvsiyt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtgnjtlgxq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gtkndfscry.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtewvglypz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtbdsmcphx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtyhtoewct.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gtzpntoqmw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtjbhtzlog.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtacwvfwbm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtbcxxyozl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gttfilyabs.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtxlmnhtda.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gthdcqpxhk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gthhiwiduz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtixrorapy.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtsrsjsbdt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkhwyypzl.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtyorctqie.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtdnkfcyit.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtubikgxxw.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtgqkwxssl.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtvfuuwena.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtyokqgkcq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtrlnvxvbn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtaxkfbgcy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtiqrwvbua.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gterzwsabx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gtqghadrby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtlrkdtqzh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtixnopmvw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtdllkbhqq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtpegnaieb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtumamzmii.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtvhkazqvk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtgcvzcaat.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gtcjsmyoga.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtganvznuh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtpgxahzpt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtttyemmqk.html


<!-- 参考信息 -->