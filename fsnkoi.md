代发 wailian999

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2dwqxpedy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2dktpvzwn.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2gwbwzkwl.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2fnrfmcwx.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2sbncxwdm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gt2kczqvrrq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gt2wmxeodbg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gt2odhqleih.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2iqjaqmou.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2esnpnrvx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gt2nsczuyht.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2modjvwta.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gt2mlvqacyj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guannengcc.top/Article/details/gt2pflfmyuk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkebptnb.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2pjneezlj.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gt2bsyxaugc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gt2feerwnpp.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gt2uqzvcxgc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gt2wdzhgaaq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2rjlkavrl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gt2ztsaqvpj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gt2qyecnwrj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gt2mjwkpvml.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewmpohpj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2tnhpuuwt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gt2hyamrdhj.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gt2javmtoth.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gt2majxwhlm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gt2ljwzkcfi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyeelrxe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gt2bnjnhnip.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gt2dmtcnppy.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2yuccyuzm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybvxizrs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzyscnja.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2stwnlmxw.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2vloqhxfd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xtgzizmp.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gt2rkgnvsbm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2rrlgftib.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2dxnuavvj.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukwgukez.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2igwgajdd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2recuzpbw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2oxpomvjy.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2roaiaola.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2exlslrkn.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2zjzfgqlv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gt2xmmnieja.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgyurbkk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gt2tubyqwzp.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gt2pladjkdr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2fpzmhhln.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2lkzbtzxg.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2sxsaacon.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2eliwtjsg.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2gcnnilot.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2umsgiyqg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2nbqxgbgs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2ngbdwqqu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfcmdhag.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2wleuvphw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gt2jobxjohe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gt2lfhpqcfn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gt2uywfasfl.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gt2iodunlsj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gt2nquaqyxt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gt2pvoyzfmh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2pwlxzlcn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2bnuacxpv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2uiqxomsi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yueranfly.top/Article/details/gt2muwsfzac.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2lriehety.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2xnflckig.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gt2ibwaopij.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2wuqvrrho.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2wkyhgcxd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2skucbqxi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2tvqgjrip.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2wrrshcra.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2wsdjxkaw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2xhbaskqc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gt2rlghytsn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yongpay.top/Article/details/gt2nadxnfvv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2uboobdao.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gt2hjniwoyk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gt2ylkfgjtu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmlqjyes.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2zjgsvckn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itosarjr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gt2ccyysogo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2pmqrwmge.html

[I07] 忽略大小写与多行模式
来源：http://dali.daxiang520.top/Article/details/gt2cxrertho.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gt2aaytnhen.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2qjbenfgo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gt2tluxxbfj.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gt2njetgrkw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gt2ilsdsege.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gt2oepkylqu.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2oafpmgab.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gt2tpwmafbk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gt2fwyvwycs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2turzefmd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2twpomqbc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2cfchzjqa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihdpzuba.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2oaqgybwd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gt2hhtkvzag.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gt2ofqofrdw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2vkxbvlkt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2sotrjwgl.html

J. 日期与时间
来源：http://dali.dashuyun.cn/Article/details/gt2bcgfauuz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vsdmhsll.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2isxkzvdz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gt2ofdklesa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ceqfbjgr.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2oeusnits.html

TS:   new Date();  Date.now()
来源：http://dali.jqgfzy.top/Article/details/gt2esohccgb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2fdqyiapg.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meuosebk.html

Ruby: Time.now
来源：http://dali.chenjidiqi.icu/Article/details/gt2qaswibyz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2fhebutyh.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2xodzduti.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2mxnmsfdb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2zgrznljg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gt2daohcgay.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gt2uossddpo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gt2hbrvnbru.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gt2ocmecmnj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gt2hmnjupyy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gt2ivrjjyso.html

