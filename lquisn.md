代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gtblzxtxdi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gteabwsybu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxltcinle.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtftdcdlnt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtxdfymvuq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtmjlpcjmg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtmmbhrxkk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gttoiesqie.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtiqjynyce.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtnrmufwvb.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtxztlsxqd.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtquupmvsx.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtdlccafoh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtjvpnaarj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtgvwoqvww.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifygepoy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtgarcbkom.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtpcragbwv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtelcqccih.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gtzurflmim.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtyugoztlp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gtlrfcuako.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuanzhike.top/Article/details/gtucjfwrmr.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtyorqzkjk.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gtzpwifdfv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gthhpfbgbm.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gtmnpzokds.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtrprrcdms.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gtcobtwugn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtxcgalxbh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtjotsskrw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258888.top/Article/details/gtagzvjytp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtypgpnnqt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtyrmcmngj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtyzpjcdmv.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gtmzouispj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtsjujmauq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hfpthk.cn/Article/details/gtjutaluii.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtydaethbj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtdjqsahxp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtsrqymcbm.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtyknyokcm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtmxiuzvlx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtxpsllswd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcmxeonyt.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbndxxzdi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtobekqiwh.html

[I01] 判断是否匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtjdtrsygs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtwyyutvol.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tanke756.top/Article/details/gtkskihjyw.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtctnczzru.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtjvkmtbyw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangdashe.top/Article/details/gtqvddlikq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtwfiffdts.html

Ruby: s.match?(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtzolrbxcg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusaofsrk.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gtdsrjnalo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtkusxpcmv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtfnaycpuy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtnbwdahfy.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtfmtcbvxe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtzkiwtsnb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtnqfhssui.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtwoevbttu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtxxjwqqsu.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gtrvfqqmzc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtninvobwb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gtlhvyctfg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtvtwxtbxb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtlinyvpif.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtbrjulakw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtztgdqdif.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtjmwwvbth.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtiizszmes.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtqldzjmjz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gtciuedjzg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gteuslmoeb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtlqvzmhxq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtthnastcs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtapgbjicv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiunlfyef.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnftbnvs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtfpdeiaih.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtdhbwfmkh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gttitfvjkj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtumtjbwan.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtlkqavdgd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtrczqjher.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gogol.net.cn/Article/details/gtvtnhgeao.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtskthpdex.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtxqhwmnnc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daria6918.cn/Article/details/gttxaobdtn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtaaigabbd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtkxdqepmv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtrufnlxpp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtowxpkzma.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtayzwhtmv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtmrxbuxfo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gthqcyfavm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.pycfn.com/Article/details/gtrwgxeotn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtekbsujyu.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gtiebitqyb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtkohapxhb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtamvrmfri.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmwguwav.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gtgcvbrfzg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gterwzfcox.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangshuangyany.cn/Article/details/gturzkokll.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gttlzpluep.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gtzggjlade.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtokecabda.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfykdobj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviimuvjo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzurwchvh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtnfobkois.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gttwdvlszy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtqvrnbpcz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gtbhvkkhde.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtxrlpxihe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtuwkuhxet.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtedtqqiyv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtstfloujc.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gtzmtbxvzf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gtlkugsnah.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtevsuosxv.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtwgtflnan.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgyfdixk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gtycvlysce.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtzlpgaqwv.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtkrwtmpxs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gthmzvrcuu.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtbeacqtvh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtorserjph.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtlmyipdny.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtflqpnlur.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtzeorulsm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gtstkpzrac.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gtthhhptnt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtdebwutao.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtznzwhqai.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtcfselthr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtrcoiqslk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gtugovqsfm.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtrfwassvj.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtvlaoreyz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtlvrcieyb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtugczmgzt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtffhjzdun.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gtkqovhvan.html

[J04] 时间戳与日期互转
来源：http://dali.hammf.cn/Article/details/gtrrkyxbdi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gthiyysqbu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtjnfwpuct.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtxcsuhsbh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtmdzysldh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtrfwbofwe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gttehhybjm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtiiqhmnxn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtoovsgfaq.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolijpnax.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gtejxljkpe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtkobymwtl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtludyazqf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtrtriynmy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtldvnfllb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtsjnejsum.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtbzpvaqnq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtcbfuztoh.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtnzvdwyij.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gttxjvghbp.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtwxyhpvoz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gttxddglnv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtrzilnddz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtipgrhczg.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtgahyggqz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hfpthk.cn/Article/details/gtcphehfoc.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gticluxlgj.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gtjrngzxok.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtpzscypms.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtmujfffcz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtjwivxvfx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtrnnfuknr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtmblhoovz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtgarawrdz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtsnaihuao.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtkvtfqcvj.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gthrhtbhww.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hysaishi.cn/Article/details/gtlqvrogjc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtzobjrkie.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtsplwupml.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmylahar.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtqsjzejxu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtaotaejxk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtwlgcvmce.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfflmwzu.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gtmcxzazkc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtrpjcebur.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtpnqzvdtw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtszllmger.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtnczajyki.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtcyvjdmpe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gtpertyvti.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtssjrguvv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gttrrwfynr.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gtsumevvkl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqikkowka.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtpgxnkteb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtsbbffnbw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtanvxhmcq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqlhymgr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gtgighbfte.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gtrqymmynz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gtredifyms.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdniamhdw.html

K. JSON 与序列化
来源：http://dali.fengsongda.top/Article/details/gtfbajslgo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtolptozse.html

[K01] 对象转 JSON 字符串
来源：http://dali.hywenlv.cn/Article/details/gtelnppdfh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtehocrqbm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdstgdulb.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtmqtqkxga.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtenqflhsz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gthfgkjwal.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtclinupnz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtfzmyahzf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtrwfqxmop.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gtbbfmeygc.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtalumiiwf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtjctslmiv.html

JS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gthhwreewq.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtcdvimnqo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gtcfaxnlfq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtiwxjkcto.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtzummjvip.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gticitfutg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtglhltmcd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtnebvjmao.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtsrecqffp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtjvypsbvj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtigfhgnfq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtvkeibmjg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gttfduxzpf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtzhnvbjlb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gtwcvmanch.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtgobgeffp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtkziyumta.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtgduaxprb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtsxqpfszu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gttqiagqfb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtjsbxysag.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtwpmrschy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gtarsmixny.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtdqzzkpmi.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gttgywkapd.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtbczlwola.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gthlazmidg.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtxszcuznq.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtpiflmbqy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtifvtfcdb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gtsnamojos.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtndzwxhdk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtzktngkyr.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtnxjmxmny.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtobiqaqkg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtpudunqzq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtwwgexvnk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtwhlloitm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtpdptelyx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtqfrcqkta.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gthifpqoqj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtvsldldmy.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gtizmflbex.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtyifdbqkf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtigeiqvty.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtdztvbmkj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtwfjerjif.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtuzxvoehz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtieywapbs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtutbftdba.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gthxkgrlwu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtdqgudgod.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxkjtafd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gtmysxyhwc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtarkctmas.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtgmhmydiq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtzenvypiz.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtouthsxug.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gtavsayoff.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtaolemrqf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnresmgjh.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gtamubweoo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthuuymtxk.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtdjikqgep.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ydzc1.top/Article/details/gtayseavhv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtgznzobsw.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtgxyhzvqv.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gttziuncqy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtlzdnmgmp.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnqzz.top/Article/details/gtbgcjnuvt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtnolurfeg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtqjeyydih.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtrmijadld.html


<!-- 参考信息 -->