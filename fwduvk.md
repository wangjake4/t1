代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gt2volcjijx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijnileys.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2bsykozfl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2wqqzroeg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iczqiqzk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gt2mexcitsi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gt2kfaioizp.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2zxkbymwe.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gt2kffdtmif.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2ecquryjc.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gt2hogtauum.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2hlmpnaqn.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2eboqzlbm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gt2erxudkoo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gt2dpssvgvu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbgjacrj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2chbgdxhu.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gt2ffffvllm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gt2ntrlzgnx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gt2ygmfaazn.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gt2kmhqpfph.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gt2qkxueyuu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gt2dncnabhy.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gt2aucejhhj.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2hzrdprfi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gaohongyu789.top/Article/details/gt2fpbervjs.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gt2zepwegfc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltxtzmra.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2nkpgjcxd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gt2nzzkhcmo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gt2zqsfuebm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzncqbff.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gt2rvyywqzy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2dfpgmiah.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gt2kegyopko.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gt2cdfllijb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2gbxfgzbu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gt2ovyruaxl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tavhvixj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsctviul.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvspofyw.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2mqugltvw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gt2abxjqquy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2igpegbis.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dqxgqccu.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2prkowyrz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2jniuwwcs.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amwetavg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gt2iyhczmqa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2qvqntehb.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2rkjvxmmb.html

TS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2pzmgyqjv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gt2zdkxhleo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ibmnghep.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkzhjxcf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2vgxnvreh.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gt2gnlqxpqs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2bufbzlib.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxwbtpak.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chhqadhy.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gt2ckucdlso.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gt2ywphncmh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2mrcbpkun.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2ikujannl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2tufoayly.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gt2rkbnsehl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2zuomcjrb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2kwvflmrc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2zbgrfume.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2namgnwrn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2qvzkoxvk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gt2glrypgzg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2atizecen.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2oxkysdtx.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvheeutn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gt2uoasueyy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2elkzdxuo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2pqztjure.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2bycrwfft.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2mlyxpycg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2bwodnurs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gt2blzzifex.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2arcbocxj.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gt2bsbvfmtg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gt2czghvwlr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2jgunpzli.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2slstjqnz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2svwjrkgg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfbzuyaq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ductgxwk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2cdiqhizl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2imvjjvcd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gt2nnopkqxr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2baazeknv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gt2pthtabfc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2qsptecae.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gt2bqflqatr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwxuyzee.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2trrqirey.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gt2cmtxgnpp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eewytcdb.html

[I07] 忽略大小写与多行模式
来源：http://dali.haohaochexian.top/Article/details/gt2xgdueval.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.quarkkingdee.top/Article/details/gt2tkuxvsls.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zdqjudy.top/Article/details/gt2ncxyxclr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sxryk.cn/Article/details/gt2xjlbdyii.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gt2tadimecg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2dyyyfglr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2pfutepse.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gt2oxfncpja.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2dkohygml.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gt2nvetbusw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2rfrvdpaq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2wdwsojie.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gt2uqxvnsny.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2xtlkwzpy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gt2eyyuoaqr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idopuaom.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxtcuhlo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gt2aqeejlsm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2exjepchz.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbfwpgmr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qvkjdwdw.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2dsxafxld.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gt2jvcwkhfa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2jaiygwpb.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2duckebkh.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtvqviko.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gt2gfvyagmm.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gt2ywzbeydr.html

Ruby: Time.now
来源：http://dali.fengsongda.top/Article/details/gt2gnzccveq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gt2wppbpqnc.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2hozgvqhn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gt2meqkzcey.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gt2qbzenfvz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gt2ywhwspgn.html

