代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtilretjsm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtrqgxwtzt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtqcmnnmwz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtmazypcjl.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtsihhpkzv.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gtpgqltnnf.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtgtfitopk.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gthdurnmwi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtcoiupenn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtgukqetrj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtvcfqzmup.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gttrrkboxi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtewhltnea.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtpdbfasgo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtxazgnobz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gtlchwloly.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gtymqhgqyi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtgzbvjpej.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtrvypiipt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtqpjpzuvo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtlrugomwq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gttazglxvi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtwhksutmq.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtebjsjxqw.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gthvhnqnzt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtswljgqmv.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtwbgkmyvi.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtgvrwkhld.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtgswkbepe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gtqfxodyod.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gtwposgury.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtortgwsvy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtsmatkpqw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtjnzejhog.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtbsgmsdin.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtoqgvjgre.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gtzcochhrr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtfuckvbjj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtwquoqmtw.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtkenaimxq.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gtbdvgiadm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtghglfkhw.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gtizbposkz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtaxystgth.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gtuahuabkj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuxbozew.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtxlbhttob.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtbrqqngif.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtonafrpwo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtlejlsvzn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aibaodan.cn/Article/details/gtfhyaibsa.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtuauactjv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplafpqww.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfymhjls.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtolueaxqb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtbazblgxw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gttgzpprhp.html

Go:   defer f.Close()
来源：http://dali.0kj1m.cn/Article/details/gtphmhrenr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gthbuhwvuk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtubohhrvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtohnccnxu.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtensuzd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqduyiqc.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtylctyrmz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtwsdglhdn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtepxpnlue.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtlaowhdzr.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtgzxcdlxp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gtetgmdnee.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gtovpqolsv.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gthpcfdzsg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtdllrrksq.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtmbvuipcn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtpnsqizom.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtygdgecft.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtrtdgvhvl.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtkuzrnlbj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkxkjcsb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeqtzwyd.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtstbfdmoc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gttgeguicf.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gtjrhopljt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtgkszfjjs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenzaomai.com/Article/details/gtbsjwyuqm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gttucqsyvi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtgdffslfa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gthxvounuc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtqszqkpzw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtbkuhmvqi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gtqcwimedu.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtwutykelj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoglrvfd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gttzxifenz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtqqxrfixi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtijksjaip.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtdpwmqtyp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtqdbfhtvl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtqquxvqvl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtjwrqaiuj.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtrfmciozr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gthrdjsjpv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gtmgltgxnd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gthglwqjft.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtukuutwer.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtlbjawjex.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gttjviclsu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtcpsslldv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtlihlzjra.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtscpbbtkv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqzcmvki.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtvvqwhaib.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gthyetnudh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gtiuahemnl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtidnqpmba.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgufenzy.top/Article/details/gthndfdbel.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtinbopncx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtwbiozzjq.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtjznkycan.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gtynpuerhm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtzbauybrt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtrgljjjoo.html

TS:   /error/gim
来源：http://dali.sxryk.cn/Article/details/gtdwafzuil.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gteyebagul.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gtcsfwqmsm.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gtawhfbvik.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtzrtckxpr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gthvemzdog.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtmahghbrv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtdsufwcql.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtgemkqaqp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtfddifufa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtdqnknkor.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtkvgzskog.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtzxazuvoi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtmvqtlxin.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtptdrtovg.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gtaglkmfmi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmdhayvxy.html

[J01] 获取当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtqxqllhdm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtahjtclhh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtvuibmjkw.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gtcvgsskuj.html

TS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtmmcqbiqn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtyfrznxky.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtxlljacwe.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtbkjoclbg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gthqrrbddt.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtatyncpft.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtcqgrjxvr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtofotvced.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtdrtkkqrb.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtvlddokrx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtzqmliiuq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtoukcuhur.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtjviagyxy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtjlhrmbvb.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gtmklbfyoj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtcwxmtikf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtzxtxitsc.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gthrsckmbd.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gthkvrvnay.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtprazstgp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtzpkpbdrk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtymgebyjj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwqhgygd.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gtcgqchrbo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoahdnbav.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtgaowwoxg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gtzilkkcyr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtdemwsfob.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gtcxlpuqhn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnqzz.top/Article/details/gtdyhzemxb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtshqnftff.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gtqkedecon.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gthkednwqy.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtkrqdxhnh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gtcuulqsbg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtweqzlqkx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtzqxgpdfz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtnnrlrpml.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtntkybaqb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtoukuxcem.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtsjqrikvo.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtingssrmo.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtibgbmkfz.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtkkgcxaye.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gtfcgmyume.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gttfshmkmb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtddtammms.html

Go:   end.Sub(start).Hours()
来源：http://dali.yongpay.top/Article/details/gtnwwgvmmu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtejlqhuhr.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtnwnstupa.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtdjkxffjd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtprrklgkt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtklnnzhoi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncepiwow.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtehauwhgj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtfctclwas.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtipqeorty.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtaooqdicr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtmihlsfyk.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtkjztamve.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtqcsylrfo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtonhuichi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtajzyqxim.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtwhqctltw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtkpkwtrne.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtewnlewpa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gtuazrevgf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtpktxrzfk.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtsxtviuzi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyakabtqa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtxmmzxget.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtkxlfewqi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtleskyhda.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtdmvaootw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtzmchqrus.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmvhmira.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtireftrch.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtwtxzqarg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtdopbrpjp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtevcilzdg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gtkxtkgwyb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtetzodbwz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gttthroghs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtidejhsgh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtplnlemvp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtemtashpy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsgcjkjty.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyipyiir.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlyliydoj.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtyjsjhzul.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtruucrksd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakazkuzo.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtskjrlcay.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtwisdwpmf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gtkmqifxde.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtnjrsmfdd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtjerxzkyd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtgsgjpums.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtfhwqdjqn.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkgdrytt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gtxgtjhnuw.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqvpdaqms.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtshrpwhia.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtnqrrxjjt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtqfozifus.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtphsnqmxp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gtulzsokfw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gtqrvlvbrd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gtitgrbfbt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtfuhpsbeh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtsikumdkg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtkrlhwdxk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gtlptodkum.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtvvdsnoxj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtktbqxhnt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtfvsizavu.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtbgicipbv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtrcrxhmyp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvqxulnq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gthassltbj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtbjdpisxs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlouzcizn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtxwhevsxz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtddgcibct.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtoxrmjcrf.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtdhtnzftc.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtnuuukknk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtxxboyjji.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtbsbuslca.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtxxjpcclq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gtshvpaptu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtohlasubq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtvccbecmk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzihyubmn.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigfzy.top/Article/details/gtdhpgletf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdltijihb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtsmcrbhzb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gttxguzgcc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtrrhdersd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtbiilleob.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtwyndeisa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtidmywmxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtuzvfdmfe.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gtrgtgrkbi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtqsaucjqf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtcazwdoly.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltdaksfi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtcwlhuuob.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtjlutxgih.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtjynrnrpw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj202588.top/Article/details/gtlrynkiyw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtjnuvrgek.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtbitnldue.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqzijhia.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gtasyrbthz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtiudrpcup.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtkkmuuykh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtydohqjpu.html


<!-- 参考信息 -->