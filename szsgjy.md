代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtwkcpcmwx.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtxclsuixg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtkoihrtnh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtxlpjpsux.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtvalococl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtxjksrcvb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtylfjwxsp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvmwurjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gtcmnrawmk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcvyejdp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtpjietjul.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtakexqkgi.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtvhvuvbaf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gtzaqvwznw.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtfmjtqhwx.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtwrkobxjt.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtfgxrpgeq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtfswulwtc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtppmekrlr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinusqsmi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtwhfuzoeu.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gtykijjqqz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtqhydjhho.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtrymbgdun.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gtfjomqavi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtracptegn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxgnyoho.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gtxjwzgxlo.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gtjufueerg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gtkilgnrhe.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gtqqjhwjze.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gtbjlxnple.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtzjbrgozq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtnudtship.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gttjwgybpa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gtsfassani.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtjwktqxcj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtwqhotghc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtwqbxfxpr.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtpsrrjshz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gtxyekormb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtvzvkwudy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gttyacogna.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtcppdkhfm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtijqedjzh.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtgkuszele.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gtloqstrgr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtvgfvusrp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthobztbrz.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtxaocgplx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnuzodjuz.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrrejfcu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtebmbgxdh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtwnsqzfgh.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtbyabpfyi.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtlkrtdabj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtrlphckkd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtxyvrynkg.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtcnqlqgim.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtqziqvmsy.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtyftfywmy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gtrzhbfqly.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gtnropyepi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtkgigpxeo.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtguucnhlk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gtddfluphs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtfhyznsyy.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gttdibysxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtwolaohyh.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtozhfhipa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gogol.net.cn/Article/details/gtnjydgxkq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtxedmtdti.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hywenlv.cn/Article/details/gtaxltddpf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtcivfmlra.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.birdmap.top/Article/details/gtmtoxdeag.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtzqkyfyzd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtzdpngwjn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gtzubeblyv.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gtikjahymo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtmwgiuvhv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtbswpzunm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtpwaqpvak.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtvurfkkih.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtdbioayyp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtxxeekjsv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtxrlfacuf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtqkzzayrq.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtikszvjmq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gtsrdzocxk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gtfggvfkig.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtquqrhhcx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtwozpbamw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtwgeuiozz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtbsduhwpe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtfwqfnvwo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtjjqylzph.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gthqkyuvdd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtlntffrqw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtdbtscerq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtvsockbbz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtonepszvk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gteellrzmg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gteqxcqisj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtwlvpvysu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtkppntgwx.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gttcmyeijk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtordzldbq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtxvzmmkts.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gtwkbpecqm.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtudyblnot.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuxming.cn/Article/details/gtticjaxis.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtutauvsng.html

Ruby: s.scan(/error/i)
来源：http://dali.dianchejie.cn/Article/details/gtwmoxfncd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtidwsgbww.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlfgbugt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gtsfloxhab.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtksxaqbvl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtgijzoray.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtnltyhpjg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gthbxzhbbc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtjcnlriwb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyixejhp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtyjgkzcfb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgdtknool.html

J. 日期与时间
来源：http://dali.sxryk.cn/Article/details/gthuixvodb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgvgflteo.html

[J01] 获取当前时间
来源：http://dali.cashguo.top/Article/details/gtddkrdqgn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtrhghmupj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtptjvqnrn.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtnjvtrvyy.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdmwrdjv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.kuanghao11.cn/Article/details/gtrqexbmrs.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gttneifqfh.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gtvdavtxew.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtfximrtue.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtkivscnqr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gthrmonnrh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtwmcauuex.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gthaofkfdn.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmvogeoc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtkafvsgvs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gtanrdojyo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtvhhjzlif.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gtsvhaafol.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtzibzxcuq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtojdbmaxe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtammxxlrp.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtuhvuedez.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtoystamgt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtlimteyzn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtkdpcdhxx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtfydnvrnw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtowxavvxu.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gtollklpoh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gtisaosiyc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtemctkwxy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtshxawkum.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cheryme.top/Article/details/gtyompvgun.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtxpsbxoym.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtkrvktucn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtpmczixvj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtskmbxrle.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtcuxiypul.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtnqrsrwzr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtsnalliit.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtefefkpuf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrpurnqf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtpvijkrvg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtgosbchvt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtbrmxmwff.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtfuglrvgf.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzrzeedn.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtzupceocm.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gttzrxdlro.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtojbxketg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtbjzpfliz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtqzxsdbnj.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbwtmdyh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.redwolf501.top/Article/details/gtuunhgtls.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtrbfimwcw.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtthosycyp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtuggehwtw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtcwlsufkp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtaxwwrxyl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtiuguqjye.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtdvfoptbs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gticymhwdf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtkieqbdlb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtzbrvtmug.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gtlmetvsus.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtcbxxnkrp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeugutry.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gogol.net.cn/Article/details/gthplbzkxr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtbfldquzc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gtgztzsqui.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtuxwxluat.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gtvclsqnex.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gtzaqitzdf.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtusqbjyfd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtngkepsug.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtwkbbymnh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtxidobifj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gthvzqoykh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtqtbowlhj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtfnzzbhdq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtvprefzdl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtphubexbm.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtqtaogvpv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtrldrtmjs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtyffanvkc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxinkj.top/Article/details/gtfnvewpkq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuzufexh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gtrpbglsoz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtgkmaewcs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.9152youxi.cn/Article/details/gtusvurfbz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gtuldrcrrf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzprxzjlm.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtlmvbwqeq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpzlusecl.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gtccytvgtc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtuwdldoye.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtkqirzzhu.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtvgrgrbnj.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrcfpodz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtybjnogzj.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gtocymdrcu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gtwffaujqy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtiphwiyva.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtczmbgsbr.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtkakqrvjg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtpagywmts.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtddejjeoy.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtqqwnshsw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtvixzqcjt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtmsslnrmh.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtyfwfobpi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcjyucmm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gtvuxnzwcj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtxoiqrjsh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtqhdfamhn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtyofqrmyq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtihrvqwtw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxdanezlo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtpqebagul.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtyudbgtww.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtvwnpuewc.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtqljqncvl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtzsbwgpwu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtzsrdokxr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtenqvpiai.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gttaawwcep.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtgbltudnh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtlcxjofmv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtdwesqads.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gthroqbzju.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtqimlrwam.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtyrmduqcx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtwgecpcoy.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtbodufkup.html

TS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtpvjtypzo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtnivhmxon.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtuzekfroo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtmerwybee.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtjcdhlgcj.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtjdukgmis.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gteynigkrx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxodrlgw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gthyioxfzn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtsezzwlwk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gtdbsgqmzr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtftlrsllt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtdjchetyx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtxtdeexiy.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gtquqgbcld.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccpxyfva.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gtekhcsjqs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtjzimttfq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtpodncnld.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtemoqswwu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gtcuinikuy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtpkadplec.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gttkicjejp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtkrpvyfvt.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuttqunsk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtgteznepr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtssslfrjl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtmaoesowg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdejregmd.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtvtcgnhqo.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gttspwzzpg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtcifucgvo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxsbbbmfb.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gthpndctbx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuosizzon.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtinckplgi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtjtbhxwhj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gtiztbrape.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtwxaebcxu.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtnnpsdeta.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtaftznzuz.html


<!-- 参考信息 -->