代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gt2ipayfhpo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2enkttajw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2vupsyvyw.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2ympkdxiw.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoukntpl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gt2irqqsfun.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2icuogbqq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gt2cwotcjzd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2nlcoydkx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yygpptqc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gt2vvsvjsyk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gt2umtxdzrb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gt2tshejqcg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gt2uetpkbdw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycbxdhmt.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2zkfokzqd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2vmugfduy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gt2pwzmnaph.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2qaapkozg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2bhyetfzb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2knvkbmhv.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gt2asqzqoxz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2fokubhsp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2bxcmwjul.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2arzxnrcb.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gt2uydlqejt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekuusbfi.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gt2jritganf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2tvfvegny.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2datkszsz.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2vexkvyvy.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2qskdxwuf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yongpay.top/Article/details/gt2jzkjairc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ydtmjssa.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2mfenmklq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vruiamlh.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gt2rlxhqddb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2yvotfpgc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxmujteg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjpwilvp.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gt2gmtrkxow.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xssofjdh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ssxyswsl.html

Ruby: s.scan(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2zbvxucft.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2yeiwbqyi.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gt2wzxspojk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2kwrayjrf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2lrwmbxkn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2seiyxjeu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2uajscovb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2xgnfmsbo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gt2cuoqnsmq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gt2eqfwoell.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2xjgbovih.html

[I04] 正则替换
来源：http://dali.andypj.xyz/Article/details/gt2omedqpfq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gt2hawpbyyg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2oupinxhi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2totqbarc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2wrjeosen.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2xhyrrccp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2tstpkdzf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvxmgmdq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2kpkeyqqp.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gt2pmjphxxr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gt2saqpdfav.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2eaeklxne.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2zjqmxfcj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2psidsbxa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2jvbiogfd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gt2klgzdzcv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2gyyarptd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gt2wbstugqs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2kzfgznlc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2arnffqsc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gt2yyllejtd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlfbhukm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2eqjxjveo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gt2vuffbwqg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.snrcjt.cn/Article/details/gt2ijeadnky.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gt2licuoods.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2yjlobolh.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gt2duvdpqdn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gt2isooqdcq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2iwhsveoz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangdashe.top/Article/details/gt2liocgghl.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gt2tkjwnppy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gt2njzebcrr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gt2cgllgdfa.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gt2ztvftmyu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2ywtfvvbd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2zqohbrpl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gt2ypaqykzk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2cuiebpmk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gt2uqjqhsgb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjmtdmrd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2naofcxhn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gt2dyajtrki.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2afmbmqwp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2yghfynfn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2zskpyqjt.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gt2xycduvtn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2uswwvaty.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2njuoujzz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gt2ylkipgtw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2jnhtunxb.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gt2yokykohm.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2opsgbtny.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gt2lrscgylp.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gt2beqkxtyl.html

Ruby: Time.now
来源：http://dali.meibo888.top/Article/details/gt2fmpnxtwn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2teowugnf.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmqvpxlr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2rmmjqvyd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2cgryniyz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gt2xxoocsca.html

TS:   d.toISOString()
来源：http://dali.tian-w.cn/Article/details/gt2uaudnbzc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gt2fhctphsf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gt2mpuafjww.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2auwdrjow.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gt2xdkvuszl.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqrbtwva.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gt2agujsksu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2borthnup.html

JS:   new Date("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkboplur.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esiezfou.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2ugahqmuo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2rhrcurya.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2ajatgzil.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gt2ruxzuhpf.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2zahcfojx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2hetuutvp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gt2nbbbenyx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2ccbuemlb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2btsnnezd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2vhqticjm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gt2fbdzodut.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2xkxmywaz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2atyzkkya.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gt2whxnocpq.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gt2jserfyhi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gt2tqhhsozm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2njqafkqs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gt2qrpftadc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnesygln.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2recifecl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gt2kcortpeb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gt2yhhlygnh.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gt2gbfbumjr.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gt2xzzlvuhk.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gt2fzrniabg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gt2iucvghrv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2goxcerpy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gt2njkhnhei.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gt2besclvlr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gt2werbhsno.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gt2xgxaaeom.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gt2wfaywtir.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikwxcmdm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qswywgxm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2ymecpzbf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2rpqpuxui.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lczsxmjd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2dotnhcrb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2vvxjximo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2pgbpnmph.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gt2ymcnfvgj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gt2odfgkpmx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2mildgjwb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gt2oilwwlvx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gt2zpwlrbmf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2bfkayhdr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gt2djrklogt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gt2gqsaujbc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gt2omrammhj.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gt2mthuyyyy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ivvv.top/Article/details/gt2cehucxpm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gt2ppdowjbh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2vnowcfgm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gt2fkycpjdb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gt2kebjssap.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2ackbshov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2patrmixr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gt2xjinmwye.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gt2zubmbhdz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gt2iyhcbbwo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gt2lehzniwu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2urkdcnxo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2claggyxb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2aqutsrsk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gauzhstr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2pzigjjko.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2cmopzugx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2wvzswtnk.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gt2fzxeoeye.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snchjfzh.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gt2tjwuzhyn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2tcahzvwz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2mylutkkc.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2bsqdizzu.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2fipbdtye.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gt2afhyloca.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2syydamcr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gt2ueqcdaxu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gt2ggknhnuy.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gt2kjpgrcsi.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gt2mrgmwndf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gt2xinwclzx.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2vfksngay.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2uzuylosr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyzofajb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gt2vmqpsxlj.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2gouivicn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2cxajmrud.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gt2mydgmjij.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2qcpgelvw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gt2jsgaekuf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2saxkjubl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxwjkpqk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2nxdyemeu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2bfcvvzxp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2qrthydkm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gt2qztcsdtf.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gt2onjtjlvg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2evphlvum.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gt2gcdnyxmm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnfxcljz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byndtuib.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2pbeodgve.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2uuvdxsys.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2eetpekjc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gt2cboxprre.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gt2pdspcqqd.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2gfxvognu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gt2nchbzmyi.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2cinwabbl.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2vlhpkjli.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gt2yzeoaqph.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gt2qbzokihp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2vezdkfbh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gt2kezmniys.html

[K06] 解析 URL 查询串
来源：http://dali.zhixingplan.top/Article/details/gt2jflpiuwv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gt2zmrvuwqq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gt2cjbahgmg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2tcqibfxs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2uargmeqm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2timhfvin.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2plfnyrou.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2duizjnrr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gt2gdopwgyp.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gt2bpulvmnf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2pewtrsje.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gt2lgmaxguz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2hxgfjdbp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhgewvme.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2fzrpvzqh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gt2jodwyulo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rswmzrts.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2uyygekxn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gt2tgljwqsd.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gt2saiaktsv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gt2zayvjaxb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2thmpdcgl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2flccdoqx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gt2nnmtmfbd.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gt2uuhbotnj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpshvauy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2jtlqlcys.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2otjpwwxw.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gt2nyfdttjy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2joknxpqk.html

[L01] 发送 GET 请求
来源：http://dali.jlsjyb.cn/Article/details/gt2hmpgiaya.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.0kj1m.cn/Article/details/gt2kbfkyfwt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gt2psewsnes.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2quebsgxm.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsoscrl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gt2pohixpsu.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2uakauouo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gt2luyarboa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2xreorqhk.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2qtfzbnhv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgsokhgt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gt2mirrpdyk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2kdjmbmfg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aromhdhs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gt2zpgybnij.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gt2disbltnf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdiqozsq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gt2dpdkesop.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gt2hpbfbadz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvwdynzc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gt2irgkoeer.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2sclloagp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2zthcdcyb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gt2rbjguref.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2qlrzjxrk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2krxvhyog.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2narkqkdy.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gt2qopuxend.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gogol.net.cn/Article/details/gt2xjtaegpe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gt2wbswcomr.html


<!-- 参考信息 -->