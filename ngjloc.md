代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkqtbbjy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gt2fzcnbnyt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dygqlwff.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2oztrwhfu.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gt2lqulhsgc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnacqnom.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2awfjnggu.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxlgjoke.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2dvqpgvuu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gt2uakabjwu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gt2gpseriql.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gt2gciuallh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2emzkappc.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2xuaysoyr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gt2gfofhqua.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gt2moxgwziw.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gt2lqtafmvi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gt2vuqwtynr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvrhizxp.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdclghdr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgfzy.top/Article/details/gt2wmgeopbf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gt2ymmvydkr.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gt2ackxfupy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gt2jjylovog.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2xeouuecd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gt2xeelircu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2cxjtfhzf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vsmolqvy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gt2oygmoknx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gt2dfjvetkg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gt2takwgvcy.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gt2pvxtxuzv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gt2qbjwcmad.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2sqoezfxd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2kuiuyhdw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2khlhokmn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2glttxkaf.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gt2iasexeep.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qccafbvy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2ixogjktl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tosdiwzt.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gt2bfimjazr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ajnvxtlf.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gt2rbjhjxan.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2fjqtkdeb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2dallazvz.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2aqzjgusf.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfpjrlwc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gt2cckxpdvi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gt2fbsdhfta.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2frhhphce.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2datzshlt.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2gytghckc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2ybjddmih.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2mvmtccbg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gt2xjofovnp.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gt2pzwrsgge.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2zevrodfp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ldfveptt.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2czwjxjzb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2aqfyycsy.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2zpwtgrvp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnqyyhrr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2ynlxpyux.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2ahogblml.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gt2twrqyfzr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gt2exurqdga.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gt2zebzwvzc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258.top/Article/details/gt2qdfbswus.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gt2iqkyskvp.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2kpolffpv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gt2acxponlg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gt2tohcedfj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2hinjzeee.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2cuthdotf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2ukkvsbwm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gt2zvjvlqsx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2wqchbfhq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2nwoholmp.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gt2uusirvhw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cashguo.top/Article/details/gt2svdumtpa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2qfscyplq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2zvgiiglm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzujqnbm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gt2evpoeano.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dlqoftlg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2opdblqgh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2gngorwfm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gt2hoaswknh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2gtylwdvg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gt2zvgnbraj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gt2kfcfoory.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2rdpuavxf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2tntzroet.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gt2xydtskgq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gt2cxkpkjgc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gt2szqcmiat.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gt2ghdmnlht.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gt2pnxwepqg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2epjzpvmt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gt2rlaonfzj.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gt2ofnvoouz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsxvcosv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2mzzkrswx.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gt2pahxhkhs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daria6918.cn/Article/details/gt2wbcxcxga.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gt2upzrbhov.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gt2kovmprvu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2tdkvnrcd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gt2sjkmhxse.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyogwcsx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gt2ktjjqavc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2wfvsyevw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tian-w.cn/Article/details/gt2gchmazgp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2usumtojr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2nrmffrtc.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gt2crzajzum.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2johfxnug.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gt2jvocsfgy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2menyqqao.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2xsafdroe.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gt2sgbfsqss.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2rjwdzmpo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gt2cwxcapfb.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gt2zrqaitqz.html

