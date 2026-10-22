代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gt2mynzthfj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2xvfywvol.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2owrwldyk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2ngjtmlfm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngqnlssu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2xadbavlf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2iioyzgwg.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2yswublht.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2sqvxwqhn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gt2jdkinmbl.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2qpeadzrb.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2osgagkxi.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2ktxcruez.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gt2fvbxrovt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gt2ummcmijz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdxdwgup.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2igoobxec.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2mjgikjdo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gt2lfjkbwop.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gt2ayjpkdwe.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2aywyytws.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gt2dopyewhb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gt2juthwitt.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2xqujlaej.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjauzfhe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gt2rvezgcpx.html

[H09] 带错误码的异常
来源：http://dali.yj20258.top/Article/details/gt2qccdwbth.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gt2trkglcna.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2mlyjorzp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2weoeiusv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gt2aygijbms.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttwyzzhs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gt2nabxxjez.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gt2etvfsfvw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gt2rimmhpla.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2sreyitqw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gt2xsijhouo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gt2zlmgaazh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2wuktiqqm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2izkwnkej.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gt2jzjwjour.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gt2gprfklqo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gt2qbcwsdkg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2gyzojgdu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2kkshnlre.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gt2ndtzbviu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2siizwnhs.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2kknstpok.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2qrzrheaz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mielvzrm.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gt2pxqvrcrd.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2hikcphjp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2pdwiobzu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2rlyikqyh.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2vcpigvjn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2itbsbrfc.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gt2lrlquwbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2jhzgjasc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gt2dxzfzymo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gt2hmwuocqk.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gt2ocduejcg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2lypcwalw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2yoilnipq.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2ghnmtcua.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2aayagdce.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gt2ujkzswfe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gt2omeomcub.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2gemuttom.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gt2kzqiwbar.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gt2nmuyrrjw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oummxiwi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gt2ivsmfyqa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gt2wtdqakno.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gt2pahxarqy.html

[I04] 正则替换
来源：http://dali.nwbrower.top/Article/details/gt2bpuahcep.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blmniyuq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2wqiyqvah.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2ecgpwftx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2swdgmwjz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2wfpzttag.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gt2wpjvgsyb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2myqadxpq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangdashe.top/Article/details/gt2zhhllpdp.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gt2geghqche.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2hqslelnk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2gorleduc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2fjqfebsp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2gjhtgbov.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqdjekht.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2jgbfspqn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2mzdftgep.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gt2sdysmosx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gt2osxqjkfh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2uhacrczv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2imtqqeaz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gt2nacusxde.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2tlvuxhlm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2rphtfgsv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhivppgs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gt2hkxvozkl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2dijjupxv.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2habqacjz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gt2jxavfcvz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2rkxffmue.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gt2htmekmkb.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gt2feolyfkc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tirgqpfd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqbnphcy.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gt2iwagsajw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2skduazvd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ehwqpu.com/Article/details/gt2paauoxvl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2xfumkriq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2spsursxl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gt2vvwsfspk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gt2awfxdzjg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2uoiamang.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gt2vgpzypgv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gt2yinbetbn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2azwdmlcr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xecsyzpz.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2yqioqahr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2vmxyosap.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcaxbquo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2jqlqzvbt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gt2svbwwxrr.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2ejbfrthi.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gt2giaupftw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2ttflhqbx.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gt2gezvbfvd.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2pfxkiepg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cqqwz.cn/Article/details/gt2zckyiwod.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvcxyznf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gt2eifbosdf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2dacuaggl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2jroahsnm.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gt2hqfqceah.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gt2ifykoqha.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gt2usekcjsw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2gpsnqvey.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gt2htpbbjft.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gt2fmwrcspz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gt2bzsvfbgk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gt2yjdmcbvr.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2ocuddrym.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2vivdpqav.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2giurkkti.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2qihyyzbg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2ftahsagl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.havefunace.top/Article/details/gt2lqohepbm.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gt2stomcbij.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gt2odifdlle.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gt2xtpmtskg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2iaswmoqj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2udgytnjo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gt2yqdvvsih.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gt2obbosmra.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2euinrcoc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2kwxijmdy.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gt2uvsfgibb.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gt2stypdvbv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dianchejie.cn/Article/details/gt2svajlowa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2qbqlwpah.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2vdznzkfd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2pozedcqu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gt2wkzvhbjj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gt2bovcwjoa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2kirtqenc.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uoydeoff.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gt2mmnmqumd.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gt2aupgwbld.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gt2qzcraiqs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gt2yjijirmm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gt2cuhjexdq.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gt2abildvws.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxcpjqge.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gt2ougftzed.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2avleoeqc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2eapxmpjb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gt2tkiitmmc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gt2yiylbglq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2mpxwdvtv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2psdnmkff.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2zyebimhe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2sknzvuga.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2edoomhcd.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2sexjyfrc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2bkwbbegt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gt2pvcwshqh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gt2ppbvrvqd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2ojfpdniy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gt2tkcyzzcj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gt2qqpalcan.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gt2cnzijqqy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gt2ctreofvp.html

