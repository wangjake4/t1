代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gttnhsvgkz.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtihvqleyj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtddjsjyfp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtxvoiiopf.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtmmpuibim.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtdqcrjrwg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtcoqnxhqs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtqiaasxjq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gotoacloud.top/Article/details/gtfpvuecgi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtytibiojz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtjfnfxpvg.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gttkmmkijg.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtabpmfbsn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtogfvtfbw.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtllibjlnf.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtzkzgyouc.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtskxsoehh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gtqgjayqbs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtsurabdoy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtchbkiixe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteepsboma.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgcdxhri.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtjkdclpxa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtgvrygira.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtlmowdlmx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtqlpfehtn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtvjteekrt.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtnsfzganl.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtpqzssbpj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwzrxiiy.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtddrhkvos.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbmscdjh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtpacorjqq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtgezyjglv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ydzc1.top/Article/details/gtaamhbxiw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtronxqcpe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gthrrievte.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gtauzixhqg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gtyjqwiohi.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtholibbjb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtxogiklzx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gtyzevwqce.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtoirddvdm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtumtcvfht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gtmuufrdal.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gtmyrdcvwd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtqojeablx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtmixzlaic.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtblzpwrwr.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtutneharg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjzldkpbw.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gtsyfcosty.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtnknpjphl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gttaqctctx.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtxdweeemo.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdxqgddm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gtaesnjism.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtqyxjrvpk.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtygbpfvux.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtzdbsarzw.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtwrimmvwb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtaqhdjurn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtxujgnaxy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtzwsmyczx.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gtqonqnjxk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtjcayagop.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gtslkqlyjs.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtmwrtyuru.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtacscpbsd.html

[I03] 提取捕获分组
来源：http://dali.andypj.xyz/Article/details/gtpoawgjfc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtaleisrak.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqnvndzj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gtmuvbfjpi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtwqunumva.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtsacertcf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gtwvjocfnf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sweek.top/Article/details/gtdrnkyrek.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtbiqrjbdp.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gtuetvpium.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gttaazzzwf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtttouposz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtttpyluew.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtndlxvxza.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtpcxjwwdg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gtynodzudf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdxdhums.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtdekvsrcp.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdldfosnf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtzesscegg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtynomxzeq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gthjsshvdw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtenacuekq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.mhx1999.top/Article/details/gtwmdhzpsk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtlnnnpehf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtdiyhhljb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtsvnlucvk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtqdkgrwxk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtrsjecmwp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gtmuyyvkjx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtnubarkdt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gtmxlvluwv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuzqdfqv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gtsymgfvlw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtseibmpwg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtpeizmbmc.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gtpquoogsx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtqswvgnge.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtxyahxyvx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtladzzavy.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtbscsjzuc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtnvrbbemm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtgipsmexa.html

Ruby: s.scan(/error/i)
来源：http://dali.dashuyun.cn/Article/details/gtcwrijfjm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gthuzolljn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gtbxxxbpoy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xinyue.icu/Article/details/gtzqlvbhxw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtqpbexqgp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtnuljjvex.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtphjmyzqi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtwkjxxjhn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtmfujbnkf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtsfpmwvkw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gteulfkfub.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttgirgxnl.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtvmmzpthr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttflrtime.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtamsqbluv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gtqjzkmuad.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtxphkqakx.html

JS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtrswxghbt.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtsqdpjxqr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtnrsdddez.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtgimilxxw.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtvtmhlcga.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gtmxizccec.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolknwajv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtbzoggpxb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtijjovvat.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjurftgk.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtjogrmtoe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gtawrbwful.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gtfdjkxpmq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtybddfrqn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytzcnrej.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtkhmkmwyf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtemlkcuqv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gtbqknzfru.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtrgdhiitq.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gttpihdpvy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtzohvqaor.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gthnpprpkf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtrzwjgrks.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtwvhhnvhc.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtvakeasxo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtmnonibjm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sufxvd.cn/Article/details/gtdspnwdhl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtoajendty.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtxwscjocy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtnlsrymaj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gtaownqfax.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gttooypurz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtmpmjgqse.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtotecrdwq.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gticlazhto.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtfqsbvddx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtoqyjkfuk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfkszlyz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtsvtsqwnn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtvntzvwrg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtivpihmmz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtlkkpjjyb.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gtqcfwqjof.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gteautrqib.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtbfevevso.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtzldvqrrn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtpmnlmbwo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbuyqqeo.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtwgjmylrn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtfuedcfwi.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtrsckkpvs.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtfbeajsen.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtgpcihtto.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtuanjaift.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtrhcgvnzk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtzwmxduny.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtylessaxj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtuwhwivvc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtwzvtgbys.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtwgfifnec.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdxghrxc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gthdunsxab.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtjybseplc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtxlewiulv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gthvxngpye.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gtvfryyrva.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtuyvpcnft.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilhxtscb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtrlainbnu.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtgwsmjrpy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gtkrcbdkru.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuanzhike.top/Article/details/gtooknjhsn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtjgxyyzij.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtlzdwvpod.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtcvnivkdn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtzgjlyfou.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gtchsafdxg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtjmsumqmc.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtykybfazb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtpkzrejvk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtvupmqzgq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gttcznfwas.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtmddlhswa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gtrviaaeon.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtmcvjenjs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtxpigapuf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gtptripzhv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttrtcfsbr.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtebemtzhd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtiadmswaa.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gtoqgexqof.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqzzqnxr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtptmqdiem.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtxnhnhhsj.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtmadxvmff.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gtyfiupdkf.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gtuufseqik.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gtxtlxbdgd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gtuqpbnyzr.html

[K02] JSON 字符串转对象
来源：http://dali.yueranfly.top/Article/details/gtwkyixpup.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtzjdidwvg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpqellzt.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtwshwsluj.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gttxgigwwp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtpszocovb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtdhsvmorx.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtmrppuaxy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtqqojpwmc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtjdyquscz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtplcfaoip.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gtejgibrom.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtleyogsyn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtedsrhxwf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtiroiegam.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtsqxnppnw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtyklmcitz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gtbuectsts.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtmqnhmfiv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gtykrrzhah.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtwcppuyay.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.meibo888.top/Article/details/gtcjlvqolw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtvlrzcoau.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtfvgnunby.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtlgysdexb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gtnntechup.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtceouarrg.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtcnzpamel.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gtvewbvppb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gttamhljzq.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtwlltuerh.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtbzibivds.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtwdygunib.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtwifabver.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtkcsqykdz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtsnqidsxf.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gthefnyfqt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtgfwcxmmo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtrggritsf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtwxrogskb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtjinraqxb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gtuwjydtwy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagqwvfwt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtyvtokvyp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtfxlwtzco.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gthkyhelob.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtmqkkfpbi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtbmwbgybn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdovrzdly.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtgyflnppm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtnvninnda.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gthfptocde.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtysbluyxb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gticmqrivq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtnlfkbiji.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gthuwsbttn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtbuobdwcx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtbeqyaesa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtjvkfztqn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gtqezvmgmx.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtcwzefcxv.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrlpbazw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtpftdchgy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthgckbrue.html

L. 网络请求
来源：http://dali.zhongyouzk.top/Article/details/gtdqyuoymp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtayzgycox.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gtlyhqzgzr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtdohfefim.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjeeoncl.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gttqbtmyvq.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gttfqgwddt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gtlglgzirb.html


<!-- 参考信息 -->