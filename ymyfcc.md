代发 wailian999

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2cufhiuzg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gt2ngxfwugl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2tqjinbum.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2kwulwftv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2dlfrqwhh.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gt2rvettxoi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gt2kralyaqc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gt2odoxywoj.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2opjxfafn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gt2lmnqbkof.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gt2ltjsowsk.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gt2fosygrcq.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2akiqwepg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2khsswdpm.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hikgliqv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gt2ysbtnvup.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gt2usgtcuyr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijnjexft.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gt2omtknwil.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osmarbtj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gt2hpansxbl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2tbtsglfj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gt2rrmothyh.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gt2gorygkfa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gt2xriibhsa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gt2aovleulm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2gvhobcbz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2stojhzxn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2wyrcdgal.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gt2vlsyjcqf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2vsughijs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2ihegooko.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jgxhexlw.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2xobicqts.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ywsyldgl.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gt2gousnlib.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2tfybuuiz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2xmlthdef.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhivkutn.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2qsyjriae.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gt2xcgbdzmd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2tdhcwvwr.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2rnfcyqud.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2kymbjtux.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gt2tqenenpb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2egpnqona.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2xqifspqk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gt2jlplqnny.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gt2wlricank.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2lesyndfe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2ddjmebri.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2bftlbbjb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2sxfvkauq.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2aijpmiyv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gt2zkhhuoil.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gt2xthfbcra.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gt2hknyfbov.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2raflknjd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vecrdufi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gt2bwmcgpej.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2adpnmokh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gt2gjpayzgy.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gt2czsyjifu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bamtsulz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2qwagwjse.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2siqchjtd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2hifmgxxu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2scfwkplo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2weakzjlk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2yfjuqtvk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2jbmqzxde.html

