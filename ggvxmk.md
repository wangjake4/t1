代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gt2yqttlqsv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gt2equiarqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2caoitznu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2yqqxiezp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gt2omhqfhiv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gt2wbxbuwpk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gt2tewpylbu.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2pdzswuiu.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gt2zuzmspuq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdiiapxz.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gt2zglulmwx.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2zkuribjp.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2mhxflpnl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gt2ldprhgyz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdlvhimh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihiqxqmw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2elqnesgi.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gt2wwdmchhg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gt2bwlrkvnj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gt2abuthbli.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gt2hipnwryx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gt2xudzxvhs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gt2scgxtrrw.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2vpcuynve.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gt2ahrsuqpb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gt2pvlzkqun.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2bkevicgb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2qlivkexx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2kamllnlj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2ifhzvyge.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gt2zzyalypy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhnztizh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2rrsqyyzs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hivkzkce.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gt2ewjjssed.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gt2qmvjaeqq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gt2zbkwecge.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gt2cgzearyb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxbdwvis.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2uobenxev.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2ittjrtsv.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gt2qawplnov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenlongwang.top/Article/details/gt2slxnzrxa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2krvrdynq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2gwiaqauq.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amtsafyf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vtylmbrc.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxsaauug.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzqsyuxy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2qgtvpfzo.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2uycjvfpj.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2gypqmoef.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2bleqmbou.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gt2anaaqoqb.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gt2mpxhozkk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2oioajypt.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gt2otyquisv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2wnoahbah.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2iwvxmiup.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.9152youxi.cn/Article/details/gt2gluuhdeb.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qffsjpzj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gt2aiodnuvq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2bhvhdvni.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2yprtjjms.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2pllvpbkq.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gt2qmfthclc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gt2szdxnkct.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2nhuxknpr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwkfbdot.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmbzcnoi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppvyjyug.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gt2ambymxme.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gt2wmuenhas.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gt2hlypjdfd.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gt2tvmqcosx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gt2qfccyxqu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2valsbnqk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gt2nxvbdubg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gt2xgijuvph.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2dverytcs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gt2deljrrnc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gt2pfzxuqar.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sysykeji.top/Article/details/gt2warieviq.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gt2rfyttfit.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gt2hoynmvbo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2wovknjxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2aqudosyu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2kqkhgewd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auktxrsm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2xaqajiog.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2btmucvss.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyxjxaqu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gt2vhalbpht.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2mohqwttj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2jqjmpfua.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2mjlstrmz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2dyyqemjw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2sqjppjpg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2bhzowtpl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gt2ppkpkegl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2yndmkydg.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gt2noskafan.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gt2xrbxuecf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2lgduumhw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2btwxcnra.html

TS:   /error/gim
来源：http://dali.nanxinkj.top/Article/details/gt2xbyzhpfs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2besrzaat.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gt2pggxoxgh.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gt2zfysddsl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gt2qkxmuhxs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gt2cqwhtrip.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gt2iujgwfur.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gt2qhurkrhd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2xylfooqw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gt2bxxmbtzj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2iwutqfsi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2ihxrqyfl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gt2iuyonxii.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2xnhivwft.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ewfzgguv.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2lvgbujda.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2blypames.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gt2dozvurbn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfsqdalj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2faeubtxo.html

JS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2wexogikl.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gt2npynsycy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gt2vnhmgjho.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gt2zrjysfzd.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2vplsnyrl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvqwftpl.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppejrqgc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2goixjlha.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2yjvirguo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gt2vmqlcnmo.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gt2neggzguo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2wblbmven.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gt2efcnhgyz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2bumdbqcv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gt2hcuokdql.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnpebhxg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gt2avphrmfg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2jtikgzvx.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2wmdewtek.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2rusjizdr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2pohfjnpv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2upelqiqy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2skkvpqhd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gt2bgkhoizk.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gt2rhrkrtez.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gt2ldoabqhp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsfredsv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gt2wrkjpsle.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2fieaejgi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gt2hxekhxzo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2wtameozz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gt2qimmavgf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2bjexxscv.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gt2pegatqyl.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2hvsnrfml.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2aydgfztw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2cffgnnzt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2pqhwuwva.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2bkjseeei.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2ajkyyjkk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxqdlpin.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2ipnvtefi.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gt2uohjfohr.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gt2vuxnizqn.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gt2mdirrwpd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gt2ekwttegb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2uzhxilwh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gt2uwghmdeu.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2lkmxinld.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drvfcaiy.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbaemjbk.html

