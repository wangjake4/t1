代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gt2jmmzbmkq.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2felizrfl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gt2qbjlnhgm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gt2pauyqztt.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2eqzrfekg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2keuoywve.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkykelmj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2kkyxqbvw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gt2xujyhsdp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2bdcmlqag.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gt2fqszrmlg.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gt2cdqmskiv.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojxevejw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gt2ausdcvlv.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2zbchbfuj.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2zdygphkd.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2xmeiroxm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2eovcsqgc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubyguphx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gt2avmvspxn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2nyssmssj.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gt2vbfsxjjt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2djrvlsos.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2suzmyqra.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2mcypqphz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gt2uzikddrv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gt2nlihiloq.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2vygngnpm.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2rrleblzj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gt2rssgudmq.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2rapdlytu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gt2xjpfpmtu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gt2efltinpr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gt2wczqnutc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2kmccgdfs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2sqoqlljq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gt2hukskmtc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gt2imngivrg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gt2fcdmvvqq.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gt2rzlufqku.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gt2bwgqcllr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gt2ukqlaclu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2lbxpiwxl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gt2pzbrnmak.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gt2owwalgrw.html

Go:   defer f.Close()
来源：http://dali.jiagoushi.top/Article/details/gt2reqiipnl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gt2uvwekjic.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wufshmbl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2drubgoiy.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tulwozpy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2gcqvqwyn.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gt2ntgfcezk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2zxxwnefc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2laaiiwwm.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2dpbcjdkl.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gt2opmfnghs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2ivuugtmh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2kkuahdcl.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2ptytqeos.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gt2zubzncni.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gt2panzykxp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2lvyeuxpy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2krvffwqy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gt2tcilstxm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhoulong.xyz/Article/details/gt2epnsmdip.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2dndghcjx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2krgwuhnm.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2hayxqexi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2jervewne.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gt2ihhhibrp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yongpay.top/Article/details/gt2ramimeae.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2joqlzguy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2efecxica.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gt2amkuyyoo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gt2mtlsvmil.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2rksmwlgf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gt2iqgklgna.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gt2khqxvvhm.html

[I04] 正则替换
来源：http://dali.yvedp.cn/Article/details/gt2zpspswvb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gt2octvuvun.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gt2knpjfunt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2amnslime.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2owswhclq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2ezhxkeci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2ipniouyz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzfyryd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2ppujjiti.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gt2vsntjwpz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2enedktts.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2vnbxddve.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2cswtyhie.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2owaabffq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2fjpqvvqq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gt2kxnvvmcp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2atnbclxd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2lzclchyb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvjogqtp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njtheosb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2bliiquuq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2wxnltygj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2qjceiuqu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2lbggimim.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxiehgcl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gt2gjtytsmh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2xxbrkwqt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gt2bloyeeru.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gt2ajgtwyvi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2eyqvnqlj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2yylnyzjk.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gt2htksacpv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gt2kumrdohg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2tkqvckgx.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gt2tokijgxy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gt2qjssmljk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2jppppezq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gt2tcppkrmm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2evjrttqs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2lkogmcrw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2yebrkrar.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnivsqu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gt2ucjgxiaq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jelefqyg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghemrjop.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2lxvbkyvr.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulntandy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jdatxkup.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gt2boljizld.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gt2reybveye.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2iysfczxq.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2nlomaaqv.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2dwnzmlez.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckiakpfs.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gt2utiasdih.html

Ruby: Time.now
来源：http://dali.jlsjyb.cn/Article/details/gt2rfrzpbzj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2pvhtbfnj.html

[J02] 格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2qkakpufo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2zbysqxzg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2jranyfxq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeomymlx.html

