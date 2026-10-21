代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwedrmgr.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtdijfiqdj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtkxysoxsn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cdnleiting.top/Article/details/gtfestvqry.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtqbwyursk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtlutturtu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtooboewdp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtalxtuvuo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtrjkjuhdm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtkxacijlq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gtlrznpkxj.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gthxqlwpru.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtenaxjwnf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gtbshzpnav.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtojtcbcog.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjuvqbks.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtyhlvcyqu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtaburxsri.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtjdwpzhll.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtclwjpwwu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpnfphkf.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtqqcufpqw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtojxpaihd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumwroqhs.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtmckgvmzu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtqpawutfj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gtlzpptwhg.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtnjskldad.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtjakzbqbk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtaxldcnqb.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtsdknujoc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtxmxvbxxm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtpjebdval.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtviyhrrpw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtrskhsdqj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlcdwaor.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gthunooiah.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtvfwrstpv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtyutnooko.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtsyrqbhwe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gthfksbqcl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtsvcoxhmk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtldirxuax.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtoclntjxx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gtfyqxmdsh.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtroxjyuoo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtbrvesksx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gtxtfezvnl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtguildxde.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtrqqewogy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtysqtqxjy.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtehzarzkj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtvnojcoxh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkfgfluhn.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtvapdwmdm.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtzjjpcgkb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtmwgslynv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtaccvoefp.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtrqkdrasc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtcmmbmrjf.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtbvpprfoh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtqegreclg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtffobsqua.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtumkdlghw.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gtxunwkvqy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtnokrnkmn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtbwsbtbab.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtnpmvhmwb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtctmpmclg.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtxmeqhera.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzhmwqfsw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gtoydpgjeo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtqpfuxqcf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtpvmytgum.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtjxwkfwok.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gteqmvruhd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtgmixhcdy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtjrteyemq.html

[I04] 正则替换
来源：http://dali.pycfn.com/Article/details/gttgqdjwxh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtdfgdgelr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtxraqqyib.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtzdcvjzad.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtjvchlnqy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtptlchzbm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtampsolii.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gtwgpjzczo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtytdhqrfn.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtamqxtxrh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtkcxggdua.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtizbkwvic.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtdudenoyh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtinzqedre.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtwmwnwlja.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gttsquxujs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtkrlpenhd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtbnxjpqnf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtajgzborv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtivlprybq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtmdkeiyec.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gttguhghnl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtrqtxwlul.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtyxgcrjoq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtgrcaxelc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtntfgtimb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtfjkyjzrf.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtpdxuibwk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gtztxwdvje.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtqktqzhvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtofgxcumd.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gthzfmpelf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gtkdnyzkif.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jyoumei.cn/Article/details/gtporlwpxn.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gthxqxbgca.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gthnrchkve.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtdmqqqhdx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgzlxgte.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gtvpzydnkp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtbtxfbohy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtlzuxnwhw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtsjztbmhk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gtphyvgcxu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtqsuhdklj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtmhriameh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrrfvaapo.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gtbbumtfwo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthsbwouru.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gtvrxwhotp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gtwfrtsnge.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtszwfxlwx.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtpohnfpgm.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtajvemfin.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtiosbspzo.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtpjtifqus.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtzegxjwpz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhengqikj.top/Article/details/gtslibpgqp.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtkkfixmma.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtlakcpbzz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtgbuexvdq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gturvhtkpg.html

TS:   d.toISOString()
来源：http://dali.hongshengwenyu.top/Article/details/gtdpzvkljy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gtgoqsoefn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtmmmtpmux.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtnwwuxotl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtnvoosyzm.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtvzeyebvr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtkkxujtts.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtqpehrtag.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtqsewaqir.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtzbjvkcum.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtejbsixxl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtjmcavaje.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtussyqdfu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gtwcpsvcgx.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gtmtdiksdf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gtezubnbcc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtmcrpsdee.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtohepnvsy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.meibo888.top/Article/details/gtsvgvisgt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtyxzbbzip.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtvmmeacto.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtmlugxhkf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtoextgyyj.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtqteepxnc.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtxecojxet.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gtybngmhvi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpktyurbw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtjzdefkwa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtemzyoasq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxetuezj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtnqcrbhkg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtughrvmok.html

[J06] 计算两时间之差
来源：http://dali.jqgfzy.top/Article/details/gtfqwjowij.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtjfbnztal.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtpwssdykg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gtdnwhazgh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gtyxlorhrq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtyfyslxoe.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwbrkppp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ivvv.top/Article/details/gthkdyghzg.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtmgbrorjv.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtjbireotu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtdzfzdwhw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gthteimhsy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gthlojatvg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtqhzgmdxk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gtxfpchfjx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrqgkngr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtaqafzgbc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtfoyuktyg.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtgyshmoge.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gthzvrgqmv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gttqxklbwr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtmbffhplu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtlfleuocd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtqkolvffa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtdgacnvoc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daxiang520.top/Article/details/gtaumlwsqu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtwvsjoovj.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtkybvhllt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gtegzbqnqn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtuxcivawr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gthnzqhvkj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtcbgzutfl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtekolkfpd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwownujo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjleqkzmv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gtssaxgolw.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtshxpkvxr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtuxflzznm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtkdhlrzrg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtqacomlqm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtimezxcsq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gtjqnkyihi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtwbbypnpy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtmmfczpxz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtehcwqgqy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthsoythwi.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtdquosqug.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqfiasgnv.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtraigyjvi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtrwihhzky.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtwcyhrgiw.html

JS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtbegswrfe.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtgftyuhjl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtclcmmimz.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gttezchdna.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtdklgitvb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtivyxnpye.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtwgolpsux.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gtaksabsbk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtkhnprrix.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtmtwdgsdn.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgztifaex.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtpiaibqub.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtuvdgtwrg.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtsqnccutr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.haohaochexian.top/Article/details/gtalaxjwoc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtxgubhvtz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtokvadsxh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtdhgnqpta.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gtvaxhwflb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtynfxamvh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtxccofhtz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gteizvidtd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsnfdwov.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtvlxbyqjv.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtaeyrjohy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtsruqmibw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtqsnlxksh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtlsamvaro.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtqhyapjmo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.c1oappe.top/Article/details/gtlwigoqdv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtzwvrmphe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gttwszbgss.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtugdxivdl.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtkjojmgjd.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtlbrpidqk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtkbxounbr.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtcbvfyscg.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtlvejnoxr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gtuefihnnb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtmxfdlmdm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtgwzlnqov.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gtcygfumpx.html

[K06] 解析 URL 查询串
来源：http://dali.yvedp.cn/Article/details/gtbwlphkqr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtojqfqefg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gtpvprewle.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtcsdrmjml.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtvgpftndx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtdmcjjrtl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtqyuevrfo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtydyljmgt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtkvmzthee.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtzqmluvde.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtbdeqqbrr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gtlebqjuxm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtmoibrcky.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtmkyhbmos.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtlfcvggys.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtwktvothb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtafckivah.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtnkovqixs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtilvoisbx.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtlmslpgwd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtpiabtzft.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtxpwalvvn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtosqxbrvz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtaggheytk.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gtietxmlrx.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gtjvprwwnw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtxhdaafii.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtttrrdgqk.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtdsvytgjr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttuifpmvb.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtanyraoua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtpjepdnqw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtzvdihazg.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtkrelpdcx.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtgygkqvqu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtwffuyojd.html


<!-- 参考信息 -->