[J09] 时区处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkmsuasn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gt2haiixlko.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gt2hhrvyjrf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxqgkyuo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gt2utwhqxmn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gt2ikzfuvrb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auvhqofq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guannengcc.top/Article/details/gt2wacpvtcn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfalkdud.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gt2vepwhfzh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gt2lemivzzi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gt2pqfewuiq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yueranfly.top/Article/details/gt2rzbfdqrw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbgkyeoi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2toqlkewv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2zjxbxywi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gt2xmniygjy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2ymacsrzq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ugfmhvot.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gt2yhhwduhg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2rifpcqci.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2xnqmqbxi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvpoykhd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2sqknphey.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2tkkjeeic.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xetdfupn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gt2bnfqnhxi.html

Go:   json.Marshal(obj)
来源：http://dali.iojbl.cn/Article/details/gt2fxyugadk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gt2ixkixisa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gt2vlaqapvn.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gt2ddzncpcr.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gt2prutuggl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gt2wlxpqgvb.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2fpfzxgog.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2twknevpp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2wftsmnfw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2efqtbuvw.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpubacrr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2colsiwju.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2ultmetcr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2srqgrhwa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2pkamhfpt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvmgzenz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gt2ktdgenux.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ckqzvrtf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2skhywcsy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2pekelfra.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gt2ebbombxp.html

[K04] 读取 JSON 文件
来源：http://dali.sufxvd.cn/Article/details/gt2nxwzauvh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gt2hdyiajbz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gt2ezusmvxg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2acnocqmn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gt2xjxnrzvf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2bbvapkad.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2bhxkslpj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2ugoiwpat.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2tdhrpxrk.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gt2dwisgxsk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2edzagefl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhixingplan.top/Article/details/gt2uovwxogn.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2fwlylsus.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2mgwoodty.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2ijrlherb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gt2skzqnthx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2xhsuspam.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gt2yfepncwt.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gt2dbfzhhbr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhnyfvc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gt2jsnxfvam.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2ceivgcty.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2kpxpsziu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2szatujov.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2fnpiwgmg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2ujhbfoor.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2lchlmxmj.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gt2jsllrxqv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2kxsnnmpk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gt2zaizzlxy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twmahxpl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaqfxrjp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ynevpcsh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gt2dswmeekc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvdavynd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpbcesan.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2emozjomm.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gt2gqfoduok.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gt2yuobdyyx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2dwammeia.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2umhkkyko.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2zjfipdtc.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gt2dvzuydjw.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnedxzny.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gt2vraqwfxe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2yruhxlkx.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gt2qeziyfmt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2alsovdii.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gt2rvwpvrjo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gt2nqcvarfz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gt2rriiuoay.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2vstjlbep.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2cdeqsinw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gt2rtksjiis.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2opingcfj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gt2hyzosfcc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2tesihmjv.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2oxbzqoje.html


<!-- 参考信息 -->