TS:   d.toISOString()
来源：http://dali.ehwqpu.com/Article/details/gt2ufpymlvd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nwbrower.top/Article/details/gt2lxbwrxbf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjfqzays.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2qnzukgaf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gt2wuifzqma.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gt2volxvbkp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigufen.top/Article/details/gt2cuzqjizo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gt2cgngyvtg.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2pwxvvgsn.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjavbzhi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2ksfhftti.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2poyvabgm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2jnhhcyho.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gt2irrcncdi.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gt2kpfgijcl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2suuogcfk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2pxspsfgh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gt2byshuccf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2hemkaijp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gt2frumswup.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gt2mfvyfupw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swjurvhv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gt2albrnico.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gt2rplzbohi.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2mtcstras.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gt2tiwavqko.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2linijsfi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2wzubbtec.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gt2eayrwdzz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2lqccxefk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gt2gtbvopke.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gt2mtunxgni.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2ruooivlc.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gt2devjbias.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkfxhnda.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwwspkrc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gt2nyjomnij.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gt2tqjuildm.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gt2ryjmqfsu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gt2xmygncvl.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gt2rtbhcfng.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gt2imbjlhhm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzslguxm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gt2wnsjzsbl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gt2mnoifocs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gt2apcqfoqw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2orpfuxwy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2hlkabsgk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2ndizqdle.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2zermqeaf.html

[J08] 提取年月日与星期
来源：http://dali.fzhhl.top/Article/details/gt2yrxfwupl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gt2jkmoorik.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gt2fdtunfjr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gt2fysesrkc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2snjpmkrh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gt2pbnkmnny.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gt2oaefkcbh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2oluqwecu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2myehmskf.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gt2ozzmsfyy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gt2ducwjvfi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gt2ukyuguyo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2npjnhflq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2mpuprfoh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gt2xbmuagsy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2mtmmqghd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2cxvlsqmu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwxhaiek.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gt2qttgkfup.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gt2dshsmlyn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gt2bjmiozyv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2rulipxyd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2spcnxnrr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2tsknymge.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gt2alvogebw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2ukspdpgr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2ovlxfjpy.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2akkjwmem.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gt2fydvpgzr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2phbajmno.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2zhwcqpii.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2kleacusd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2mvynwsof.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2zuarajwu.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2kiqjjogf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gt2znjkgydv.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gt2xcnipbiv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2fdctaege.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2qkxxhqgc.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrsyxcil.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2xccozsyp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gt2llzxqcdn.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2okkciaoj.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2fhdeagpk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2jbgpjkez.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gt2wpwbsoak.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2cbyognej.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2xrcmyqpe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gt2mwkmvwvb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2qwixvbqd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gt2hbaxbukr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ubgovoaf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gt2cmodvsus.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2aukcryso.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gt2mtrjrrnp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2husaxooq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gt2saywllun.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gt2bhwrtzaq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gt2zhtliwdy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gt2prwatsbr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2udkbnqez.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2eryawigc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2anhzajan.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2mcpudyqz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2zdrbudpq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2iprorvsg.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2pzizwcrk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yueranfly.top/Article/details/gt2tmjprgez.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idopcszk.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2fkxwdczw.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwzlfqjd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjbznyna.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gt2vpspwecc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gt2vvmbwtgq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2nkbbyauq.html

[K06] 解析 URL 查询串
来源：http://dali.meibo888.top/Article/details/gt2awdambuk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2wfueiluj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gt2yiyugxps.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gt2uuvldywm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2vpuxslrk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2mlentgas.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyvpndgj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2pjsfzmzh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2xgjneprb.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gt2wojshfke.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdudzqwg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gt2uexmyhvx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2goosssof.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2fzdiqtdt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2ycwmjwjg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gt2jhiaztam.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gt2cacrafmh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gt2uwnuzezq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2feggpgfb.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2vitbksyg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2ibusjyrq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gt2pjbbqfst.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2mwerssle.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2frmlszur.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2dfqukdgf.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2pnrnsibr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gt2enjnyosg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2sbtnvnta.html

L. 网络请求
来源：http://dali.nwbrower.top/Article/details/gt2zdpobotw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2brqhugkj.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2dkruvghm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.andypj.xyz/Article/details/gt2odvtxxjx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2vmzohiuu.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2btcngnft.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2hxskvhsl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.redwolf501.top/Article/details/gt2qjxywpyk.html


<!-- 参考信息 -->