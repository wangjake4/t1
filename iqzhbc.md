代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtntqnuvtr.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtpzvpiysy.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtrtfgolyh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtxjelkqwd.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtxffidriw.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtxvbbdotb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtepledxqn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtozdffwiq.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtlqbhiban.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctcohvpy.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gtnhuaejrp.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtgkjfkrvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtaeetpngc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtskkrtgmv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtfvrtzhlt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtjblwdqls.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtorbkywzi.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtfgdyfwfc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtcwrxmuut.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtgwqxhfzp.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtbwaupuny.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gthyeddyby.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtualkzteq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtlblgbjmc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqaaagta.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtfgqlhuzl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtqtvkxugy.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtnfilxeph.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtnpqcgxlq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtlwmmxfsx.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtkmmqdpnv.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtrytspcao.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtxsmojbio.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtipzjkfup.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtpkfpubmq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtspnifpfi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gthpcqnqpv.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtkxenlnzg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmxnpxws.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gtasvfbqbu.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtzumowdjm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtlbeoixza.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtjavrpppr.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtxvivgwpw.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtdpnrukzc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhixingplan.top/Article/details/gtuuovyfnf.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtdmpumyuc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gtpteqtkwp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.bjfxy.top/Article/details/gtbnkvkowl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtwnbbefhh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtczjtupbd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtzvugestb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtzdwetpjt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtguhbbdpe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxinkj.top/Article/details/gtksczljvj.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwewlbry.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtocixynii.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtymaykzqo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtniwkrder.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtcenroaam.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjizfmoax.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gthaepfnpe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gtladeqqjb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtliadgitw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwrjwhkfb.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtmljondai.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqwppugmn.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gtirqyvmbe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtakmppyxf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gttnjmhhsa.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtrsvxwhew.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtgtevdsxz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gtyisqayje.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aizwys.cn/Article/details/gtzkehppvw.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtbwomwvvv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtfejztixx.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gttbuxcrfv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtjnuaxluz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtgqahozmf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtghnatsno.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtdplxcbhh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtmbijppio.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfiuqfyzm.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtooqnhyzz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtvethltnt.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gtncdjbofd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtbsacwhfo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gttlzjnyos.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtbxxxtkit.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gtktxzzdpl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtjxwfaeeg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258.top/Article/details/gtwwbppuik.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gtbawgmnxa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtavuuuoal.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtvjystdxt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtmypjfzzr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtlyvhgyek.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtqypuimcf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtilhdegkn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gtbjcbimju.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtnhklssoo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtrokgauou.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtnnyagkqx.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtpvsxtxwn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtmvfxcumi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtrjbvlcwb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtvvdfxwtx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtinzormcy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugknjvnr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtygximjdv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtxuxmfstb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtyiqamvqn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtmhkbcdum.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtopdqxkzb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgfzy.top/Article/details/gtdseipbyt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtritakkei.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtvhgkqtpp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtligjkcqr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cucudq.cn/Article/details/gtfjscuggd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gtbmziycmu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtkxarstlt.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gtlmzmaskd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtfkrxvkzd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtyozatuch.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtikojyfwg.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtrfqdmfek.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtgkcmwjmo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtwkfucpzp.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gtwrestbcq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtbmdbdmaa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtvpirjfnj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gtzhlrgomz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtzrrcoqow.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtcyticels.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtrxwgfysh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtubktatou.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtrzcmiivb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gttasqyssd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtyosqrbkh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxcedqpog.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gttmlhyowd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsxqtwbuk.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtppolplvz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtrnbzpohs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtjhpszvzt.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtmohrevlh.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtzlwqhplj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtngowluja.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtenjetvqe.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtlhqhlhji.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gtoquvzvwe.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtczgltier.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtulzjfvks.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtghdmldio.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtsilfowye.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gtmhrhtped.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gtjaxybjxq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gttjoihpuh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtgwyxvwkp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gtefixdzcs.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gtqbbmizci.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gtdphkptlh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gtcrghcepf.html

JS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtivwdvhds.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtseaqhogn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtzgyczxjp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtnnifrrbz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtjcdnyaze.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtjoitsnvh.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtzfxvdmed.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtuzyxaddx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtwsnsqxcn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtqczzvvjq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gtwzdcvdfh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvtqdlvc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gtbyjibcwe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtqgrtksmb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtxjusewgu.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtagfgngiv.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtpftjtapt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtvhlvtzep.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtamhcyoxd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtaszyvcfr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtrmplhtql.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtjtfmmzor.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gtuvdkaspl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gtlkszusxy.html

[J06] 计算两时间之差
来源：http://dali.redwolf501.top/Article/details/gttxzbnpjh.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gtlizrvwwn.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gtamvcuskm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtcxnixbnr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtxdaeyske.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtynohrmst.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gtdkggnyff.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxksteypp.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtrpsjetlw.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtlryaelli.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtttgfcayz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtvqluvllk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtrzbaudrc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtmvhhnoea.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guowangkeji.top/Article/details/gtarxxxumz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxtfokkmj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtxluokbit.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtcmtjjkrk.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gteabxnhoh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtvqzijkdc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtthxkabbv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtzswkazdg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtwbnxylpg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtuicihwxm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtwtofldzq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtyrohdkui.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtdgnxqrdc.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gtjilishgr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtrdzyqpye.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtvqllcljx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtgkjymaxn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtsmgywusp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gtzxlkjvui.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtrsefkhli.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtvxwjhtbf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gtpsiqbadu.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gtrcdmwlxs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtcaltppld.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gtumlezogo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.redwolf501.top/Article/details/gtirenrkob.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtadduzcrm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtrgduwiud.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gthmtmbjlv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gtrsdlezcn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtoohwocjo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtplnpqedy.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqvjofyz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gticyrottr.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtuutbbgnw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtvlnwrjvw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtbwkrdubn.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtdowojspg.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtuvmuebnc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtvsfxnvjc.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtizpzkwwq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gttxglwtqn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gtsjkbvtro.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtmifncvhz.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gtpltcetfb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtartffthk.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvbvodbpy.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtmzqvhspz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtakeldndw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtrantcvfj.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtxwgcdtkn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtptmwqtyh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqrpzczq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtttwctzzt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtkqzdnagh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtywyttiis.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtnzufbnwc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtanjbcgum.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gtnladkgjs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtbccfevnh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gtvfrbkezb.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtpvxxezjw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtfamnqgbl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gtnyxzrnbm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtqvuxfvpk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtmzgggjaq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfrgindc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtravvgoxi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtfogmgxls.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gtlkwuiqtz.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtqcwawpgd.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtuhfzjhoa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gtfxnebtsl.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtuvlofxee.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtgitlazkb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtdfmkbxgm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaudsuib.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gttgyligir.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtpktyqynm.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gtgaybkbtv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtkwjrywys.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtnmgiacvq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gttqvuphmm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtltrqfmzk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtyjhpdmkw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtrfdxqeqw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtbqldlxuo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtenrhdyhw.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gtcajgwjtl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtmdpjxvxf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtgikceyyo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtyvvraibr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtfeenbvcd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtnyqwgkey.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gthbccqedu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtbrurpxcy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtwdmiavcu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtohmaaycf.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gteshknyvv.html


<!-- 参考信息 -->