[J07] 比较两个日期
来源：http://dali.cashguo.top/Article/details/gt2mftbbnjx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2yveeacen.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2qwplqlhc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2nfuonczm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2rtkwuluk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gt2wgwztcwf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2gundbhhr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2dhteyrgm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2xjphavmu.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2nnepubcz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gt2udrlimcs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.svipenyu.cn/Article/details/gt2yxisgaea.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gt2ipwohoou.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbtmqphu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gt2rlgnjmxj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gt2poenvovh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gt2duvbmooo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gt2vgxhmaep.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmwkutpt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpgsuzoj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gt2leadjtgx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2asdmzkus.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2hrryspeb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gt2osoaadmq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gt2qgqihlwx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gt2ynldgjhn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gt2vgddlzzp.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gt2fsozrowt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2naptumrx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgkwdliq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2muefcisf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2lhrdpvby.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gt2ztfyaeiv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.9152youxi.cn/Article/details/gt2usgeulnq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2pofxwnyj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnxjwoq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehmsvflm.html

K. JSON 与序列化
来源：http://dali.bjfxy.top/Article/details/gt2cqybpfck.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxachpym.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gt2xdpohnyr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gt2zlldqsug.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2qbbgbftc.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gt2axrmfarr.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2ukkbopho.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gt2jkxauxrk.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gt2ikirxaqe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gt2rvgyunfb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcelqagr.html

[K02] JSON 字符串转对象
来源：http://dali.ivvv.top/Article/details/gt2zmvzhitk.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gt2psxrtjew.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gt2saxohveu.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaflbnps.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2gjdjbfme.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gt2tjhmzvgu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2wieoqzsk.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2ewkvleri.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gt2ytxwwnob.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gt2tkemtoie.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2sqgmdrba.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2ndmanpzz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2pvostjug.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2fmotdpwv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gt2nplldyuu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ownjoyyw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2chulusbj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tianlin.xyz/Article/details/gt2apedfooi.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2suabjnvv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2bethmnrf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfaawewn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2retdzlzr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2jfjrxavz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2immxqzyo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2nlxcilso.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gt2mxmslppk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2phknqcef.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gt2eoucvgjz.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2ezwtmnxh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2sfguzwre.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2aeehufpc.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2bsxfzxca.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gt2ommnsizi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2ffagydwp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gt2asilirkm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gt2ohbbuqdw.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2jbvakzby.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gt2qrkaaqtb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gt2whspjqja.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obsmpunl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2kgocyhwk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gt2lhkkoult.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2lxjmmktz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2jocjeubb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2bhnlpwow.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gloarobj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2finnlhhu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrqopujc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2ikbwvkia.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2clzbrziy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2xfspygcs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2rzjmdbdt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sufxvd.cn/Article/details/gt2bmutceym.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2kbpqiaic.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gt2gtasssiz.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ocvmiljn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gt2ddeonoig.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2pouueaqe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gt2lokkwvxd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjkfsqew.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gt2rvryorbb.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ueovlcys.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2styeutaa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2tpkspaxi.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gt2kkcksjee.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uklrqbwp.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gt2ubtdmbgk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gt2xxktzlvr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gt2mqmytond.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2wezxyisk.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2lathghkm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.vqdsnc.cn/Article/details/gt2qcjpocpx.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gt2upushjdq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gt2kcnmtzso.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djrrrllo.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kttdwyta.html


<!-- 参考信息 -->