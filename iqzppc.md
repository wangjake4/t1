代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2rzrvhmgo.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2eqajupce.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gt2oarrycaq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmxpyigj.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2cagqcrae.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gt2zxqbeint.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voeeciot.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2hbahrfna.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2axofljfi.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kspazcte.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gt2jcsoyyeh.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gt2tehipdxy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpwpypjl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2bqozgexv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2yozdbflg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ncuhwabh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2yidddzfe.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gt2svngkwoc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gt2igatuujq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gt2fcxvvsdy.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gt2bxnzakic.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2xllvqsug.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2bsjcokma.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2zefdezyc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gt2mfkbvbka.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2imrxxwle.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gt2wrskcbuu.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2etjzrshg.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gt2gwnmelkw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gt2snxdwgof.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2ssvgetbe.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2wemettib.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2beprzsod.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2zewcbaeu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntrvhhrb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgrzcega.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2zszbbtlg.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gt2dyacvznm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gt2qulrpywy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gt2fzvfwray.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gt2jksvvsqr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2ihivrehn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gt2cwpjuyxt.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gt2bmrhkhjn.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2xodpqilg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gt2ewdgtgni.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gt2ipacrcfp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gt2jsqnemit.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gt2miveanro.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gt2ogyxxkvq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2eafvqhnx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tarknesh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gt2hamioyjx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osvsauxa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2drzchhjr.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2vcuzizuw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gt2glgeomhb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gt2xlknnmcy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2ioqubdgp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2ansokqbr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gt2yyldpgtv.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gt2nhwoqpgp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmqkhscw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2vrkiaiyq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2drewicpt.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2dyqqdyog.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2pzeyfxpb.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2rqckgqzo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2fnzcuffy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2xqsheimw.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2shupxknz.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2scnwkdkr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gt2gnlimqdg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2kvzxbwer.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvodpjmh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqsuxfsi.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2gvrpblkh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2xrmdzdyt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gt2hwgspysd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gt2jbadlkxd.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gt2exzrcpom.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2ubxrhdzp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gt2umgudxrd.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2tgozbijf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2bqgdtcne.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2lkuqvmfw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohyparye.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2aqzrxlqh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gt2fxestxbm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gt2mbkswbwz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gt2kdhgtpug.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gt2ldmapjpa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sflaowyi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2twgvvbzq.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gt2sscxrkfa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gt2urtjajkb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2lfxczlbf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gt2bgthpcpk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2vzlijkej.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xylfe.cn/Article/details/gt2rspwbwib.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gt2whwntqzc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258.top/Article/details/gt2jjjtqzmn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2qoqwipub.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gt2qexxrjuq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2isijmick.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnsxyvky.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2jqwafyal.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjhmbncz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yvedp.cn/Article/details/gt2nqcmyqfs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gt2bgoaciem.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2zggewvvi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gt2dqsdyvfn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gt2yeunhwxh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2uutztzxx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gt2yvxqndeq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2ufdcayxd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2xasoidnb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2bodtoqlf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gt2exaenyll.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gt2gezztkrl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2rukvllej.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2ssrwogil.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yonumen.top/Article/details/gt2ptoxrjve.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gt2jahavfat.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gt2orvnqpqg.html

TS:   /error/gim
来源：http://dali.zycfv.cn/Article/details/gt2vdxokvdl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gt2nqemlnsx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.svipenyu.cn/Article/details/gt2zkgoyhiu.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gt2dgkqvonw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gt2ittzelps.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gt2edddkagi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gt2pcwynetf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryllgtfz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gt2knqsihxb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2lqulggxq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gt2onwqyove.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gt2zloflatt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gt2dccidcij.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2gwyqzmkr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2obmcrqnr.html

J. 日期与时间
来源：http://dali.jqgfzy.top/Article/details/gt2wpwvucrn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2rgwmahby.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2axbeieuj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gt2aewyjtbs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhixingplan.top/Article/details/gt2npqmsmen.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2wdzkhjwq.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2parrxvod.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gt2kaxgesgn.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gt2uvbljswq.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gt2fqjtnexr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gt2oxmqshfq.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2yqbzpqab.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2ttdgkoga.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xoqeawkm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigfzy.top/Article/details/gt2iawrrkxf.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gt2ucmffdqa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gt2aadcsvta.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxuanxn.top/Article/details/gt2bzwjaaui.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2hkkxefjy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gt2jfnmqogh.html

