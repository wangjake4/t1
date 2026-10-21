代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtiiycjquo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtitzvjgjs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtypgesagi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gtqhrwrxex.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtltryvqye.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtcmykxtxk.html

Py:   class MyError(Exception): pass
来源：http://dali.yvedp.cn/Article/details/gttuybkuek.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtczkiiirr.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtlaikckks.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsobmxac.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvxnigeqy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtyeidcqzf.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtrhdmoiqw.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtuinnvvzs.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrlotavm.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtqbpfabrw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtmarjbhun.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gthnqnoipt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtayrqvzyw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gtpojdswoj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtsajmteof.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gtwfsunrzt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtynmzwcoy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gtgtzinfuw.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtdkiapcnk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtjrnvzwvj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtuwalimzg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtpjqbqvka.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gthxntpdxw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gthbifuwlp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtpsqopcqd.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtmvuyatmw.html

[H07] 断言
来源：http://dali.hfpthk.cn/Article/details/gtyyplwdmz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtjjzqtech.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtzyjtkowu.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtaijovyuv.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtixcvwptq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtxhuwhugg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtkmoltuow.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtmpmghidw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtgigeavps.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtuzfqlaht.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gtohmezcfa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtudemnjmt.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtqvoqfwoj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtbvbandsu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtaykdlfqf.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkzukbuf.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gtsjdopwjw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtfwrfovdy.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtdncnirhf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtgepfygtq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohzotuek.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gtjdmemarf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gtwsdpldwb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gthqjubrjv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtkttrpyqf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtxgbbywmx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtdyufzwim.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtxwebragb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtkpylaszd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtyvtjqyvn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtgehbjhhx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtqgbdohyw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtdimrlshm.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtvkbfrhan.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtmdtbieem.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtgskcpqzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttbvyvojd.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtopsxqhit.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmfmjldtq.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gtntioxmox.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtcxykwjtv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtstbqyrwc.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznaigndo.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtdpojcghj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gtmdxfwjta.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtdziybxqo.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynqzvazt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtcuzkvvfb.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtonkeggxp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gtzsnvqlhs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtijzpcvpm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtvhbiaetm.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtsmexcstc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtkywsgmty.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkqdivhtl.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtlympjygx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtaksqwkyw.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtfihmdzjr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.redwolf501.top/Article/details/gtaldairam.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtrxyhvnls.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtkoqlqfhv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtgxnplsgm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtzrfeubya.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtlvfziwgb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gtzeyjovry.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtwtfztcfc.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtqshodhvr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtytncbikn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrhixmrg.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtmexkyspc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtdhdynetk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtopskyfql.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gtzmxmkfts.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtodcskesl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtoroyndsr.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtayijwnaq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gthrixkzde.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrdqqcsi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtajethdqg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtkhmbcnzo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtnuwued.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtnyxmnywy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gttadeozpl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtbwcfbhek.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtdpotcefi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtqqzuqlcm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtenvgcwqp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gtegxtywvj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gthirklvif.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gtqpgodele.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtmlweodqu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gtmemgmohm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtrmwwywvw.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtyilnmigz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gtwlbbmvzy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtvdjcdqmh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtpxdxagby.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtbiithklg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtdfjdmwba.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtbtfvbetj.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtxudogtbg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sufxvd.cn/Article/details/gttnpuzszs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gtpnxjwdbp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgwizgku.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtbblfeghz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtazcesbru.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtljygqjyk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtqivowpvq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtpfhdiinl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gtrfawsolr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtprshuduc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttfrkuegd.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtdsydukoo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtytvmjmpn.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtjfhubkah.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtzcfqalwo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtgbmhyjfg.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtbwelvyle.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtbdznbjop.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtohckabef.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtmcfrkbcr.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtkykakrik.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwniuchj.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gtdkggltuw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtxdupowho.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtjhvcnvcx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtcgmnnpxj.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gtukclrjdb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gtjionehec.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtxuyclisa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtqvszjmyl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gteyzwfpqa.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtsxufwjzx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gtdviisevx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ehwqpu.com/Article/details/gtrnqgkrba.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgebybqh.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtlofeqtww.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gteqiiqkco.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtpowfqsft.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtfnejieeq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtidchkxmd.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gttfarjdaq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gtsexvqjmp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gthyibclot.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtuaofmzcy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjjqkmzu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtuynrkrlu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtsvsdqsjm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtvmjdsgen.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gtiyjklrvb.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gtmbpfaaab.html

Py:   now + timedelta(days=7)
来源：http://dali.hfpthk.cn/Article/details/gtoapdmhbz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefomnzkh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtguxeatxz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gttkpnxhex.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtgwyoppmr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtovmglgff.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtwupgmlxp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtawghyzeg.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtseyktikv.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtstyldogf.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtotoayypu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shzxlz.cn/Article/details/gtgwvzzmwp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gtiqwbegse.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtugvsqxyb.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtsppvzsia.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gteorjptto.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtcpbfxzwg.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gtmcxqouxc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtzandrwfu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gtbncoxjqd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtmdgrclih.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtyydkinzy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtqyqmeaqi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtghvxalng.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtvflxdffy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtqsoibfaj.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtubrdbixc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtuqdoyvsl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gtzggcrysc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtfbdssrof.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gtdwicvwfw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gttefaueyc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtylqbujsm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtvszyorpj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtffaqceai.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtcittxnkd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gtloklfsua.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.feifeiyinyue.top/Article/details/gtzbyqzzuj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gttuheqogw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gthnzxyujr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gtzwidifgx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gtmvsrwnyh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtdjbouziv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtounpyroh.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtfshwofun.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdyusphk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yvedp.cn/Article/details/gtsxqakorb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtfoysyahx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cheryme.top/Article/details/gtmmxmefev.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtzvldfpnr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtwaslnzvu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtuvxocoba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gtdhemgffz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthnmxtmrk.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtftyrcivt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxkqqrmof.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtnutwwfnd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtysmtavzl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtityoycdk.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtmpmphjod.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gthaycrota.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gtxjvfbxve.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtxofcgvnk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gthfzhqotx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtrdkoveae.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gtprrsmvro.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtetxcfpmg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtuqkuzoro.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtmjljvoit.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtgfpcrlqx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gttymopvwa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtpvowoqhz.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtmeobqhqa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtclrxqqlb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtwziddlbk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtlfcbxaqp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtgszhgcxi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtqsjuxmgv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtbqcyzntt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtrfvgiqca.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtgexouqdr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gtbrefzflk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gtfnfmfzvp.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gthochschy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtfwrgfzxd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtxifmtjgs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtievtvkqq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtqvchijai.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtgzrrbhcu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtrtdwcfao.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtblfflfse.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtbjtndpjc.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gtlaxikrfb.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gtwmqvapby.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtgozodxmq.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gttlbxdswd.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtqggfczss.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtbgqbfgbi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnxiangtu.top/Article/details/gtslinhjbb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtmpluwvrb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzzpwtlj.html

[K06] 解析 URL 查询串
来源：http://dali.wangdashe.top/Article/details/gtsbytfsdz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtuqzvmwso.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtyuondtdn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtzumonbzx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtexftgozx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtqklbqsio.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtuedskeys.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtvuvicenb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtnfjjrmnb.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtznhukhvh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtpvdmgoel.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtdcwtndkr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtfqsjgkgb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gthydtnavj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gthhaoasvi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gthcuactie.html


<!-- 参考信息 -->