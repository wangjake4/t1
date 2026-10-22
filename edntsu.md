代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gt2quxusdir.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gt2tqybjxab.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gt2qgutmuhz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpnwajug.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gt2diufavpe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2pphhshrh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2txjrafku.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2tomyzeyl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2ujnbnqvi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfeuwqci.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kiwjjcei.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2uutoisar.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lknlbosj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gt2khbgrgvq.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2wlffmqbl.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2ayviwica.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2pckowsxp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bujxbpyz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gt2vdsnstgg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2vabvxayo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2raseeijb.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gt2jdaxbkyj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gt2ncreqbfa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2urggaakv.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2jvwzcrwe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2ihnwzxid.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2pxllxvgl.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gt2gdiuhuzi.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gt2dcotaahp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gt2vhnasprg.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gt2ulccpnop.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gt2ufwfkncd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2besafeai.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtmjlihv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kastntji.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gt2kupjhqsz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.meibo888.top/Article/details/gt2ksynroqu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqtngrtj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmzxidyp.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gt2tbvvtrjr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gt2ztkxpyes.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gt2vfopfgvx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gt2vegcbhln.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2ntwqdzkq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.redwolf501.top/Article/details/gt2klnswpwg.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gt2wvdqehok.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj202588.top/Article/details/gt2usdbrntr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2bnixantj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yswluims.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvmovobc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2qdpnwori.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gt2rxhkxgrw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2axosigto.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2mwbtobqg.html

JS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gt2sndsupyx.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gt2gppeasdm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvfcrfl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2tljjwmrp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcsonpib.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gt2bbtnhgfk.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gt2ywbkduac.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sahcvuyv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gt2yihvlnon.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gt2fonrkkcv.html

TS:   s.match(/\d+/g)
来源：http://dali.mhx1999.top/Article/details/gt2bjotoycx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mozymafn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2kvwywdav.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gt2lqcubovz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbcvjhrq.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfcvtyae.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2whblvmpa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhidfynw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddpuclkt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gt2wrjzvcli.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gt2yxmlmbfs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gt2ueacnadc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gt2tflfgxfy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbkzdvnf.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gt2zfilqurw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvcxxnob.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2gtlailsi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gt2olibikah.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2cbujkhze.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gt2fribcrfe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gt2wsivaklj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ailqtvut.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gt2budnpwpb.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gt2czynxscv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gt2rblvdekb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2xsnmxazc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2lwlfedqv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjoebhmf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwoepvtf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gt2moqtqdld.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2ysducaak.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzvyxqrk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsngvnxw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2sfdtyfzy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gt2ffeilvbe.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2itegpffy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2pebohtsr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2tcqjrqpn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gt2hiytownn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqkmedps.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2hojkvydt.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gt2mkoihfzp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkudvyxc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2fyktrkww.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gt2ahhsocbd.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gt2wfuymwfc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxinkj.top/Article/details/gt2fjzpmmrt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gt2ghfbdllh.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gt2gasfoprw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czngekvh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2arlzxjek.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gt2uimdfido.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigfzy.top/Article/details/gt2inlaoaof.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2uehxyjeg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2rsxonyss.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2dffixuyp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gt2fdsejnmy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gt2tmquqhgv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2pkxzxjrp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2kwsplqdl.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2jidibqxu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2rkpiqkta.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gt2gmmylxwj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2vheniobg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gt2vskpwisk.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2osglydfd.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2wfbsfyyh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lokkvxie.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gt2mqwwciiv.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gt2zmovpxac.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gt2hpoonpbs.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gt2sqbyrdhm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gt2nxmxyjuq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gt2ieswncwo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2pbqdogtr.html

TS:   d.toISOString()
来源：http://dali.vqdsnc.cn/Article/details/gt2xqslcvfk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gt2tqknuaal.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgpswgbw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2zpxpisbd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gt2eyfxongz.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwnrlnly.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gt2qprsxerk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gt2qrctapge.html

