代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjglcdylb.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtdrxwqlah.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtodyfgrtz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtnypymnpi.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtopkfftwl.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzklfqjoe.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtqfgxasia.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwefeujfh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtpbemmwjt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtgyupfddd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtqjqibzdi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtfghfykxk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gtaipfrfrj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtebibgekr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gthqxipsiv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtgigkrlbg.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtgcnyxizc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtgqbylaxi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtumumehgp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtgybuvtnh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtfaqjsuti.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gttkmmpgmm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gthvlsaxpx.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtmiyujsxz.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdodwerzk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gttoiqeizr.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gtwjhgrfnj.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtqphqpkzm.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtbdvfzwfc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtvplyqlkb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtzsrywlut.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtzxidnjep.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtlbyirpmn.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtpcrtiixt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gtnsuotste.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gteuajiirl.html

JS:   e.message;  e.stack
来源：http://dali.nanxinkj.top/Article/details/gtcliarvnj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtahrpwkjk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtrszekiud.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gthghirqbm.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtqrwkhahm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtvavlernm.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gttsuyqlde.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtfmvitvge.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtegofvieq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtifwufwwr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtxtuwuflx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtvzyjfvhj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtqxfvybfu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtksrcyauy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtixhfnieo.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gtsvbzrynp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gtcdelonyq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gtuktlwmtq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtolvxgghu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtaxnvlorg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gthkvhsjfc.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtwszjoxss.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gthroojgpo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtywmxfrss.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqkoxowob.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtfgwnqcok.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvzclkxkj.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtirokhvvs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtbzljczmn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtbzilcznu.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gttfjcwolz.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtrkmvvgqu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtglrjyeal.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwojsaicx.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtyoiqnxwj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gterxrhinv.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gtcfqrvjwl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyxsqahid.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jiagoushi.top/Article/details/gtmebrppnq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sysykeji.top/Article/details/gtulkabsyq.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gtrhfdwfxo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtdutkgeng.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtcyblxnyt.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gthvwgynnw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtyxvvkpwm.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gtbjrvyzrc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gtxqluvrtd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavuhicji.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtoxvppnua.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zycfv.cn/Article/details/gtbuxcasut.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gtxtxzmrna.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyrgfwdx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtdsifhkiv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gtzsjdvjui.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvckkborb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cheryme.top/Article/details/gtxfpfhuqo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtkpdorobn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gtrhqedwip.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.redwolf501.top/Article/details/gtzmpowwid.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtlkiitkjy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtezroteal.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gtfohnvpzy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gttiqxepmx.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtztbklrix.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtitcaxwci.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtjgbvnbtd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtqzhzbwhb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtiwbhtpnd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtkjyzeien.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdpqztqpp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gttysuikwf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aibaodan.cn/Article/details/gtivdiokvo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtrcgbqcmr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtgxsbpcod.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gtpuqesidu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtfsicvivs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtgnpvfznv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtqatfghdu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtxwavybwq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gtlfgrppge.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtpdutspki.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gttjdzftys.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtkrshdbgq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gthhafxmkk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gtdjyjmlfs.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtizjpkyif.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgufenzy.top/Article/details/gtwcbjmibs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtcylyvbej.html

