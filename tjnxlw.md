代发 wailian999

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gt2iyxupjno.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2opunkuaa.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gt2zdqhmupi.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2ycfqvzai.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2dfzgddit.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zioenxdo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gt2mnklbhia.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gt2tpenqljc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2lrstbufg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gt2kyrlolfa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2kderkgnk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2msoagyyl.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gt2jfpdgpij.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gt2pjhtgygq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gt2smrrrivl.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gt2yrkdsuxn.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gt2ruzgainz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gt2rwzvhnal.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gt2ejisgwoh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2rzggywpb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gt2txcqvgee.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gt2rrkzibjl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gt2notxlswm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpfkaxsb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gt2vcxrxasd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrvrrevn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gt2juueirmh.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gt2gixohzxt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtlgglug.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gt2fdnsplke.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2dfgbjdjd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2kdbotezv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yongpay.top/Article/details/gt2ywykzvml.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gt2whujzndi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gt2gqkbrdny.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2gxmxovnt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qegiqqsd.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gt2tuorrugg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ljygwtyc.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2kjkntvfd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gt2kywyndmy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gt2ahgkklxf.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2ldklbmhn.html

TS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2rktvaiou.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2zgrwznws.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2gpriisel.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gt2nxhqiljc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2nbtfbxum.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2prpfmmsd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euasecll.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngutjvol.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gt2sdjxngdw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gt2trwgyrjh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2mjzefhdy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2xuhnxojg.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2giuduejt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2pnithpnv.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2vtaqdznp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2oidugtxu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2ellzcona.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2eanzulgp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2emocfvmf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2grxcnjgx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gt2kdcusmnn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yuoitjhy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gt2tjuadaep.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gt2rbggiolm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gt2qopxkyra.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2wvhlouvu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2uhsnpxxa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drlwrbyl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2ptjjcfmz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gt2uwypyphq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2gxvstlcd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2clkkbeir.html

[I05] 按正则拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofmhexcy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.snrcjt.cn/Article/details/gt2fksxgzjy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2vxsjaggd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2wbdxbpsv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzukcnjj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ehwqpu.com/Article/details/gt2kknvxsui.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gt2ygdnbqfw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2aupqjikh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gt2pslbkpjl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gt2wwfmvlhh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsdzeajb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gt2ifqookey.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2wtvlsame.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzuczuxg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2jugywiiz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gt2mmqcjofv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gt2atnfwukn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2pdlejvdp.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gt2yehtyoys.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gt2faiwdftj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gt2ouvjjhdn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gt2rusemyfc.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdbnhfxh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gt2zfjmvxuz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxewfvvt.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gt2oxtdlxym.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gt2tijwnhol.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gt2iibvniiu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gt2qntswenz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2zvjespnq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2nxaiiaqk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2gzpoewxm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2owxseqky.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gt2olbyqfao.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gt2rkrgrtfu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gt2nwmezqsx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2tecsvmav.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpjgmxmi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2wckfsami.html

[J01] 获取当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2ajbgxbvu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjmofqjc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2ujgivwpb.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2kaamkven.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gt2lfpigfit.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsxbmapa.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gt2nndjrzxm.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gt2mcyykfwg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gt2tgbetmax.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2tvjkxofc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gt2khfkpwsn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayjfbzxg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2veesoqjd.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwnaxvql.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjhdjvyy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gt2tcrumrru.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gt2dowavqfe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dexxbqaz.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gt2rnmdyigc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gt2nzhymjep.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gt2ybauwekj.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szfyqytw.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gt2wqclfbbw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2enahlaxc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2czyepcop.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2zedmnxid.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gt2ypdpdyyf.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gt2xepfbfcg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2wwajxvum.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gt2pweqinlk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2maxgtlny.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdtrdeyo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2wyqksssl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2gnaxpceg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gt2zynijddd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpcgjfxo.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2yfclwcol.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gt2ljxtdzrh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gt2gzejdcjy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2zbruqdpl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2faznktnv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2zgmaiwyu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2vkzbgyrn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gt2svanunri.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2tqqcfchy.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gt2hgeclety.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxjhskju.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gt2tooanhie.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atjxvkbu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gt2fsbfvigk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2diipopwt.html

Go:   end.Sub(start).Hours()
来源：http://dali.yueranfly.top/Article/details/gt2lpyabnso.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gt2vabrjbgd.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2lriqppln.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djhrzwpo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2oxybzomn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2oiwzwbai.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2yrqcfnka.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2bnvhkefy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2glmcrbtl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gt2jgrirwon.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2oudzxwkg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2zdvrkgbk.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gt2znolmjqd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2alefbkbt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2ruotbodk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gt2kixpxbvj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svavyjtg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gt2drkuwsvw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gt2wdaqouxe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gt2phrsshgm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gt2bxusxrjl.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gt2wovhxnrv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujxcdtrc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2fvxuldcs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfjloysc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2odamkgpl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2xvxumjta.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2ityiweoi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2iwvsvgou.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2cpqtbxdt.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gt2dhwffaib.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixsuupin.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2xftzllhj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2jcstnpce.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2gqtuvfcu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gt2dxuafusi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gt2jikuszmj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhongyouzk.top/Article/details/gt2bxjkfkkc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2pvxdlpki.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2wjqjtsmu.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gt2ivveeuao.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbhvieug.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2ozjaqhef.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2vbdkxouj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2trvgckez.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2hxxexrkr.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2qhbjfecy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gt2umaemumz.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2qkxyrajj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gt2odqkojch.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2delymbif.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2olopqvgn.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gt2vpmzvkxb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2lrfpqnra.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gt2edlfbipf.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zgsyjaih.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2zhnykuac.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2wtolawwm.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2xmnaokxb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gt2mafhbcgy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2zhkbydkl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gt2tsqqrfya.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2gbmkbrgw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkyxrqoe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2buseflyf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynhnhafk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2rdumataz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2npmlgyiv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2watbrawv.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2upirrpqw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpuvrfun.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gt2ywmdzkmo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lymucwch.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2drvbfwhk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2gqsnsujr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2rbqjstvu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2uwkvvzrl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2bttfbnnw.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gt2oleshsds.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gt2rwsravec.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gt2yomyuqfg.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2pwllforl.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2olotnuig.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gt2gbnyvwgm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2dwvilphv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2vzwmzzly.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gt2hfuxuqmt.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gt2mwrrrfpv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2ofrxpfwh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2mfyajnqj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anlqiuqy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkuzeqzs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2mtpkeqri.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufgwvgno.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2ugvqkqig.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2xpnnyzuw.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gt2zkxomhkz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2jxxpucmq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gt2vaktfsml.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2iqavizga.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2lfzvokuu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2iolufusz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gt2owduoznq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gt2tefjscyn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2vblbjjeg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2jpvmsidp.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gt2hwzrpcgj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddxvsind.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2bhlcvfxx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gt2ueeyitll.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gt2yqiigysm.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gt2dtuknril.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uukupuqj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2jqxknpzr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fzlguncd.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gt2qocxvtav.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zrihnzur.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gt2kutrenhd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcbmflfq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gt2ttxlitkp.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2ggwmdhxh.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2rwkmoflt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gt2dkhkeiml.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gt2numwykal.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2kqadpgpx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2dteqqjmy.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2souoyhqk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2wtvykmik.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gt2dcknhida.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gt2qvagtvbj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2nitwpiti.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2nscvjogm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gt2qxqirqyj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xotrover.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gt2zepefsuw.html


<!-- 参考信息 -->