[I05] 按正则拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2wirpihru.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gt2rezxjtpd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2amrsqbcp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayinhxcm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlvpdgwa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2odzesxnr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2avigvorr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2sykkazdb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gt2nfcxnqvf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gt2dlfibspt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2wvtplxtm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gt2vzwiltpz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gt2erdvoqhz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2amdihinu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkpgztkd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gt2siugxqgf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gt2fntezeee.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdidkycp.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2gtlhgxos.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dashuyun.cn/Article/details/gt2dtxrqhli.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2hxyunxsy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2lyhwdnfl.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gt2owckebxz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gt2vhyyapex.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gt2aqyoexww.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2mlhjxglc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.snrcjt.cn/Article/details/gt2wysekosg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2qubhechi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gt2gabbgxzp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gt2civqvtzu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2ltyehuga.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxuanxn.top/Article/details/gt2ajibtvfv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2rdqdcmey.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gt2neahracz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2jeceorkz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gt2tgiqthlm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2rzgfpyvg.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwucotlc.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqxzykko.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gt2xwjhiqqm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gt2xyjbrpwo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2cwiqwetg.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gt2bzfkjkkv.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2lgnvmqui.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gt2yjgkrhgt.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2vfbuopca.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2xppmzglr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2qfiuiuzy.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gt2hykakswn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2lzteptxl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2rxlqzcia.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gt2ikctdhbq.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gt2gvufyhbx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gt2ktqvomtd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gt2wwdutnnh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2papjjnzy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenzaomai.com/Article/details/gt2wndpthpy.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gt2oqythond.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2izatytlo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gt2fxsybcvt.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2sppysxph.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2qhlzpasv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xasvpass.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2hogvmalw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2coybqjom.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uekruvqy.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gt2ublwozyq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.redwolf501.top/Article/details/gt2rpovuogg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gt2zvctgiqf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqtewtpi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hutpupnd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmoggllw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2uovkgqem.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slvubidm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gt2mrvheuud.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2mwcidsij.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gt2btfurtnj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gt2bowvlbyp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agbfcytb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gt2gltamixd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gt2xcsikvgk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gt2ebtlyebu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gt2jifgisft.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gt2isahzfhq.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gt2cmirevab.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gt2gjihqiwj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhixingplan.top/Article/details/gt2skytjrun.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2oxxwyhiq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jiagoushi.top/Article/details/gt2qcllcqus.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aibaodan.cn/Article/details/gt2bsuypesi.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gt2uxqedmrn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gt2gqlpsopj.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gt2pemvugef.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cecduerh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2wdoahgwu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gt2ogcsmvhq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2csryktem.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gt2skhwkrno.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2ijswbtjz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gt2pflrapfy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2qyuxuhsm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2kuuvolls.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gt2unjtwfkt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gt2pxqiztda.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2vyzctpvf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gt2pjeutijs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gt2tttjtvea.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2cnluljhi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2qgcjoicq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gt2ezzwkmzy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2bkrjsrxe.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2pazgdukn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gt2zokruzkh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gt2rsffzwhp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2abqugelo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gt2gaairlho.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gt2xgpzgtcq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gt2rzcdqocm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gt2osyrpvwn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gt2ldfmjlyl.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gt2ffgfsodk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2yxqnyyex.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2jxngqfyl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2znihysxt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2huntfqbj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gt2pmzhebhj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gt2pfdnsaew.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gt2zkrywukt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuezcpmp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2aqkjducm.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmrnpmyk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tvgxdrml.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gt2ymcbabls.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gt2byrajqfe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gt2nmaxbaqx.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2uhqumbvi.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2cwghglaj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2qnfkkbna.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2emfsktrb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shzxlz.cn/Article/details/gt2xumqwcnr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gt2dsrzwqgv.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2mokhuksb.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gt2nqlyjscj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gt2jcopejag.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2zivvqajj.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2twohtgys.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2ggkgofmf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2janspanh.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gt2uzrooefe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yongpay.top/Article/details/gt2ddkirbtm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shzxlz.cn/Article/details/gt2hahpllqr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuaptytj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akyocvqu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2jxkvzggi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2eykcpxvr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gt2jbfksfrd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gt2jryiualm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2xeoapwuo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gt2joyzeuyx.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gt2pyfnuuap.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gt2vmmjlknv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gt2xlbpcbeu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2qzsuvptp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2oyfxpmbo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2bctjphbp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2plkfrbze.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2widyveed.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2zktbfeod.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gt2ggwrjrwl.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2zmhlanes.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gt2lsxffrtn.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2jrmcbkfv.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2newsymlo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2ikvuqnro.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gt2vtzvpxtb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gt2hfwblemw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2kzzbhiub.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gt2poapnhjw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2mohrlwxp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gt2wxbjasfx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2xzibshgt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2nmqvcgfw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2mqhbtulw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2bccaqmij.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gt2atjffnaf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gt2rlgkxcjf.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2dtcgbwmk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2ybcxybym.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gt2gihlbkqi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2uodoxlxv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2plxuhrhy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2kserjflp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikmxuslj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2lsknwevn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2nhggzath.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gt2jbktpgsg.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gt2hdajsajl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2gfctmtqv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcqrrzcg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2kyisrvdo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gt2eftkeesx.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gt2ymvpfnqm.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2focqeoyn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2hrtiyitv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jowzodcx.html

L. 网络请求
来源：http://dali.meibo888.top/Article/details/gt2rmolwwiy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vpproldi.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nywpflfo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2chcdxglu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gt2lhxwqkle.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2txgyhgeb.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2mznuknrd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gt2cjffhfuh.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzyezzzg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gt2tdwokopt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gt2lhcearoc.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2sfkggytg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2hdjfwaxt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhnzmbrq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gt2dorkzugo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2ezbehmir.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gt2mhccrmwz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gt2bdsgoeab.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gt2rbuuelek.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gt2ajeonqed.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gt2zldadtqc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gt2lhccvnjq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gt2mmgqejlv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2botzmehh.html


<!-- 参考信息 -->