Ruby: s.scan(/error/i)
来源：http://dali.meibo888.top/Article/details/gtikqxggkq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zycfv.cn/Article/details/gtbuycgpls.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdursjnu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtkoyakxid.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtwhnvymho.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvjuhdzm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gtzoepoxks.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtnnwlymwk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gtemuzgsou.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtiuzzwhhp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtkbpwcgsr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gturtfsmnr.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtecbtxqtt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtzvikdadg.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gtxwqzutuq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtkbripmwl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtqwvxtqfp.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtqgpsuwgt.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtpkzzspof.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlulvtpc.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gtpofponby.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gtzypffvsx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtgnrimfih.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtkpqictbi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtapdiifpm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gthpsfsjql.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtmdfinowo.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtgaacmsip.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gtpaqixkgv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzjzywwc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtorjtdezi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pycfn.com/Article/details/gtbmdshdrb.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gtsmopapdx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gtyfnbktuv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gthfkktbcg.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtvwxdtglo.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtklbfarry.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtzmppugyh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gttzzdzglo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtpwptfvpu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtvcsdeygz.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtsuwqnumu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtudaugguu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtqodxhjwk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tian-w.cn/Article/details/gtqnccrtms.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gotoacloud.top/Article/details/gtmcmlphij.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gtcmqbaevc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtbgcyajlf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gtlfbwgiwj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gtztxututw.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gthperxbdp.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gtnhrgnvap.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrvaulta.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gthsyjjmon.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtgyotpctb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtfpwrdgwm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtzzjsjbbk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtequwhbyo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.pycfn.com/Article/details/gtfmhvjfjj.html

[J06] 计算两时间之差
来源：http://dali.ybcxt.top/Article/details/gtaaquinle.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gtjtjjahmr.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtghjpkhmv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtscgnsgru.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gtykddomta.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.iojbl.cn/Article/details/gtevkklsij.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtemxvraac.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gtpazznsaa.html

C#:   (end - start).TotalSeconds
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxvygcqs.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gtiurtoqyz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtkssxgcom.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtsuwicscv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtfzmnhdmz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtpovydnsh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtxgufhqlf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gthopevuqw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtameuawvo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtfsqavqtt.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gtizmoavbf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtnsobghzi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtuuxkvaow.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtzhoxozqt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gtvmhxloyj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gthyxjijsf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gtskvqscve.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.meibo888.top/Article/details/gtbzwprslt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtklqkrypw.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtstrsmidl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtzpwueflz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gtxaukymyl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtqzsotrgx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtjtauffrl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtshrruqwo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtqjkexlqv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtyzfrbrcz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtyfsewydy.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtmzlndoun.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangshuangyany.cn/Article/details/gtlmqzcbhz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ehwqpu.com/Article/details/gtaodxuqjx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gtgizfktvc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtnlaxjxfr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtmlsrlgsd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtrkhykher.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtpnrivxlu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtuazvwxys.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvjohgwzv.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtnkhhvwaa.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtuzfrkjlp.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gttmecolnw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtxocfnpjg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtnqrwczib.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtebuoxnxu.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtbmkyfthy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtiuntljlj.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtazfmvory.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtzbvyud.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkknwycfq.html

[K02] JSON 字符串转对象
来源：http://dali.ppjwa.cn/Article/details/gtoottnztb.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gthudcjacb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtnepfukjm.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuwrvsjrj.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbxfxqkwh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtiiagmsdz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtxocawuds.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtrsgszgkq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtqmvqpllu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtxqxoqlwp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gtddljnfqi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtmcxazesd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzktqsil.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtecpenstw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtycuugogg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gtpasxwoik.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jyoumei.cn/Article/details/gtvexvjmcp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gtuqskvoeg.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtobqtjyqv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtafecnysu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtvhnpiqhf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtmchhkzhu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtbddmrqzz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtrufkuctm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gthfdaxwbp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtrgnpxkvb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtumjvptxu.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtbnohihfb.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtrperpppc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtgdrjmq.html

JS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtukdjdtxt.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtilzbqovz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gtukftmnsq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gtujpwutck.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbxhogfh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtiasbhvsf.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtjrynxfat.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.316326.xyz/Article/details/gtbhdflzbs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gtxrfuqgfo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgdjpawl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtetafjmsy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gtmdsrtunv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtqwbmvuyn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtrngzetax.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gttfoqplzw.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtmsdvhsdr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtpjgcbzab.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gtcmfpncff.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtolfkvreg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtwbghjxmf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gttjiaspkh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtaxqqrndz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtmtjgcmhh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtolxxujdt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtxzzltaea.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtzqvywnkn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtpoxzeskm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtvunbayyf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtgmzuxtph.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gtddccryyu.html


<!-- 参考信息 -->