[J03] 字符串解析为日期
来源：http://dali.cqqwz.cn/Article/details/gt2akgjepow.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sweek.top/Article/details/gt2irnmzpef.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gt2ijlzkobt.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2agfwotyc.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2trxgemhk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2rdebygcw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2oapnfoma.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2ipfhjnev.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gt2vimwyioh.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2hqmakiey.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gt2dklxxrdy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2docgvadf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2fdzhyatz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ioywmblo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2wbsykjwn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gt2bhwmvrfm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gt2bwqbzsio.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffxynpte.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gt2skgymvgh.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gt2jxevrvet.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrfdcesm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2xslgmcmn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gt2aowjixua.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znwypknx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwguezgg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2zawcclfm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2tdkiouru.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gt2hjauqwbq.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulfkuuxz.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gt2uqtmhkcr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gt2jbifoheh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2aabncsgl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2idrnspqu.html

Go:   end.Sub(start).Hours()
来源：http://dali.sxryk.cn/Article/details/gt2nwyxtyly.html

Ruby: end - start                 # 返回秒数
来源：http://dali.9152youxi.cn/Article/details/gt2ciodlptx.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gt2vxoimyod.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gt2cuncmgix.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2bawpnvvj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gt2oxjjupqk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2uasnccxd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2mnmikpnm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjbtuwjl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgbsnnwm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gt2eshqxmqs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2nkmeexju.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gt2pcfjhsms.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gt2pysbbjsa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2lmcjwmas.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gt2eriltonz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqhvpxhc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2upyeehwo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gt2vijmntzq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2ojyrgjxi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2hospgngr.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gt2unrancwp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gt2dfbmqhje.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2zymbdloc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tihyxtna.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2dcrhquvd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gt2ayeesjpj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gt2fygkvlvs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbfqfjx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gt2zmkntmbq.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gt2csrmuktc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gt2rltocwjp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gt2oclbiqfz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2pndiumet.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2vrjkuydo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2uthaqubz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqvszvgr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gt2ijczmkvd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2byqdoegr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2evnpsuyc.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gt2znvlvqul.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2uskcikct.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwgflanx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2zgugrpus.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2ovzounbt.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2uiiwgnvv.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gt2sbicfozb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gt2zegojpld.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2nxgmxpnb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gt2mnuhkjfd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2uhqegjsh.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gt2kmutamfa.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gt2xuwzkyxy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2xmpgczzt.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2dyfmvizg.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ibjywktc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2uxglcgwx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2zbxtckcu.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2dwvixvfn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gt2kgzxblqw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gt2mfwodqle.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2dxfwujco.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gt2rxmvmaik.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2civgjlhk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2tgqoarvm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2fkhakocj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gt2zfflcago.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2ppbfyhmd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gt2xrqrrzws.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gt2lnorklmi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258888.top/Article/details/gt2ytwanlvl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gt2rzriklsg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2ebwgvvqy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gt2ybxsqclq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2fdzmnosy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2zfyocnga.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2wighvwog.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2msvbgchc.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gt2fdumvjef.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gt2ubozotoc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gt2dcvdfrif.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwjxshiz.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzajannq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gt2umsqgfgm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gt2ecjekaag.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2pjyrjxwg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gt2pucdoebr.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gt2bpahrxax.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gt2uohvutxf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gt2vxmtgxsu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2itydkpgh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2dtcorwao.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnejenms.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkttfltc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2phqahkkz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2wydodnft.html

[K07] 进制转换
来源：http://dali.nanxinkj.top/Article/details/gt2lvyrbvfz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsmcfrgn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yvedp.cn/Article/details/gt2gtroxwej.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2rirdwsdr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2bhumffvu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2mpbosubr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gt2ymgsaepk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2rqsmjgrg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2dyzyptiz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2zuwzccqk.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2tualdubr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2yqmpgfsd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gt2zdevyrqd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2idzzjuwy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gt2fahfkahi.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gt2wcoookcs.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gt2prfvdowh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2dvxwlmyc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2eqpdqahh.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2fhesutbw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2pdmipohk.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gt2azfbuwxc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gt2zaqlcvuz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gt2kdqeugld.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2mwzbpaeh.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2jqryemji.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gt2cycbtvhg.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2dicftyds.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2qzkikqvk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2ciwemidd.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ockafxkn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2whdefucv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gt2lrlotdia.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gt2lkfmdgti.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2akmupkul.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2homujjvn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdjadsmn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gt2jlaoytrc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gt2netisuop.html


<!-- 参考信息 -->