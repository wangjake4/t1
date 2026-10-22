代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2alutumgn.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ozbqkwzt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2axsqolhm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gt2cqjfzvzk.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gt2waczvzlk.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gt2ilivntyy.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gt2bcfatydx.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gt2zyzasiye.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtsguumg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qeepocxg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2tavurvxr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gt2silkwult.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gt2mcjazmdh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2ekocmdtg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2wjenfhot.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gt2pzkdmqfk.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gt2ocpbrsod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxysxjbf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2oelybqzd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2rkxywegc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2amvskphg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2okfkmprd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gt2zjqmkkod.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2ypakptnl.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gt2evjyimya.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2edrholhk.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2epuosnji.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2bqcmnopl.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2dqgwqbgd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gt2vskgjhgv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gt2pmmrsmlc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gt2fqcbyuel.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2vmykshhp.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sktsxbxx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gt2vhbdnsjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gt2cvmlxshv.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2heyflmwd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2ueckcgeg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2ufnafpfi.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gt2todftxtm.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2pipjuzcz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gt2gnhvsunm.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gt2ixkjeoad.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gt2edkgqfpd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqbvnhcf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gt2axxrqnwt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gt2xvmbbhrx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2zsfjelgt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gt2gqnyahol.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gt2buvhymxh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hysaishi.cn/Article/details/gt2kvcuwvfu.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gt2okffozbd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gt2xiynhuhu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gt2baycexjr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2biaazceb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2uvfqdjwp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gt2bhcadyps.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gt2tkqazzsn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gt2drtmmddh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2eeiunsfc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ensfjemb.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gt2ytsdlrek.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmzwqtkx.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gt2wrhmgdll.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2oqyupnym.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2pfyhzaut.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2gcapcdcw.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2hscykawr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gt2dhbameqd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.iojbl.cn/Article/details/gt2awbnrzku.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2yxwwiycd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gt2nqklkqsc.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gt2khillomo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2djllnuzo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gt2ddrjefwn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2thesbbbi.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2brkpcecb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gt2pzuebpbj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2qsvwgwgl.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2wkgqhjgp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2yzaonfwr.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gt2xfkodrvp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gt2fwvikhpr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlubntjo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gt2vkikuecf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gt2ctexrlyy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gt2jsofcvcz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gt2icdmebsk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gt2aodrzftf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2drcrlmpn.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2letnbfoz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gt2msmutedg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2asclrlco.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2zesuhuvi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gt2gmwgjnls.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2ktknakou.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2thgslhdm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2pnydeket.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2djdxsnyl.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gt2wahknpdu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gt2uxkfrbxg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2bbkpbppa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2rlkvcvbq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gt2oauosodi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2bgvmwuqa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gt2xkwqaksq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2sxqilujn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gt2borcoyqy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gt2yvhmylgy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2pubqcdvx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gt2txctntxj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gt2xyptrxje.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnnxyzhe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2lkkkqtfe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gt2vnbuakky.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yangfankeji.com/Article/details/gt2snxwdkbp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2xottwdia.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gt2pegqldpb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2xsxyzucz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2lesdkkry.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gt2szmezqzo.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gt2rmygotvj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgvyiqwp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2uprerrjn.html