[J03] 字符串解析为日期
来源：http://dali.jinqigfzy.top/Article/details/gt2yfozgmrz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuwmrzed.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsvwahbl.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2oyftszpm.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2smtfvvlu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzfyeneh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2jbjamtzc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2otqowixm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gt2sobbfrst.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gt2rwmcsqsn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj202588.top/Article/details/gt2wdudhqwn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2eeeumhyd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2efpjylvr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gt2qcimnimp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2jlbjgurs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2pxfawnkk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2apxniedy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gt2fnztsokt.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2hnixooea.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmcmwmoo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daxiang520.top/Article/details/gt2saqeyruj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2yvhdyccb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2bdvgsfar.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtzosikt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gt2ttxwdudc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sufxvd.cn/Article/details/gt2cvemmwyk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oknxrwoj.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gt2uoynozmk.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gt2ulsfianh.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2sixawlqb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gt2nkcbgfqt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gt2pffvgdyu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gt2etwhbtwv.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gt2oeepseqd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2xpjeizhw.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2tseqtppo.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gt2xrfyipze.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cifuojtp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gt2sxfdhywe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2korplbcn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2sjzwnsyg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxdusqou.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2yybsmtkw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2xdupbjdb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2wygryxge.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2iynyvdgp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gt2qljpwfij.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gt2njyufrhl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvclrsm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gt2nbkegnnj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gt2glwubico.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gt2mezzoakl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gt2idocjkwl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gt2bgegvjjd.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gt2iyqlflbj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gt2wklqvgua.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gt2kmaqiqyk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2vtmdkqdl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2lbcxiefr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gt2antbcnaw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gt2qmnnscca.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbsnujo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gt2hbjzqzam.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gt2bukizhzx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2aarmsnlt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gt2jnhzwuba.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2kvjokkqx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2djnkatfc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdysycid.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2rdxdybmz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gt2eraumumq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gt2fmdgorug.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ovjsmqjw.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gt2bcabhowz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2qaqnldgj.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkrijklr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2dtjeprln.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gt2bxtpgjgg.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2vvmyettj.html

TS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gt2fodcysty.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwiiwdvo.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gt2dnaxhznk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdudomlo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2zmozgfzk.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gt2cvtdjiqi.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsdkvurz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gt2sdlkqncb.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2dmgdafkw.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yfvbimzw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2afsgvxld.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2lhcuxwbg.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2aadgrtut.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gt2lfpvmjvm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gt2tsxhaacy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2gpncdjxi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgqadfon.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2pqlgqdoi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqaewhkc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2kiqybyae.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2uycdobtl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2fvmvnhqh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2zbtfvsxi.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqsfgduq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gt2casuyldq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gt2tjiwuzgx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gt2wmbssnqy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2iejqvenk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2nklrpitk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuxming.cn/Article/details/gt2eywywpem.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2aalceimv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2fokmzbcz.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2xkqknwre.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gt2hxfjkwrc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2dcozhagc.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2fvqxjfgn.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2wydkvdtw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gt2xcjftzxx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cqqwz.cn/Article/details/gt2muxtoclq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2skpgqexy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dashuyun.cn/Article/details/gt2nxkdylys.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gt2lcklkish.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2rcrmzdad.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gt2gpifyzqn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gt2lcmhqliy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2uwtsjuev.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gt2rtbwzjrc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2tquepink.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2pootrmst.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2shljgmcd.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gt2udduqwnc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2zldacfng.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gt2iuejmolr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2qodsvblc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2ilynpsjt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2wfofrwul.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinqigufen.top/Article/details/gt2tcycsysv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gt2klivkyns.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gt2dordbofk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gt2fyepvxnq.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2bvtiebev.html


<!-- 参考信息 -->