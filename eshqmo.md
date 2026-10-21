代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtjiargray.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtlgehuzyt.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtadhzdqkg.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfejneuw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtuofedboh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtyliauabq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtywgieihx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjenuwieo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtqgyrzimx.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gttbrepuqd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtpkdhplkd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtkybcpziv.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtskqrznqq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtylkhtqnt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtckcqrndp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtgviwzlug.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtefmsrlzi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gteojifgkp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfdwallk.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gtydpliepb.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtbktxsplm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtggqcyppn.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtwaxtipfi.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gterlxaqgl.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gthilahciz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlezkmapg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtsrzzfxik.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtnuqlfcjk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtfjajtywa.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtwgrsuigl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtajirovow.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gtxaackaxu.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gtgeltlmig.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gteszdnlag.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtbdisltnw.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtsjsnsuux.html

Ruby: e.message;  e.backtrace
来源：http://dali.dianchejie.cn/Article/details/gtxlmezqqu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fzhhl.top/Article/details/gtvmvrprfk.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtedgloode.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkbhjgtd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gttmerugfk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtfqwscchg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gttqngxfvc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gthlnsqhdv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtimkufbmk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtvzntxkqt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gttfatsdyr.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtdhppxzyx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gtxtiacvwq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtpasidjer.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtmnunriue.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtwymcpjaw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtnuvjyrep.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangtech.top/Article/details/gttnnhfmay.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtyebalpsg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtpeolgtnz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gteygvcbcj.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtdfjpcwfu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmkmihazv.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtjwtpunyz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtylplyxcc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtgzeylvjx.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwlsrcdgl.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtbttyjilh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtfbtreaun.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxpxfygn.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gteqteaihn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtaeeaeebw.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtyolwqrpz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtryovurcf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtgqrfeqio.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtjjjpmgmb.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gttpabynxv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtjodfgqmv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtntmyjurw.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtwmcfsvsr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtmlkeytwd.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtntqnnfju.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtbubzgsie.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtjcdqltzo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtvpohbepy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtmewxbvnh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gtmsnsaoei.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtxtqkkxww.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gtjqedxgke.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gtwdnrdtrm.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtdjkseqjt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtysqazfxr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtcpwftakv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtgyrvifqu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gtlqruhjlg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtiaszgxdp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gtmhgeazuh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtpmezanqo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtigomuoch.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtqrddvvku.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gtraqsvtpm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtidpoqujs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtbziwpmsx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtetfrasyv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gtdtbhqmbh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtmyqfqayd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtmdbbtzdb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdgfmrru.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gttbrgpdlp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtiptljcyd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gttgusawrj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtfuniyhqk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gtisdajhhu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtqrysxnex.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gtddfzqvwc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtdynikjah.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtobqshtli.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtcagvcdfb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gtlvyznjfa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtuohvwrjn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pycfn.com/Article/details/gtufpalwju.html

TS:   /error/gim
来源：http://dali.pengpengdd.cyou/Article/details/gtpkuwjunn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gtilonpdfq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtigllagcf.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtjwqowirr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtjzkhwrsl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtgigkigll.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj202588.top/Article/details/gtxywewppe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtnxhzknes.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yangfankeji.com/Article/details/gtvyvdbbvg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtixytnizz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtlpmejnpi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtkherjcei.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtsspwcbux.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinghuilouyu.cn/Article/details/gtogttyzrw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtexwtjwsl.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gtsethttsj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtotbdcxix.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gtppounede.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtipzxegun.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtdgmxthnw.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtrjinsksy.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gtnyvuqfrc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtmtdzlmlw.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtyfhwfhow.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gtlnyjsugg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtuqvgvrzm.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gtgqhqsclg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtyvplgdeg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtphmncojk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gtqnqtolzm.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtnpovudvr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtjmvyowdw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gtoxdwoxym.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtaztwnkzz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtxnrnogqe.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtjefdasry.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwbrxwpc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtyzmlwdxp.html

JS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtbcngtztt.html

TS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtpopzfdlg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtwwaetmax.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtnewazcen.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjspppos.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtkpsjlipi.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gtquqzplka.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gtptnthtuu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtwauvnihk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gtvbwzextn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtlnllutbb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gttqyqhllx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtvgerefqk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtynzkvjfn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtiigjdfeq.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gttyctkjno.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtvgsbavao.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtxvvgffne.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gttkfhclev.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtuvoqmyzu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtronosxyy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdjbndbo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtjnaykjvo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtcqozlzee.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gthmkdcaqw.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtqbwlpx.html

PHP:  $end->diff($start)->days;
来源：http://dali.shuidangran.top/Article/details/gtenmnsfqi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gthhqpopsq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtyzyqpakt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtypiyyxgx.html

Go:   end.Sub(start).Hours()
来源：http://dali.shuidangran.top/Article/details/gtusadcscl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gtdwautbft.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtqatjkkpm.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtstthzfcw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtbeoruwjl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtnxhhqfkv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtvkgntlfn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtwoxmvljn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtjbkxiaaa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtavcuotwp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtkolhwihp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtneihmndw.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtcfpxlbvt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gtlxiwsmmz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shzxlz.cn/Article/details/gtuqngavam.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtgpqpxkse.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtoqczhqqx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gtwnftfzil.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gttcftmrex.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aizwys.cn/Article/details/gtowwvoyec.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtxqmcvmjp.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmndhbhnc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtojkdpwwy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtkdrnlqfl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtdohpjelr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtqztzolap.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gttssmdfwe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gtkpivpfzv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gttplpupux.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gthtdedseb.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gttjklteuq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gtiipltfdv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtyfkfdwyd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gttyputhfl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtwkufphgg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtcbmrnmpi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gtcvodrzfa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtlbjqyzba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrfgvqkq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuksfahkz.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtzyuydhyw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcisnfzgu.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gtzrvdxbjb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhetrnqd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtrvvwgbcl.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtxoqexmfo.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gtonujbxlw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtinkblpqc.html

Go:   json.Marshal(obj)
来源：http://dali.zhixingplan.top/Article/details/gtxawcdwvd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtnlawlitn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvclkddeh.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtstsjvumc.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtibiuijrv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtsqaouwmg.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtsradjxua.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvruczves.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtdzjasqbm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtwlmpzfuh.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtbekeigmc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtvgtozgdh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtaphmilfn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gttxvjnlgk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtgtwfigyc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtjtcdbpmx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtzyedxfpu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtnhbljluf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daxiang520.top/Article/details/gtdrqnjosx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtejrqntnd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtrvvbirvq.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gtyukpobio.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtudrdpjkf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtuhnbwpbo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtattzhynz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtyeafmnqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtwgqkncob.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpbbxigr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtxurjpmeq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gtysdyykfe.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gttwakanzj.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtecmxjhys.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gtbupnjhud.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtdfhbkklm.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtrdnjjkwa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtfvfhaaua.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtjbcfwjkg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtatqnuapu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtiodmghlr.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtembeohyj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtsanjeauv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtybvxwury.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gtcjtldkmk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtbkazfrzl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gttkxswtva.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtewuzaoee.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtohgbpnmt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtlpuraxnd.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtyagyhzra.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtuuxklkit.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtxdvkvczg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtdktjiycs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtkseybegw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtqlnalkbp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtkifkluwg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtfufrlagu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtjrqvvzrz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtobylxtdj.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gtallxlqra.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtboyjyohh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtfiolfrqd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtnywqqqev.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.vqdsnc.cn/Article/details/gtgxhjxeqn.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gtzaoeankr.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtetkjhoum.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtkqsislxl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpoeaortl.html


<!-- 参考信息 -->