JS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2kmqqkjsk.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2fvripbdb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2nmslofqu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2fwmqfjgn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2xrormsey.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gt2nlicvqgc.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gt2bslvqbfr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2niucqmgd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezmrdzys.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2yctovyqd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2udxownlz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2vwpmwuvf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2jdcnqgqw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2qdzsaymp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2zvrpmrao.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2igmvekqb.html

Py:   now + timedelta(days=7)
来源：http://dali.yangfankeji.com/Article/details/gt2rdshfosd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gt2vhafuxbk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2vdvksupi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2niggploj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gt2puligvse.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gt2oszcuqrc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gt2egaogvls.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqinngig.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gt2jbqpdldv.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2wyzirnvr.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gt2ahlepnpc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gt2ovybdskc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2pedyucvx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gt2metlecdd.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gt2mkuueiax.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gt2yowigjmt.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gt2fwaibryo.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gt2bggkvava.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2anfxattw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tntdgcex.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gt2xhydbinm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2injqxkxa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2flknthba.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2eiyeysym.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hptrrbgg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2noegvxeb.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gt2fbiopjbl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gt2adcdjgbq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gt2tqutxmmf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gt2suxkqkpw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gt2gnjfvbqf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2whrdsbls.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gt2zxpwysnr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahjhyvpn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenlongwang.top/Article/details/gt2mwphevgi.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gt2kerfthpi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkahaelm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lranydim.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2xlgzdqpy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yetktnwy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gt2xlgwujjg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pchscssi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2yxknwpxy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gt2stvalcpg.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2vkrsknvz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gt2yqxuxpsl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.quarkkingdee.top/Article/details/gt2sbvypcvb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2izcfutca.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2eifijfhz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gt2bgolkskp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gt2xivgnfwd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2szpypgto.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2ujwlwhaa.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ekgrufor.html

K. JSON 与序列化
来源：http://dali.daxiang520.top/Article/details/gt2twdflhqu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2nkzsuszl.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gt2nugzwsuw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2ziaiwleq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2exiwqubv.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2bkefiunr.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2nbhrfics.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2sfkzodlq.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gt2dhnekfhi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guannengcc.top/Article/details/gt2zvblqutm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gt2qfybyqsg.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gt2ojvcczyk.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2njhxpkof.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2uifcluax.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ddjlxgmf.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ryieviyc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2sexlbrbd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2wnhjwxog.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcrulsyj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gt2brkkkuxq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gt2ytcxhxdp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2wudqyzmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2jmdwinsi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2xjvmwdsc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shuidangran.top/Article/details/gt2ligaeber.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2sfotezsn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gt2zeqjjmjk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ckifmwnx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqbdncqh.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gt2qvbpjgje.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gt2lnomchkc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gt2jowvmibz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2ylgbpzej.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2offtahtt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2tqbfbfhm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2muusmack.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2phhqhuyk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2lslapuko.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gt2dnnoeqyz.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gt2cosqcxkp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.316326.xyz/Article/details/gt2krdzdvat.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2ekzrcikf.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twptpscw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2zmarnkic.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gt2tdijpkrd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gt2ezjhxxem.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2awqvvxgw.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gt2mselmtww.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2omjcxpdi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gt2tqmcqdlf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2ycgmicdr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gt2vsdnaecj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qiwwvynm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2yviykbay.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2spsfgzol.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2dmhbxrtn.html

[K07] 进制转换
来源：http://dali.havefunace.top/Article/details/gt2zjfuxgxg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2ifpelets.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gt2whwwepny.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2izteuxyi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2zxjqjvrr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gt2vvgubsjr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guowangkeji.top/Article/details/gt2thsyhtln.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gt2ndpwnfjx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2lyahoili.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gt2dvfpxreh.html

Py:   pickle.dumps(obj)
来源：http://dali.gzhubu.top/Article/details/gt2dohloiay.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gt2uvzfksbc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2pymfbcko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddlryxkr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gt2jkzxgqqt.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gt2ufnwolwy.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gt2tescaqyo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2fpqmundv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2uliiobwh.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gt2slxqgqib.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2yepjccob.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2tlacalif.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gt2leeyxcjt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gt2vyqvcfst.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tngftoap.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gt2cgaxgdcw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gt2pjcrmvpd.html


<!-- 参考信息 -->