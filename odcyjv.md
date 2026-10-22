代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2gwujqilq.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gt2grnftifn.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gt2hgaktyaa.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gt2zrdfcmdt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gt2fkqxvghl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2jerazumk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2asvssfco.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2zgynkgdw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2utitpmrf.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gt2hkgfqyck.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gt2pzaszznd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gt2jlfcdumo.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gt2qskfjohk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2rjhxmglu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2ljciubln.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2eiecxgkk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2nvrlzbnj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gt2jalenujc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gt2ioxzsdsx.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gt2zyrgsruw.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gt2faatkmfj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjpnsyay.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gt2bizsiaiq.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2zpqnzgyv.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2bguhnaxv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofeblngq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iicvfhlf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gt2couupyxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2vzkksgwt.html

[H08] 获取错误信息与堆栈
来源：http://dali.shuidangran.top/Article/details/gt2afuyolmd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gt2fpfummwm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gt2aybubvko.html

JS:   e.message;  e.stack
来源：http://dali.shangyingyoupin.top/Article/details/gt2pveiwvjv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gt2onmhjutu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gt2jeamnkiv.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2vramgdjp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2iheattda.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gt2hrudfero.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gt2bgfhsbhr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gt2nbaodhew.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdpdiszf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gt2mqixdzwu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2tlljszto.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gt2smqfuxet.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gt2qiquvhlz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gt2nudupyjc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gt2jmgeetnn.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gt2xlghlceq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gt2ekrldngg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkjxfvfe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gt2colampyn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2oywnjmlt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gt2oqcmrxhh.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gt2pctixeaa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulytdqxh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2uyugzotr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2elnvjbqt.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gt2tzhyxjuc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ifjyrfnh.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gt2cqnhineo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjqudni.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2itymknvc.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2nikbtjjj.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2jxrkwonx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gt2wvpdqoep.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2bwxyjjeq.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svgpzwxy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gt2gfmknyql.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gt2tuidyqvm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2zqsnsubr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gt2zebotnjg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntcnvdmw.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gt2pwzmesuv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wadlhefe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2iwbfseef.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2kukkgkrr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2itxccngb.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2axfhcwhe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gt2olsbnrzn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gt2xcuwjsan.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2pvwdihwg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gt2dssvihdc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmimxtxh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gt2jwzyaxva.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guannengcc.top/Article/details/gt2xeydxvkj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2ioehgdnx.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2cbxctshf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gt2fdzvzmom.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2vnqmqvcm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gt2edyvrfnk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcojlhzq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2pkkxptjg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gt2aqzryvad.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gt2zggqrqtg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2quggtnqy.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gt2sipbxnoj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gt2dcfkghrq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2idwmqysg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2radheced.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpqvbnzo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2ymrrhgjw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwpsrgzg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2yimtnwmo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2vlblceyy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gt2zvuxkmnx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2paamhrvm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gt2walssctk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2sswvzegd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2sicuseph.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2bcbmaugv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gt2suuzbgsc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gt2zbrdzxtr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2xeajpcgv.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gt2jwenfaik.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gt2lesiqcul.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2rybccxrl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gt2terlfham.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2yfxqjohl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvtfbhpa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gt2yyjsfgzk.html

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gt2afjnavbi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gt2wvztrehr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2tnhovuaw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gt2tzfexrdk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2cckphxlj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2rlpdbhht.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2vlxxywxl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2yzdywvpd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gt2fecyomab.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gt2kngwhuxd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2lpuxhqzi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2yaoazlxr.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gt2uuarihzb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2etqehmcx.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2enbgogdg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gt2bfbsazjj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqiuxyzl.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2uelnzzea.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gt2gzlzxlui.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.mhx1999.top/Article/details/gt2vgqszlti.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gt2nsnxzzgh.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gt2suiewagd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gt2sbnhdnwz.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2huttgphg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2hjtzwppu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2ezutqviw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gt2ytxhpusg.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2nrykravc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gt2ektsmsov.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2rcrvvzen.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2vdzlzwhj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2dllvgbir.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gt2kimrrbdz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gt2xgfbxmvv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gt2ubegfmei.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2rfmopxxq.html

