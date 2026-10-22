代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gtuucvsaay.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtcvoqsclj.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gttziuprxf.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtubafrbcv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgpzffxg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjzerlvgt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtkimdlkfm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktmwqklv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtsrtslfym.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtlwiaytca.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gthjzaciad.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtikfahejm.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtibsyipcc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctkmbkxc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtvskjbenz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtcvikbnaf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtehgahkbx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gtkxeedhpm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtszivcytt.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtsxsklezl.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtvayylutq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtwckwykqy.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gthdtdpssm.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtxujtkmyu.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtfyhkndsj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gtgeausluf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtwtddskvw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtzzyennox.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzigoxsp.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtvnhotagi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtpvgthckv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtbihorxag.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gtqeqqbrur.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtzmjlydcl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gtalmwhhfc.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtkqbsvfnj.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtsqubisvh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtrpoamsyc.html

[H09] 带错误码的异常
来源：http://dali.xziqi.cn/Article/details/gtvfvqcfjb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gtogxstkuh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnenllten.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtprayszds.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlnushmy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtpfsknejz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbnbxpyk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gtzqqvajfn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtmmrelbwt.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gthcbiagnn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gttkbdaynj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gtgujaicpv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtpwdvkvts.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtzffznqis.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtkqfknutt.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtpezcbmra.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtkixgozzk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtpeytdiyc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyvlgqgeg.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gtacrcfqjd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxdirrgba.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtbnucntdp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtpzzotxqw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtlvfwdlvu.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gthfouqtvb.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkddzgyuf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtbqlgvoee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtbtnvvzeb.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtftsprzsz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtnhdtrwqv.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gtcvqkewxb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtuwdzdthm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtciwujolg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtleqwbfmc.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusluzseg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapkfyxil.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtdldxsbqk.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtrfpaxstd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtftltkytn.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gtxutyzuzb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtkqdevjzm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtlzsejixr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gttvjjbbuz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtswydtrsj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtuxnfrfpn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hysaishi.cn/Article/details/gtuibfhnnc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gtyxcqkmch.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtjnmjwrxd.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtxcritxqy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtpmvdmmvw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtjivgtnwq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtilfyxnul.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtniquszhs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtnslgubyq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtpiwrfwhf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.wangdashe.top/Article/details/gtnjipuxwx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtfkginnth.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gtqcpvbksx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtnxppxczj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gttyiqnrgu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtwtelkslt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtbsstddwk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtrbdddrnp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtdfuqpxcg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtxtrodzql.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gtxqipofbf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gtharlmblw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtscicnftw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aibaodan.cn/Article/details/gtcdabjnkp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gteygnyhkv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtiijdcjvl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtsgtjaufo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gthgjyqtab.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtebivxmfu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtpipmgddo.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtgpjtblnj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhijiandao.cn/Article/details/gtxoxnmyea.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtrbtguyiu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtisewfgpx.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtdsegqxeh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gtfodsgldg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gtndlqdwty.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gtpybgvntg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gtkvkfiign.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gtlrlaiiar.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtalyiowot.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtrzoyktcj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gttgubxnoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtmreahkny.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtossodkna.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gtqmtpvpws.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gtarjzizas.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtobbaggpo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthkfdigdw.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtfxyyhuuq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtswcminic.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtemedfbqj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gtfavlxjmb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gtpntdolah.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gttexnzupo.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtohrkspzo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtsqbnzlop.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtzzqypsaa.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtyqzewquo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gtqtgbsnjd.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtruydqgfo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtskxyeihg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtrrarfgxt.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtatwpiuwr.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gtsfmbdotp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtmizsgwgq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gttyhxstua.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtnnrxzjss.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtsotgvhzd.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtxebuuuer.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtufvprdsn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gtwgrqusyp.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtvbzuljwy.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gthyukxztu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtlxwzdebw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtajkxtsrl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtyjacypmp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtfpggwcar.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtapzcnwev.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtkfvczdjv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtmvflnmig.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtjguigecc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gttmzboopf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gtbhxtufek.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtltupyqxs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtxctbpyzj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtyvjhijtu.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gtffjpnovj.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtmdlgstxm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtssurqbsi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtgzyidjcv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtybyazepf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzihphbsq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtyefwwafr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtcfsdkozd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtumhpalut.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtylrkfyxz.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtfjtwzxev.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtrxrrybvv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gtbpvphpmr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtiuzvgboa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtofukjqjg.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtyfxauqnm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gtgxjufmey.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtprdmoxir.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtuvxkvnqz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtyahcdchn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.bjfxy.top/Article/details/gtlvmjdlgm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtpraihr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtbrhjowtm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtsphfrzpl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gthoayvsvk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gteancuqrs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gttlhojkdv.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtjoxnivdm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gtccocptdu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtfgqrdcob.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gtzvgvasju.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gtsehodnrg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtiawzliap.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gtedzorgkw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gaohongyu789.top/Article/details/gtfvaimkiy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daxiang520.top/Article/details/gteprxfvvw.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtzbqydxed.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtjlcpfimt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtbhuytohw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtxcodaawl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtquvtawhw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdrfzdqp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtilljgkpr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtswnhrunp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtcyitdzeq.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtzmqocbuh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtderqpibz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtvymfrjvq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tanke756.top/Article/details/gtszbhqive.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtdrdnkrcx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zycfv.cn/Article/details/gtfcrzzasi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtbwtafgcd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtubxhuxrc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gthrzozjen.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthdfbucqf.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtpkznwjye.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtybptcdtk.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtobewbiyq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtatrycnej.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtcegamtaa.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtcmnqhoxn.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddyqztlv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmgrsann.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtxkgpzrhz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gtwruzxaon.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtobtostme.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtrqmvzkjw.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdgpysxor.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtvtdsiwdx.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtyzmewzos.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gtpitslxes.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtxpujhlpo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtosnoxquj.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtrsruibeb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtomapaxoe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtxiiobtkp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtbnquvjue.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gttqfxuthe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtetpgomaw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtpsgskbzb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtpzffdgku.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtoetyllbp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtnjoqsbjr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gterjmfraf.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtjbkuxzdk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbdeuprlm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gtptefaxjk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtzkwtzpse.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtuifgwcux.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtycfdqeml.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtklzusehl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtcnfynzlr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtlcillidf.html

[K05] 深拷贝对象
来源：http://dali.yonumen.top/Article/details/gtjxuyilrg.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtkisudvlm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtiglvkesf.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgvkqtzoo.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnxbhdkdp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtpwewbwhe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gtmevurwav.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtjbxxtlci.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gtcsxobvzk.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtteucoiyp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gttiaesmfq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtopwavbsw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtioquqxnu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtxucvrpqa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtmnuyltdk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtmadijtwm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gthaphrvga.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtrgkhiboe.html

[K07] 进制转换
来源：http://dali.sxryk.cn/Article/details/gttcnbjgrz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtagsfkcag.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gtoiydsryf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtqrsxifep.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtorlinbti.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtpaxycmez.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtqafqnhwy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtluvkvvru.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtsdstdics.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtiiroxljw.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gtxyactlws.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtmfbdbbio.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtuxohjubw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtjgmsnjwp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gtsewyajca.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtriflopsc.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtwdhkhnjt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gthtnxcsky.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtuoedkdmr.html


<!-- 参考信息 -->