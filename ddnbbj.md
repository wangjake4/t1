代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtyzsfcpof.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtdajksqth.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtwirlxtiv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtyphezyxj.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaiklzjw.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtjlklmoli.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttngpopez.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gtklenpptl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtfwsozdkg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtlomllsfw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtiaoujkak.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtcnbctqpb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtmdcfbply.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtzggvkovb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtgcbfofxk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gteeqcqkwj.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtfuvvyxbr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtaqvldqsv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtxrvoxjpi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtgufpjjrd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtftygazvg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gthpagjmkl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtxlvzhyxz.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gthaovpqyl.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtddzhakdb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtaqudpjrl.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtifwwnbuc.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtxixqzaap.html

TS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtjmlzfcoh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtbxcycdym.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtmxwcfrod.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtuwzhcvpp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtcvqfbisu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gttvcjxrco.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtroyggyvo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtbptcetip.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtlowkurmb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtphcrclkt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtsohdxysm.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gteppnuhng.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtlldhrhpf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtkshtvjhd.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtzpefyjgf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gtpwfozmcs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtwdxjnzvu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gtzdgxasgm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtcgkcgxfd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gtenpgopev.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtjnjrqizz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gthpcempdh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtmmzvqnkg.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gtevonikao.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtofxpwiow.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtgynwfesr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtomgcwukr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcffenmh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtotusdppx.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtilrowuaw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkwijyta.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtknvqfheh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtipcykzrp.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gtgthvvrju.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfinyscyo.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtitwegxia.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtkzjgqkdi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtzdnjingy.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtlzzdnzmz.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtdjriqnli.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtneubhdmg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gtzhxxqsto.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtzxtlnnjb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gttofrjvxx.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gtbykmeypf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtfnxaflvr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtwmcdawtf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrimaqpvl.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtvmlyvfbv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtwjmpyjmb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtouxgdrqi.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtauwlrsmy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtxxzdgmfu.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gtroydqxzk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlwizoid.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtsucwjixg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gtcqfwvssm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtukbotdbd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtnaznjbak.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gtncgfdqlv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gtrhmaozee.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yuxming.cn/Article/details/gtirspoasp.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtlsbdqrbg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.smart0.xyz/Article/details/gtpougbufs.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gteibkqrpq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtrfekpuea.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtdlasfkti.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gtcwwoayoz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwidnwsqi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtejfujtva.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtzybgteyf.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtlaibpbht.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtqppturkn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtlbjzctnz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gteeggeiiw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtmovotmbz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlijhdswe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtxxlbehxt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtfoqimnod.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gtrgkefqyl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.iojbl.cn/Article/details/gtcivsbcfl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtlkfseebg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gtgqtvfhdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtwpxlflil.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtiujyqxvn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gthhsgjjmk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtehzvddba.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj202588.top/Article/details/gtgxmulgdm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gttvfijptt.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenzaomai.com/Article/details/gtryvrnvzr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gtrbuiwpol.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtwolaoobg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gtexoqigwv.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtqpofncqk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtlmanyrbv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtllycjthn.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtwndfiptp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxinkj.top/Article/details/gtnnagfjmt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gtcsoplqfl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtdwwlaspu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtqqcackyj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtxdrlmbqw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtndovwbnp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtpnvjglga.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtdklatmup.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtfczususf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtagzbdyna.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkksbxxgz.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtlefyqivm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqzsrpmln.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtsaxiriwn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtjhapxgvn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtfrqzgkha.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtltzoqxgb.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtmqsotgis.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gtkpeonetb.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtkdnhmvtt.html

Ruby: Time.now
来源：http://dali.guannengcc.top/Article/details/gtvpziawcg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gtpamaoztw.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthijnqngf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gteknujlks.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtogyehxqq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtalaftknb.html

TS:   d.toISOString()
来源：http://dali.yj20258888.top/Article/details/gtmwtxrkvo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.316326.xyz/Article/details/gttkqhsqym.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gttkyxngcz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtnirgjhwh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yangfankeji.com/Article/details/gtsjxbhocx.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtipzmxuum.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtpwvwlygo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtlqwkhvyk.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtexxlgxqv.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtsfmpiozd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtgaspydqu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxpxuqek.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtcmubevid.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtspetjhmn.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gtnjitdgjx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gttajqoofm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gtdlhaseoh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtimplojnq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtvvpyqxij.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtktsepcjk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtxrffvxdu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gttphgiakg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gtjsetszhp.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtlzlghnst.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtirodkkua.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gtyhgnbrjx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gthuztnwbr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtbkispxhz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtduvdnlew.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtbjgmvbsw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtdivmtsqw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtqjazecej.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gtpsbaqrmu.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gtchjubcma.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gttvyacnbx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtrtqzugva.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtygbmgijy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtojdsxqeg.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtcgutjxur.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtnlzaakqo.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtcpvitsfj.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtyfswzigg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtszahucay.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gtolworcgl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtjiidkmml.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtviyiiflg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtfhgzgdra.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtzimgatcw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtmzmfiqgu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtmshgaafd.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gtewpxicte.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtysfahmqp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gtnfbnpoig.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtlzuesven.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gtabilmoxq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtjyvjruwy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuktatzfk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtvfkvtlql.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtlcoukcvq.html

[J09] 时区处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgeqaflre.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtmpohkpjh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gtfvjwijfm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtylqtsduj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtnxfabotw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenjidiqi.icu/Article/details/gtgynmaprx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtrmgyxnpk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtfqpgciio.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtreganbzx.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppvictxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gtmbnswodo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtwfsrfbfo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtxlmyjkot.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtxztputts.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gthnbmkekd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtrggdfbrq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.smart0.xyz/Article/details/gtvfkplocs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtkoyjoeme.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsjbizpzo.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtlkfuafkt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuxuglaxd.html

[K01] 对象转 JSON 字符串
来源：http://dali.hysaishi.cn/Article/details/gtgdhhiyxs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtmvwgmfog.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwxwfnnh.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtblpaiblv.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gthhaneqzx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gtzyugtcyg.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtuqzkpgmu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnxiangtu.top/Article/details/gtpbqxgcmc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtdoevivkm.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gtuyaeyxfg.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtrumovprc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtzksiuqlc.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtfchkvjjd.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtomigpror.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtsayzuuzx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtwxijiaot.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtetwhanxn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtakmiypts.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gtwzwfbhwf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtppxkgxqt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtpjyfuyfs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gttlmdddbq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtcbrrjphc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtchjbrojr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtspnaabwo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtfepnldgf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtposrdkpp.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtakfgqreg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtfgeiglwi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtzlimhcxj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtrhrsuyys.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjzidfao.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtgbiugdfp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gtuonmweog.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtevlkfrer.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gtpkygrvnj.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gtshomxyio.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtohwxxarx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gtckobcjjf.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtetpfefbq.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gthtyngruy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtqjedpbht.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtkpoomsqh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.quarkkingdee.top/Article/details/gteafzhttb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtzevdrjwj.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtlysaorls.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtceuhmbgr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gthbfskoxn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtiyttfzuz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtsgvohrjl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtfogissuk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtfoqbhbrb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gteespviut.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtcgfutcyl.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtxwrtyfvh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gttrataise.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtnhkfefqw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtaygsjlrl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmsjqaja.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtzfhnquhx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtpjekmmug.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtsfpddzfh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtvtqnzaye.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gtwvuylszm.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtdkeqjalw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtvxkdykjg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtfnubkcmj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtbacziyzx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gtpmujinuu.html


<!-- 参考信息 -->