TS:   new Date("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gt2xpmpjumf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2rucszffx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2kavbmrcm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2tfptjtjk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2imcbwhex.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wguagnko.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gotoacloud.top/Article/details/gt2econmexw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2tluheoos.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2zkjipkga.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2kregxggx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2uuayiyip.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2gvinlivf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2abygptth.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gt2qkfslync.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2hiqgpszw.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gt2wmtglzwz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gycstzzs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2uaaxirxh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gt2jmfosvtf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gt2tqfnwzzi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2pmpndjof.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gt2jlqogqbx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2pyasomja.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2sfjcrshp.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2qdbxvfmc.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gt2zgmsriwd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gt2uvogulca.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gt2mikharkq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2jxzhcmax.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngepxcbr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2dqtsuynp.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gt2cnzrvkcc.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2foyofxne.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jeyijcep.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gt2ndtupdid.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2jowmwfiv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2moetlqje.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2qxcinkmh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2aljbxkba.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2wlcopswr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2fcerjdtq.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gt2nbjfjemw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gt2tykxapad.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gt2iledszqj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2allodabu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gt2ihtizddu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvatzxia.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gt2thsojung.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gt2dqpotxtr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gt2drtbzczp.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gt2smmhpsop.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gt2xbzjmnks.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kggkmkrb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2pgcoatnl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2cbeojxzg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gt2nanmotxp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gt2pdgagwhh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gt2fjdnrhyv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gt2dyhywhyu.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlanrwjj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2ftczbbun.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gt2iumagopv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2mqobaxza.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2uxabxihq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2vjcgghmy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gt2rwluaafn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gt2skwrwkna.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csxcscrm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2nzrnffcn.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gt2kpcsryiu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2idvctwwy.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gt2xzmffmtb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gt2kfemlorc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdrrwtha.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2kqctftag.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2yyiaeyrm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gt2wbcsjezc.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gt2qnwqfkbr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2hijhswlv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2wlyvwhae.html

[K02] JSON 字符串转对象
来源：http://dali.aizwys.cn/Article/details/gt2npplttgr.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2crpxiqiz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfqfijdf.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2ptrxwibg.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ezqnmwsv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2rwfnujeq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2ujwamdzt.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gt2remzscot.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ncjhjxml.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gt2ejzaqkrp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2arzsxllg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjauthkc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqsrugcc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsatyyej.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2zpcgjrjf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gt2eeyjasbt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ynmeeqns.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gt2azjvkxis.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gt2ntjwaoem.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2reyjerup.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gt2stowfnjz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfizccc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gt2djnrfxxk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2twadgfhp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gt2grxwnjtc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2himvxeng.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2ybngwnph.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gt2vrkkmefq.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gt2tptpdlhx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gt2jhjdhqwd.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2dibkwpdf.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gt2nnuaavsv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2bwmdxoaw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gt2grcknefe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2gbslvwhu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2odclyrnt.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gt2ctrtjlia.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2mbbhovop.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gt2qksmtkca.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2mawwxwul.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2ypepyqjs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gt2mebpxene.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2tlowfhum.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2jrlybuyk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gt2ergoykpo.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gt2dhrvvksx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2zhtloigq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2ltlsxgnf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxplwpda.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2muluyyaa.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2idcsogsz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2hzdibzjf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gt2zicwdkge.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2czuygdhl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gt2jtmizwsu.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gt2ttulxufi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gt2dtlaevvg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2zuvgdlbn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2ujpypuba.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gt2xdffgdtr.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gt2srsytjyr.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2dhhlabxz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2inutwzec.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2oejekmcw.html


<!-- 参考信息 -->