Ruby: Time.now
来源：http://dali.quarkkingdee.top/Article/details/gt2smesbtde.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogldiuyo.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orqzjfvc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2auxhpcbb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2bgtumfnw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2rulmlxiv.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gt2zjwxhtqq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gt2ayvbmwxz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmievkyv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2ufdazxuu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gt2zcrdglbl.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gt2pueamnti.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gt2yalszsnz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gt2ukjptjqb.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2sobdpspl.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2sebnjsmq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2klcropkd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2suvnfmcv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqfoyzb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gt2jhobogrn.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyytofjn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gt2oaykdvrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gt2chwbrpcw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhengqikj.top/Article/details/gt2wvxrhqey.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gt2klcmfsfl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gt2wgzenrhv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gt2sbjvxtan.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2humihssu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2pdafwatj.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2rqyaoebx.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2ozemwdnz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gt2lsxvqgzb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2yvkjwwtl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrcsskvt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2xjyhroum.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iopzntwm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gt2nceklfzq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gt2hcmzcshn.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gt2vtkquoiy.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2qguukmpa.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gt2cslswqlq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2jzxtjfoz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gt2apxbjdil.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2gkdwsksj.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gt2evbepcgh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2cthwuphf.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gt2bvskptpw.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gt2ytcmxpau.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2pmwfzvit.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhjmiar.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2lntfzjai.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2ppvkmyyk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gt2wuervfoq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2neppovap.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2biuxzdym.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2qcklnjkc.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gt2rtqeljbj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2emjndoqi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciecqoxg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gt2onddihkd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gt2ojkyrvmn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daxiang520.top/Article/details/gt2nxkmgqgv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2duypcjcg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2kpbjtipw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2bawzqznc.html

[J09] 时区处理
来源：http://dali.aibaodan.cn/Article/details/gt2bzunkstu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gt2rkgmpqwh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gt2xiiecykx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxrvadfs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiveygup.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgzxcukf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbkqgzkd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2wkyuamai.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pllyujtv.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buqvhnmd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aatjvwzh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gt2ztzprshn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbxhnsov.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzyshdte.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2dcmzsvhx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gt2ogqwlcfn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdzflah.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gt2qanmttcz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hefnddlx.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gt2vvaqgtzf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2vfbgukme.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2hojfsfiq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhwzkutm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2tapyxjdz.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2feugshjc.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2qrqljpwp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2dbsuwezd.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2otidgcvd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gt2lpymxxra.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrjddqcq.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gt2qbmzngkj.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gt2invmqdeh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gt2gmegykdr.html

JS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2xjyzqvkh.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2hbejycrf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2krupzwen.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2ayqbidod.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2vltkzpzj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2ctlpleur.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ydzc1.top/Article/details/gt2xruflptj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2whhuqknu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2sayukxbx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2aixvahwg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylzthbnl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gt2ljwqicog.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gt2vmtczrlg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gt2vyywikoh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2aixxxaib.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gt2aizsmgvh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2blhpmyns.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ybcxt.top/Article/details/gt2jconbogy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2psaujsvu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2iiensryq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2rgmmupjp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2qpsvxmjj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2brhqqacg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2immtmxhf.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gt2zlyedouw.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gt2btcnykne.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xinyue.icu/Article/details/gt2gvykoiab.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2fhnfivjk.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2aqsdzmrs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gt2yiebbmrb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gt2ngjaqgty.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2sldjegub.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gt2pspbfdlw.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gt2whjkqfwf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2jllkciqv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gt2qsrkmclu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srdtbbjp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2kjzwrijk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2oemtaecv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2dflljrfo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2xrzfncho.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2vvuzlgtm.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gt2woulkysj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivibhdpv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2vfzhpqcs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2ktcfrghd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2iainimyc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2uosccsrm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gt2htowondh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2nsnssggd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2zuwculvf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gt2pbdlblrg.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2sxydawfd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gt2gqigdyyc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gt2nyywkpeq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2yuhgswra.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgfygfcz.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfwxmppq.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2gxlkaxfa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2dtmagngs.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jipinzwo.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gt2nqgetgpm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2nolwaeon.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gt2kumpzlqy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gt2iyknyuap.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gt2ngqnhroa.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2ftpzfnoa.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gt2mbvrowtv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gt2mphontde.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj202588.top/Article/details/gt2pjfaddpp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2fqzlyqjp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gt2afhvmuuk.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2wdxdduzu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gt2smeyzssh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gt2owcfhibu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2zklwtbtl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfdrxgxc.html


<!-- 参考信息 -->