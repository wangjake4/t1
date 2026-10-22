代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtsfejbhjx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtuqymlqvl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtaghyvjzt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtipyeafzx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtqpawxoph.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtrghtgdci.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtmgjgqphj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtjoobufib.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtxwdbqzif.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtymnjmixd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtwfoncjbk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtjogphpvc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsqxcjjx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtnmwqilar.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenlongwang.top/Article/details/gtjtgwfptr.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtdimuyufe.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtkxwiohvp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtgtvljtbi.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gtmjniywgz.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtgaggepti.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjzyvhyv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtbnldpzds.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtoppxwssd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtchfuicce.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtttyiavca.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtvimfmelh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gtufviggqn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gtmuojftqb.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gtiojewtnj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtujwczxyt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtgnjiykgb.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtedflhswq.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeyzftgd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtdtxiubau.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gtyrfwmfrg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gtnsemzzmy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtqsriboix.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtofxanugx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenjidiqi.icu/Article/details/gtqapxkxlw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gtranlaklz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtqvvqrpvp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtgpzzxbie.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtozpwguvc.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtdomspsqn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtbloirhdw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gthxrtovvu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtgvupxccw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtlhichplw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtxtbakkky.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtvisirjog.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gaohongyu789.top/Article/details/gtilzzfqkm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtybpgcdrn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvqhunplw.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gtfhdilaik.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdjbidutt.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtxsjdroyw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkixjbcxb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtcxcypztq.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtkywbpzad.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtjqmallur.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtuuyytibk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtzygeftmc.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtfjacxxbq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtbdezxyvt.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtnzrikkmn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtzkmodyyt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtuqwaonff.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtqmgztlqj.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtmctwgvzn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtjpmpcssh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtyurxkgim.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtcxxscgad.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtsnwnwlqq.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtejmhwndc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gtpqayswbx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtvjlvkvpt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtayyoxnfg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gtqkuvusuj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gttbhuwqul.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtvpeaoqxg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gteukmffpn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gttwzftpav.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gtufygywak.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtwxsgubwn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtuperzejp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtzcpmqqvp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjtaypbi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gtjssppesd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtjfstlbdu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtxyochbyc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtgvxohbji.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtpzcqcdqo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gtmvxuvysg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gtvpbqrhra.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqcouzrk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvdfsnil.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtdeeqrshe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcqwxncc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtyqnfyvov.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtjnfrtvoz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtskqkydzg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtwcbnvgkg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtdkikfvjq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtenrppxaz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtcsyemyhs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtturhrlgy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtctcbhsiq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtumtdkltg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtkztapssq.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtguzspkoe.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtxaudblgx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtibdtlodn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.0kj1m.cn/Article/details/gtwzfkqysq.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtykunxcvc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gtkhodvfld.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gtjrbxfimj.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtmpqbpdat.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.birdmap.top/Article/details/gtuspuhhbc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtmahmgedg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtbcohlevi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtaxietuhz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtfruztpec.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtwmeubsht.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtfloseobk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtfjszfwpr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtswhjbqsj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfhcmsui.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtouwyuohk.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtoijgrbhv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfuwxalss.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gtbjvdjlnl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gtrhegfrxy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtkmnlhhty.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtanpamhus.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtusumsgok.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtcuylbygt.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtqxczdjme.html

Ruby: Time.now
来源：http://dali.zhixingplan.top/Article/details/gtexmwuiqh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtcbwmvwgl.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gtanoltsdt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtoanwnqlz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtvulayqrq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtxvhlpjcy.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtupxkzkmm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gtcnkxwfhm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gthzuljmkm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtbljfaqwd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gttbauexgw.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gtxznmrxhn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtnqzcdduc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtdvbpqqyy.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtucthhffc.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtsftvcozt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtmigwnluw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxxuhluz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtyjgeywhz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtqinnqdmx.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gtozlizmdn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtqrfgikrb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gtoxylfnqe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gtogtgwlvw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gtoavxgvmy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gttraljolu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gttnmrjruy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtuerhwfmv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtkskugauv.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gthmcaeqrx.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gtmvkafztr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtnpmofvou.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtibmvyrjt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtpezyundi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtbugoxhjl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gtpacfebdh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gttbvwhlyr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtepuyibdr.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gtsvotdhwi.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtlcltklun.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonljggeg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gtltqpokmb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtgnqjegyl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtrwhtzged.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gtqczrgzxf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gttpgsiubf.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gtgeuuucgn.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gtyjpiezvq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtltggitmi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtzwealewu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtpadzeztw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtguqgnfdi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtwnlnvazb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gtbducvnpm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtrzemaewg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtmncfgaop.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gteplahoft.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gttwilewca.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtartmcnja.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtakfxffph.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gthviisdlt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yueranfly.top/Article/details/gtmkxahcuc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gtivzwbgkk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gtdezbqryg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtstlnbbqw.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gtqcnywzry.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258.top/Article/details/gtdgpefssn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtxvrvuuzp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtjrprrdwe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtawdoqwbb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gtnemsawmb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gtlluutiyi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gtkewgfinz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtozsfoxcv.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gteavdqcyz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhengqikj.top/Article/details/gtcnlbtjku.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gtgpgjacxh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtsgnpwcyr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtximanlml.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjuyseim.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtekmggahl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtrebbhdug.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtwbnohztu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtguhxigjp.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gtvslyjvyg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttxcdmsoj.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gttrjglbwu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtnsjdwizj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydiiafco.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtqgymzhlm.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtjvfmlnsz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtwsqrggro.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gtnuoaeghe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gtxchkesvv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtldkcsgls.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gtpvsflpls.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtqhamkpfi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtazyzoufo.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtczhqxmga.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gthxdukmjx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtoxhljtjo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtlgrkciga.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtimigujfm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gtqsefbndc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtmessksud.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtlulctmxi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtzxwtrmdl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtlrbfuwdq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtiuqnqgbd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtnjxgomyf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfakimjdj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtmeumupqk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtsrvslrbi.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtgmzbhhix.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtqxobpolx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gtserelhoi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtkkekweku.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtmtvwlwmz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtcaaxswfb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtboxqwtja.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtncrgomxg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtkzvfjtlq.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtehqtgmvh.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzahfsuwv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtkgpeorir.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtbwezyupd.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gthehipwgq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gtwrjyrmem.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtblyrfvge.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gtpgrrvhly.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtnculqnbz.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtcvndgite.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtimdfegiw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshxtkpro.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtmmtivvhd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtqxtcbhts.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtmprvhzdn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtvljwtqmq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtbcahlriq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtmsxxcvcs.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtzfxdknxv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtzleekrpq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtrwntfjxq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gttsyqxtiz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtuowdqrkg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gteicfcatj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnruflpam.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtcdccuehj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtigbbfcwa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtbbemmdwa.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtxoukgbjz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gttekaodhz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtqohdbeck.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtnbbuzlcd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtzicjxpqc.html

Go:   encoding/gob
来源：http://dali.yj20258.top/Article/details/gtpqvuwzaq.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtshahpqiq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gttjysvvkq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtynskqlpf.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsmycrdh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtstcrvaza.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtaxafwcwh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.haohaochexian.top/Article/details/gtlpqmwmsa.html


<!-- 参考信息 -->