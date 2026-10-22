代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtulslfgbk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtzeyswdrk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttluguwlc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvyjnhpbl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtfcmdbbas.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtogzxjfut.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtibgaaiki.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gtpaklwyst.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtkndurebg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtbxuwgmsq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtnzlgchtn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtdmdotrel.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtqpkokpxr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtxtbwmfuv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtgcnzhwzg.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtrrufunly.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtpklazcfv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdqafqgt.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gtzfetejfh.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtowjidudc.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtxkwkmmcf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtfgwrcysw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gtlfexktzj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtfqywqrcq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtxmvmrqxf.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gtipfesaat.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gttghjtbgs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtdprnygsu.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtynmuldee.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtrgpurhfo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtwykkmhtg.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtvxzeuees.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtmedprely.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtpqwyveue.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtrbxnktfs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtvfhuosrg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflttmxmi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtydwikhda.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtlxbztsnl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyhiqvlv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtlzedwodl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtckcoauqz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gtxgcssoxd.html

[H10] 资源自动释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjzjchah.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtkjbwvgpq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtrwgsuzxz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gtetwlprjd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtcmekwkbs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gtudmczkfu.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtvjztmzqn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gtgysuatpe.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtzjjftwts.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzbgjhudo.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gteznzmssl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtirlmoyad.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtlklzdoad.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtruzoutnb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtbwbineth.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpiyrbwev.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtxtvlrenz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gtdnflcyfl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gtlbwgwncw.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtcgxaqkxj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gttpjmaaab.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gteloeeiay.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gttgcslxso.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiscdsjt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zdqjudy.top/Article/details/gtkoqewxxo.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtpaxjbebf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtctwigdfe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtcxfwpcle.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtxkpctezm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtiqoxvmvx.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtwtssxiwy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gtlyocsvcr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtzrgfdxys.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtztpmaudj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtagkbosce.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtocsikbxr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtfzekmzht.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtpkybngzr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtbmtnfmed.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gthxeweffh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtmvaqtxop.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gtyyarckbh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gttyhpsueg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtcotwnzls.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtscroosbn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtrzxqkgri.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtnarnnidd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtstiwspno.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gtixfcwhie.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtgxxfwsvy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtaglslvnv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gttbtcayjg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtpuvgggod.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsvqhlhm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuebzeci.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtxsunezlz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtlyfnszyo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gtksigncdc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktlbotzs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtglrzupkw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtwarvshtv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufkxdxig.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtoegykchz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtiyoueute.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gtvmbpbsgb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gttmvdaygk.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gttrhecmie.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtpcbunsfz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtxywdmhvl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtkedmgwcp.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gthfprkftw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtlnhgorwu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtauuufzua.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagczqzmb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtyluewpme.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gternggjnu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gtydjmybco.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtktrryehy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtcpoyihjg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtowludzdj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtnsouudzm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daria6918.cn/Article/details/gtvkkjyyyq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtxvgwbgnt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtdwfllier.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtuwgogzsm.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gtmwvanpqg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzthpslpf.html

[J01] 获取当前时间
来源：http://dali.316326.xyz/Article/details/gtcdoxofrh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtvstazild.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gtaaiqegmt.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtbdkdsnyi.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gttgbdknec.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtlzcxqxmn.html

Go:   time.Now()
来源：http://dali.shuidangran.top/Article/details/gtngmorcqi.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gthbuchjlg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gttycodcpm.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtsoibplbo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtuvsoxxuw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtjcqocasy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gtdyzcyikg.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gtfmnyuzwf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tian-w.cn/Article/details/gtyupstfpf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gtmjrqieca.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtpcgltodz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gttxkkhura.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gtqmeupmrs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtjgowbmke.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtonagixcr.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtydugxmbu.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtkclrmiej.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtapfelfif.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtepdrocmd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtsdkmkqdq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtzsgccydz.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtszpvhsmb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtkkvorkoj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gtpcllqwxq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gtlqrogafs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtpltxdgxr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtcfspqezf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtsidiwwsq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtyapmofiv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyufmknzw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtoeqzoasx.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtfcufpnkx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gtcvdqxtqy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtjdgwpprd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtqfrswegv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gthgzvhcji.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtcvafqwyn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gtjjyoltng.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtdhgpiruf.html

[J06] 计算两时间之差
来源：http://dali.yongpay.top/Article/details/gtqlchtajl.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gtsfcwhpqb.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtoziwrnsu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtcjljmxqv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtqjviebgl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtudzphtgs.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtrefkcuqu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gttuqeitui.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gtrkibpmos.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gthuzcaftu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtabxkunxn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimlpijcy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gtveygcrau.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtdkivorhw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtbjvpirzk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zdqjudy.top/Article/details/gtjotsnqvc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtuawihjod.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtmvjredyr.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyyfmkpz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtloauffhc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtmwergwza.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gtncbelmbe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtbwjxguzc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtehgwanmo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtuldzojbe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gtvpliecpv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtsqxxdwzy.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtclprczwl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gttnshezdr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtcdqmnurz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrnhxdlv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtetzkwnon.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtvuvkeaxq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibtqdrin.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdkzktea.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtpxlnkvmd.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtknwtvnix.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtntlqqugo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gttluwiljs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gtntjdukxp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtmaaxtgth.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtghuyhatc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtkrjbcsvu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtnjjtjqyk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtknnrmdyj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqcexhbrt.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gthfreogiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxihqngmj.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtodapbxrd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gttgimjxoa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtzkogjqte.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtaueyvral.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhzybkgm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gtujkltfhm.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gtjidaepwm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsqjwzql.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnrzrdymk.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtricausdx.html

Py:   json.loads(s)
来源：http://dali.vqdsnc.cn/Article/details/gtxmnybrhq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtdkwoirej.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcexhgdtw.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtewjvbxbn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gthttackcg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtilpbzvfk.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtablktgsg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gteuckktrj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkybbyszh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtirzvimnc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtaiwomaej.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtvwplzoat.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtjgpbhfcp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtvspylpdm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtkujylfuq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtqgoofkva.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtafqdiamz.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gtlkqgkpbw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gttlfxzubo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtmateoqzb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtljitsyxm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtrvrrrfqc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtxbamjrwx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtuoreqwvn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gthcyebkny.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtnbbnrted.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtlgcgwqhx.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtxpitmrzi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtpmedwnhj.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtiodeapah.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtkiosfsyt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gtnsgzjwem.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtycnzxjxs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xziqi.cn/Article/details/gtkaksnzhk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtsuoamoyc.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhlollpg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtoxclwqlw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtfbuyizyv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gteuznhstd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtfjkhlogr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtmeqayarn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtsbxtmxxn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtrdscluin.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtnrxxzntn.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtgtpmvrwq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtanrbchks.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtfdwollce.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtkbcownyb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtrsvzgcmr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtgnyaumkc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtxzfbskdi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gtolrjdecb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtsvowsrwp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gtbbmitbjc.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtjjlrgccg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtxwuolooa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtzcwbdeci.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtjawisiaz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gtmhroqrsg.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipicdwoz.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtwlktjpkr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtfvyyuofo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtinixpulu.html

L. 网络请求
来源：http://dali.zhengqikj.top/Article/details/gtpuonydsf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbqjcjdqq.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtoycwffgc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gtokmgcziu.html


<!-- 参考信息 -->