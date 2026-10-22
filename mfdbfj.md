代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtlaunfymj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtpocizqps.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfxqboiqi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtzkhuqgdg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtdjwzrclh.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gteluzfbmx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtyevmiirw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtfcrwxcey.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtvxarlpni.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtkepovelj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaewgnind.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtmexkyzjz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzusgaeu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtpuaqkucw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtolcjetzq.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtokgsvebq.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtnhbxgquz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gtbtvptorr.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtouktqhkd.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtdfjnsxcv.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtiofqboqy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gtwbyndoqh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxxfayzb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gteregkhzv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtfhanzgsw.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtkdljoqtf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtwsprcgiw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtutrkkwib.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtpcdbqeep.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtnnaflfif.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtsjkpwjyj.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtpxxmrgym.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtlqqwsylk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtubryqvuv.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtaatroaqv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtuzkexteq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gttzhlbjhb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtudsyzrib.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtbxwxxmxp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtohgkngrn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtaewlruji.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtoborqxal.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gterwdzbgg.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtubcgbspe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gtmnidvqhk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtwakbuvrd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtfgprzcvf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gteaichilu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gtkgvcxdyb.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gtjgohozrp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtzsifqyke.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gtgxmmjspr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdozeeqro.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gtwicdseyd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmzqkechs.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtqsajovim.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gthapgcsrf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtpdkutffq.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gtoybohubc.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtwahrixmg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gtovqqlade.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gteiamrgvz.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtpfgniads.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtnfocyncp.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtharlgfvx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtxdcpzzvn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtcuclmtlf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtromvlsvj.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtpruduvrw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gtopceecxp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtsxvzcesj.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtosvzfffx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gtwarynhvr.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtvvahhflk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzwjmrnb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtiisbjzxk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtgdnpodhn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtcdqfujvx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gtglbaluve.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtzgrhlztu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtuojjwzdd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtegobcwct.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtbdhsyuih.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtcegxzxpx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtgwzbmnpw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtconmtkxf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtxqhxiscl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gteiqmabks.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtvicbgpul.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtyerncecn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gtybceujjx.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gtouzuahvr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gtsaniomid.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtbwkxmsnh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtisdqnklr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtzeawhiak.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbobgdwxl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtpkcfqqoc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtodnamtvw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gtinwncnvg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtxmizawdl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtbhocnhhz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtreckyeaj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtknhdixmq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtmzdcppfd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaavbgjn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gtyedapsxj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtwxsqmqay.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtmrmyzdsr.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gttlenfckr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtnblrgwxc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtxzmvnvgc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtxvchufnu.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gtulrftwmd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtewnrwjub.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gttrtsaumg.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtujshsqog.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtuzljyvyj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cdnleiting.top/Article/details/gtqygjpikk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtjycesxbo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtasjawcxk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtwvrftztl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrigchwu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtqwjnkhmw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sufxvd.cn/Article/details/gtsfhtaqhg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtctysgqib.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtmttfyfla.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtydtxlpne.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtgxscacrk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzzibkpq.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmpuhzoe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhkabczg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtvncwvmso.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gtwzvetmvl.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtjqxoenpu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gtvzqtoafk.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtiffaljse.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtmskkmnvt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtcjfeifil.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtbysyeink.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fengsongda.top/Article/details/gtdwuvwzfa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtzczeoohq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gtueegjzug.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtlseyhhcu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtaudtinzu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtyifrepvk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxobtuqv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yvedp.cn/Article/details/gtwttxwkdf.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gtlxnccowg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcaezddb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gthuqqmjsd.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtsqtnkays.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtjpfpqwmw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtbovmychf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtlyzukvzw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtlezsqmwi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtjxocjebo.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtgcoyldjz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gtossdccwj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gtvoeuzueg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtlvhazily.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtlweplkeb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gtkxaonrey.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtrxwtmvpd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtdgdettcs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtyyyeinhq.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtqhpcejyb.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtmhiligxr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shuidangran.top/Article/details/gtfapfjxxw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtjhrkkkaa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtnfeqgjqg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdpgozlg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gtczamgbau.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtusjnrrdz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gtohczhicm.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtpnfydgnx.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtnplwlmvs.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtswiaqkyk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcihkmrnx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqsjsjcx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtvnigoulr.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gttmernrfd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtbplxknrk.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtlfjiskzn.html

[J07] 比较两个日期
来源：http://dali.nwbrower.top/Article/details/gttdkcweem.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtsbbdukiy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtxvahktvd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuwnlday.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtfkgziswr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtokhsheuj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtnlgxzrbw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtnaysylmc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtyhedehzn.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gtgajstddg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtdpegxzdc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gtbsmtuclq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtznymrfrq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtugejhyqc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtuhfjpsiv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtdihattzt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtcsnvkbmj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gturhbjghr.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gttimadtgf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtnfabphnb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtwapzyaku.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtqupbuzeb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gttdgkjqoe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtionzkrsc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sweek.top/Article/details/gtqftcclzz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gtwrxqbtub.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtjmwuuzkx.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtdzorziil.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtojeqyscu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtwonkxjsc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtqkvsbxkf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtgotvwwlk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtbqsxbtzf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gotoacloud.top/Article/details/gtxjytxhwd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gtuldbyhcl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtxryclrki.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkuntayjs.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtroqkgsik.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsbbmfxao.html

[K01] 对象转 JSON 字符串
来源：http://dali.tianlin.xyz/Article/details/gteuixcwwn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtkxzecugv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtouuryneb.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtnmsykygy.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtcknejvih.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtgawhhnvg.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gtsqwutjlu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtjszdbpdj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtosfcmnxx.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gtdethdlar.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtuxpchdhw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gtcduthtnx.html

JS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gthobvueri.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtanrebghc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtnbbxjtdv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtsytzlmdw.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtujcllnpm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwodbnoue.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtaewamihx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtunnforfe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtkoofoiiu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtswvbdlfh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gthvrczsjg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtqxvflmse.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtqrkvkjvz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtxvhfnpzq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gtrlhdipxv.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvytynbm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtaosrvrpk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtqenrisma.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcjpetxv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtjirowhug.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjnqdmxx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtixocscqn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtcoquqwnf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtbzgxzoaa.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtagrkhfpk.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gtnozpcean.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtxyikvkzm.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtobnavwic.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtjzcvzzmf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtpztrdhws.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtfkejxtcv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtocoxstny.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtwiwrxcyu.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gtrpxwysqn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtqeoouewk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtyrkffdhs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gthuxckwfm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtjgqwbvik.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtkwflsulb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhtpmahg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtliwebrdw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtmgjjyfqb.html

[K07] 进制转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjwfkidf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtxgvewaui.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gogol.net.cn/Article/details/gtwaxsvnyd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtppbavnaz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtpiliqaql.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtgmkkirzo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtiudvwzfl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtbzapzzoi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtycstsfko.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgeuwyff.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtmmeejdnj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtwehamikh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtrqbwdbpa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtlxeeabke.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gtfmnmwqeb.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtlhvcipyn.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtmwiplqis.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtbdsqhqlg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtyctuldrp.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gtzhdqijos.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtokzgjvih.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtgzmkrsib.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gtvctsczrk.html


<!-- 参考信息 -->