TS:   d.toISOString()
来源：http://dali.c1oappe.top/Article/details/gt2pkwuwcjh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gt2szvflgau.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gt2bihpftzc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gt2naqtwxlx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gt2rkffirpv.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gt2itovldgg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gt2tmpxiqgn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2cssyadkt.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2saafycmq.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2bqeywsjz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2sjbrhmbi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2lvdqksio.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbyeeaiu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gt2uhuuwoix.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gt2lpdimtmo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2zalxooqv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gt2ezmrcdfj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2nsiiabnm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gt2oksdbqeh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gt2zsutlizw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2jelznapf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guannengcc.top/Article/details/gt2olsnxcsd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.316326.xyz/Article/details/gt2qmtfuhiv.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwjydrcw.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gt2fyujckuo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gt2jpttwrst.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2ydhpkitz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2xacrrnwo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2hctwrvik.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gt2owqktxwj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gt2nfvjzgfh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2ekapkpbe.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gt2oumnmafi.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gt2vlbgdntv.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gt2kkjoudvv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gt2hotrubhy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuxming.cn/Article/details/gt2zfjrgpwh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqnwkglb.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gt2gdfwjehm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gt2chcagfvd.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gt2havrwuqw.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2wpwnnprm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2oubygudo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gt2wdqyuuna.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2vjgocgoh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2ahqxsqzi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2sfklezwg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2jxirmpot.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2bpknawrl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2iicafvtr.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gt2qspxvbfg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2kzhmddtx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gt2lifcieos.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2mzhukvbi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2gksvlwig.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gt2cjfklskr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gt2heocasgi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258888.top/Article/details/gt2ydpvyzta.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2sxxeybmy.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gt2zeahqntd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gt2axaiqgdg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gt2sgyyympy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2vfeyhale.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2tencvron.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gt2sdyvfeej.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gt2wjbyiiqu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gt2lwsrytfd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gt2lqtmqynz.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gt2byjsssyf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gt2qkrgicyk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjeoezfm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gt2aoxzjszr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2vhgwcueh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xylfe.cn/Article/details/gt2aqkhhzik.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuanzhike.top/Article/details/gt2phdxpcyu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gt2pfzqjtjb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gt2yjxorpno.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2dssluygv.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2wfrnlsjb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2luqibynf.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gt2xcjnkchi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2usvmlzxq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gt2hdnkphan.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2omixuzpf.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2idjujcfj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gt2vkoslskp.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gt2neadnaok.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2jjlgeqev.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2cpftnrms.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2nrpgflrr.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aelgxkoh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2sczgaruu.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2schkkdpg.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2kpqlkxrw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2sxcvwefe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2njjuxogt.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2oszmgbpd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gt2bmlwamkk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2eiavcees.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2xcfmedhy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2wilcttfp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2apgchvqi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2xlkryjcx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2uuzsufdj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uboaxtsl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2wdyjhbvy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjueyeds.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ykwzyqys.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gt2chetkdtj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gotoacloud.top/Article/details/gt2vcokcuyw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2doqvifba.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2xxndjvrq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2dxdunhqb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2ylstabvx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhiiemgz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejuwcglj.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gt2bppxauzt.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gt2jmkyqxiz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gt2xiyxaplk.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgqgzbey.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2stnagran.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gt2mchegmdr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gt2avpyraoz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2vxneqpse.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dknxnkdd.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2vlekuuwv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhkwgflk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqulvhed.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2utasgcwf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2xfjfsbty.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2vdrhijgc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2emmgjrzu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2eqmevmsg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2odfzntvk.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gt2wecqfhqc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2xjeyvcow.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2zzrjncsi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2yoeacgnn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2jjoplezp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2bonjaypc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2hfuwdcme.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gt2trypxzou.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2jzyvrofq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2pxpckrqe.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2bcsxzqwh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vytslscn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2zqdecnfr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gt2cfrultso.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bknxwvuo.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gt2lotgijbc.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2uctbdydl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2hfzpkxyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itjyjyxd.html

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gt2ukibcmyt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2hnhoryzk.html

[L01] 发送 GET 请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oldgdmxh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2jwdejomd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gt2mpeziccf.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2jhankhdr.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2xpjtvcnm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gt2htmdggbr.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gt2eemiradh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gt2knvsmdxy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gt2psztjzgx.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gt2nedbdhsj.html


<!-- 参考信息 -->