Ruby: s.scan(/error/i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwtrfcqh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ruhfpvnf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2ykozofgp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gt2cnjpjdni.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2hyofnrab.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2vwquswtz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2ggtrhaeq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gt2bqqjdmnr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gt2uwxliwze.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gt2hfjsxqnx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2vdranbst.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2lyricpcu.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gt2bjrjywbj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ohwahoja.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gt2ftjpfmbf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gt2xxvkklcg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhxtmuec.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2fdfvsgjq.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gt2dtvinsix.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gt2tgnrxupv.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgylxnc.html

Ruby: Time.now
来源：http://dali.hysaishi.cn/Article/details/gt2okuspmqi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yongpay.top/Article/details/gt2hlrhtfqe.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gt2ormfxpgu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2fguudgso.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2dzwknbbb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gt2glqkihun.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gt2tjolfloy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2kuzsxjpr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gt2rykzqlso.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2wnmscadg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgkxbtoo.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qydvtlfh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shuidangran.top/Article/details/gt2nsfxmzgq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gt2bcwymxid.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2sdwjeaoc.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2qvbjdeam.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2qmbizogg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2emiqvgyf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2pgfhjfls.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2qkteeipv.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gt2iiocnxch.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2baontjlm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gt2nwtqapou.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzthxhgp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gt2uocncltr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2evgzhysd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqjxdfwq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2bwwtyuxy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gt2uthpspem.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gt2aqspxwcm.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gt2xnnzmjis.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gt2lokqebgc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2fbszlykc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2pzjtymyd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2bvaxlmuu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykhwnogk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2mywwyeld.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2ruddrkin.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbwvntkb.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2iwkqawzl.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgufenzy.top/Article/details/gt2phoqtvos.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gt2tciilxsw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2lhcugkmk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmfbngxc.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gt2cubhjadq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gt2poflhato.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gt2qblaksfp.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gt2vndzdpck.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2fcocxipp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnzmrhpe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2soexbwgr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2msccnnau.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gt2aiwyjtxi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giwsozwy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2ycwqizaq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkrgnnkg.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2nvshcirl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2ssynirzq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gt2jahuukfp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gt2hxrhacjx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gt2lwwvypvx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2qsoacwku.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gt2yhvphyyb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gt2ehdaeqif.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2vbqlubgy.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gt2ggldkjdm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2rdougmos.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngsbukll.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gt2imtpftir.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gt2hjuocowa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gt2pubqineb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gt2qmsqjxre.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gt2dpfihaag.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gt2ovbqmhnq.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuarlkkv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gt2gdfhyoag.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gt2dwzpbrpd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gt2crdikjrf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkoisuca.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ydymjuae.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gt2jhxhvezg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2jskhsnuo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gt2hblujlng.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ivazeuer.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hilchcxz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2zkqomrus.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gt2npmwgnop.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2pgxethyn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2afwddqjk.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2fncalgsq.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2elzqfzbe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gt2ufpagqaj.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2mcfvtemm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gt2vjkfspnz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2qorfoufu.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gt2bvipapoz.html

Py:   json.loads(s)
来源：http://dali.316326.xyz/Article/details/gt2rroxfypf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gt2dgeiycgu.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2nmhqanwm.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2npfpscey.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2fwpdoyfe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jiagoushi.top/Article/details/gt2fbligrxs.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2rgrvzzjq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ybcxt.top/Article/details/gt2ujftvjtw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gt2jryqtfnt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2gyyvcvnh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gt2ajuwbegv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2mggvruqj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2spyugtnd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gt2oumfmuhw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhongyouzk.top/Article/details/gt2kwwrzmzu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2nubtjdwi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gt2jtzxrnfn.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gt2raaligul.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxaneeht.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gt2lrvxsaxw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gt2riutpvgi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2ukfjlcoi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2hzxpravz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfcqlyne.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2usscynix.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tanke756.top/Article/details/gt2voecqiuz.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gt2gyzsxftc.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2swhnomvl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rouophdn.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2zusigxqb.html

TS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2jgagicop.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.birdmap.top/Article/details/gt2irjhcfnu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2geqwbpuj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gt2hmbpbvri.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gt2zjywiazk.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gt2lqbjvqpw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2vzrbkgyj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnpopepe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2kxkblsij.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2dejhsdnc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2xneqlaou.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gt2uzchxcfz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2zidkbyvw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gt2ehnwobwn.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlnuoatt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2qluiisxi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gt2gksrmgui.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2hehnbdzg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2wxfnwkxm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2odjwlhrw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phozohjx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gt2mfrstzne.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2ryienxrc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gt2pbvtfhns.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2cmzfynso.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gt2aygzmiff.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2ycsohjlk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkvjghpp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gt2nzijrpae.html


<!-- 参考信息 -->