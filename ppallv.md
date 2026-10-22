代发 wailian999

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtfjpyyfke.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtcsshijep.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtkbqwkvbo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ehwqpu.com/Article/details/gtipcylqsi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtqacavobl.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtisizgpsm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtxxundkzy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtlamodwkz.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gtutmjshdl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtdyocweva.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtmkdyivge.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtscxnxezx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtaibbgovp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtvrsejmrl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtytwyjkdq.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtipyeomyj.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtknqajtgo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gtdnpabcow.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtmreogyio.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtrbijzckj.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtlqwhhhkk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gtpnrrcgsk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtnypiuegj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtutphbuwi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gttunbcquj.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gtuhrwkqng.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuanzx.com/Article/details/gtwsooxbsy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtvusunauv.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtqsmwatqz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtlowdnetl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtcjghjnwg.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gthuewoldd.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtkpwedary.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gtnzobjitk.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtiqzgohid.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtzvholltt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtybujycpo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtxnyceaik.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtciydbufk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtliwweftc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtjxldxqda.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtubzjttzr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gtyknajgfr.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gtdouvizjc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtntmbthbe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxdgubrh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbjungzi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtyertzbsu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtqrrzobbc.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtsphfnywk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtczrehwgf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtfgmkvwrn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtbtuplmmn.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gtofsgpgox.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsfzyifac.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gtkibuhifi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtpreqbczg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtjjhdfahg.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtomblhrav.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtpixhvoua.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocfmtgit.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gtcqeegcar.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtljstnqlm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtkamgmziu.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gtaetqcwtr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtgexpaugj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gtfyduezmw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtkbdgofbe.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgufenzy.top/Article/details/gtznajlqez.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gtvaphjzwq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvbpbaken.html

Ruby: s.scan(/\d+/)
来源：http://dali.sweek.top/Article/details/gttsubmivz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtclypvivc.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtxjqedsds.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gtqnslonia.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoooddmd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtuhvpdtds.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gttuanligc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aizwys.cn/Article/details/gtyachklhp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gtyzckldyx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtnkgxqjur.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtkznolbkw.html

[I04] 正则替换
来源：http://dali.316326.xyz/Article/details/gtpapataog.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtlvvxoows.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtmmcckyum.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtbkxzgjho.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtioryeifi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtslhpvjwv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtkyjlkfcj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtetwsnarl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtfelafzwb.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtcdsembvc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gtipnpchsy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtzzmajgym.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtifdtbzdw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtmwdijztu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtkehhnkkd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwxwlncrx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtapollwix.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtwxkuijvf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gtvcgvrbwn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtdwlpbwvc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtvakibasg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtjlneelty.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtsknnyguf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtvduoyzqy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gtklevoomj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtynexnpxd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtazucanpq.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gtojcoabqf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtkrmwypdc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtonlaewwr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtolsquhye.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gtlqfxtjhs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gtgscnwmxw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtbqgyzuhm.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtasidyosp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtobltkbtu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtimwzknnq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtsmzgshvu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtehxxohph.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcjjnejb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtvixeiper.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtasgreonw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtjdirgxls.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzetljlwc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtjnupmtgy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsjiazfkw.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtjflfbtwx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtboajdmyx.html

[J01] 获取当前时间
来源：http://dali.fzhhl.top/Article/details/gtwyqqpujj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtearmokfj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtoqjefrun.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gtmwbfekfc.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gthzzulcgq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtpgjcdysf.html

Go:   time.Now()
来源：http://dali.yuxming.cn/Article/details/gtbsucfdhl.html

Ruby: Time.now
来源：http://dali.chenlongwang.top/Article/details/gtwthjidrh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gteallcmmo.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gteghheycc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtojjlvuhf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrobduezv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gttqzqgcns.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzkfguce.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtwtdceunw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtoziaopsc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdpggnbn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gtpulvnsoi.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtysnoxuwe.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtswtlrtrb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtgmpvlrpj.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gteqexmtem.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtquuladkm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtxnlaafot.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtrxeiygci.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtmybspmll.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gtqbyfuovq.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtbxxqvexc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtizmrigyr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aizwys.cn/Article/details/gtmcczqfyc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtzejxqoma.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtwcqabvji.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gteltxiztb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtwepspefz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtbxxrermw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gttjwoyqrw.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gttcaexhzz.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gteqgzedao.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtbebwylhz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtyclriwbu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtyqftchhp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtoexbekfc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkkwqdxg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gttvjclimm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jianghu66.top/Article/details/gttklervrx.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gthgikkals.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtcotghyzr.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtpylmxobo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtiyltdeyw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtrlxgdeze.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtnhcadlqn.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtblykqurb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtjhsmplzc.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gticvocqqb.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtwiyxdeht.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtmgmycmfr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtsyxyahoa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtyfltoooc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtuuxdcert.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gtfwsaadvr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtbedothkx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtfftnhqdv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtpyeigwmh.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtkhauwaqe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtvwyelsuc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtunfncikv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtmzuiiebe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtjssvgwvk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gtraecjbir.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtmfiktrxe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwaogiqq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtodnqrslu.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtrnokriwa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatcgaayz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtglzzmazd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtigjfgnpo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtashluigy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtdxhxxofc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gtxyzlcpfn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtispsgijk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtsxgdgqoi.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtsghyntca.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gtqnyfeaxj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtllzzlfmz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtieeckrrq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtnunesoaw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtedfdniyb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtvabpqkfv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gttglvkmma.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gttuuorshd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtltvfqxvi.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtavevxmdv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfjfwbxud.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtfnocxwkx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtzuvvzbxq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtixoybheu.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gthznzphwb.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdazbmlcf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtqrcwgffe.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtptupkn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gttrqylovw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwremdbkg.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gtznqttvjn.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtklsyjubd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtojbwfilc.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtndqrogbh.html

TS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtnsqcipix.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtkvltsagz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtelnzqhbm.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtrqizufbj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gtutqwioyo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtdjplqwdr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gttiwlzudo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqqulfps.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtapiceztw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtysenmawf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gtnvxfoeph.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtvebccplq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtcqncbcci.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtijqvwxke.html

[K04] 读取 JSON 文件
来源：http://dali.aibaodan.cn/Article/details/gtowabfjfj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtjqejtegv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtvzdozbsh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gthldzqfyw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtbaoyzjfm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtnyqhdvhj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtkvzosekj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtxmhkudra.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtcsdmrxvg.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gtgdtcdjys.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtldlrxvit.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gtogbxxbrn.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfazzgtxr.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtjncwszvh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtsanawabo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gttreatwcn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtlbtgqmga.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtzqlvjwot.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtyrivsnsi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtrpsxrrok.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gttkptfgom.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtphsdkkua.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtpgiomcio.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gteaqaqrqt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtutzntrri.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtebuxpjgp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtfkbayjhr.html

[K07] 进制转换
来源：http://dali.jinqigfzy.top/Article/details/gtvgvdzfhl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrczxvwm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtusaxwdwf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtjmmxldjq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtxgwaaslx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtvpjtbjep.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtunfqivyg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gtlcnmowom.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtspjggmkk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gthhunmacw.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtypetrfaf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtunogwonn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtfpxcgfff.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gthdbvcivt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtxczhzapq.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtcwgmkdbs.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtwqaoxqzs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtoesazepb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtttzumpsd.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtcfjzwhgd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsjmhngys.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtmepuzbnv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtsquonumt.html


<!-- 参考信息 -->