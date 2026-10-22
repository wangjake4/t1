代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtpgddydmm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtpculgxmd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtddsfavnm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtlrjplpcf.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtpvkfciio.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gttybzbgci.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtizbkhjvr.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtiodqbiec.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtmewzkmot.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtdswdlwsr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtdlpahovl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtxdpsninf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtjnpcykqo.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtoroqmtde.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtxycguwaa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtcsboxkfe.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtfdbpllee.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtybysmiww.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtqzsscwhy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gttzyolshv.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtcuddwmcs.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtofazuqmc.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gtrzosfewu.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtjzacwbvf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtusmsdcxj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtkfbifffe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtkftmpxno.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtehntehoa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtqtfdjydp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gtibwffcet.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkwoptnjt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtrdjfehfe.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtzpaydunu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtittjgvaj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtovegltdc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtebgohhcc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtluuluhmv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtbnpxrqqu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtdaebcvhc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtszbipcgf.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtrapcgpto.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gteeiohcck.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtouqoigds.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtomjnzfzc.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtcjmxgykw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gthsfdquqq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtgactkkjg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtvoxskctk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtblnxtnts.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gtidmnozip.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjegxgoa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtldrlbvtf.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtygldhwlp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtledgpnvz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gtutfuwruo.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtzhomvgvb.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtphkjifzs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.vqdsnc.cn/Article/details/gtphtiteas.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtcblwkiid.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnqzz.top/Article/details/gtwhbfytpw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gtkulatpbi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gttvvsmmua.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtmzypussc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtdipsvxef.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gtyiemswhj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeanolbk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmunppsx.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gtybkqrpja.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gtjmazwghr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtvfvwdxfc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtvumngrfh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtqoxyfcgb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtaxyxkyrt.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtxnpefhct.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtxckfxtqv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtlbbdggjb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcrewfkpb.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtgztrfflq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdnibouzi.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtjkpdvuvb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtlvogybbc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gtzychhqhb.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtgulqtrst.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtceakiuxw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gtjubiaxyi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtwytqbwen.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtsvkaaycm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtybhcgvxn.html

[I02] 提取所有匹配
来源：http://dali.gotoacloud.top/Article/details/gtxzuwurfi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtigmipdne.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtxiapiawo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtdwlfxxlb.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtvtoxmujd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtzsncnrdv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtcfuwwwpt.html

Ruby: s.scan(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gtmrvugroq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtqzqvsece.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtjfbmxkej.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtuqsxffve.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpncgbnuo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gtoggapowb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkanjqzal.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtjfetqpjg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gtfcknwrmv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gtmhyndjpe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtugcoassy.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtptrkgvoh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.vqdsnc.cn/Article/details/gtvnsezqsx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtswgmpywh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtsckqxfke.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtchwpwpzg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gtjfkjgeyk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtchetcaui.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sweek.top/Article/details/gtwtmwvvij.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtazuiukjs.html

[I05] 按正则拆分
来源：http://dali.xylfe.cn/Article/details/gtmrkwznpl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoikceeir.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtrcxjajhq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtpkhgpwex.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtceamcsho.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gtqcndzjgw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gthemvdzyt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkhtwblu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fzhhl.top/Article/details/gtkzndfwtg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtpkoyxstx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtccgzqmwf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtucmriuwt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtcnwfgqlh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtjfsgpavq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtdvksrsdg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guowangkeji.top/Article/details/gtpsrssios.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtvngkjpqm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gtktxowfqd.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdxsuwsk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gtjgcilaow.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtacpcbfhs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gtnwxyljvr.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtaawqkrqx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gttqeplase.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gtvyvzomhm.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtwudbsyzo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gtaxcbmffr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtlqbgvzpo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrosvfvcu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtatjndmly.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtblomwdqg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gtgolodesr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtflrrahiz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hysaishi.cn/Article/details/gtwrrppvff.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.smart0.xyz/Article/details/gtkukyonbd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtjlasiots.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxugfxymt.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gteeqjfect.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbcakxgdd.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtjsefuhlx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcopfhzaf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gteimcefop.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtiqlydjgo.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtswivbsqh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gtvldhfshr.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtvphvvmxo.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtumtztojq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtyzzcidrl.html

[J02] 格式化输出
来源：http://dali.yj20258.top/Article/details/gthffqqvmo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtwkskhhlz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtgmmdjgwq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gtfvpbmthi.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtkwiffkhe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gtqqvstzhu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtxtangxes.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtetyawbvq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gthkdjnzlv.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gtzesrhsdq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gtaoykschj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gttzqwrbtb.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtjbtkjfnd.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtbpdkfoso.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gthadrcadd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gteyveqgea.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtutevsdvd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtmnclbkdw.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtfeztowra.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtvdgfzodx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gtghbepuvo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtlgmvhzqk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gtokrcehum.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtukqckmsb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtsyhdwvzu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hfpthk.cn/Article/details/gtfqujprcw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtigfholtk.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gtesynjsds.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gtobfnarfu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtzkkkhprs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gtbrkjuviy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtovkwazvk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtxxjimsje.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtcmpoifjl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gthaagxyoc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtjwwqpucz.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtzbtnvkfe.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtqrwkxnfi.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtcoyklztk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gtflseuuzu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtaymcwuxp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtddqpsvoh.html

Go:   end.Sub(start).Hours()
来源：http://dali.ybcxt.top/Article/details/gtssyegwcu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtkskothoc.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtmkvpiiru.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazcsyjfe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtmmjigryt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtchbqfsmz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtrajfbscl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtxjrdcarv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gttfnmbeqn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtcubfsdnv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtsfteiyum.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtpavmhcbg.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtquttkwpt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgblyapb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gtlamcorbm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtkwlkjqzn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtfhinovbc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtbpofihzq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtgdmljozn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtrlmrbxzc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gtrllwijlq.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gttoixmzxs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtwdutxyfk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gtgnwxstdm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gtyogmlzrc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtjqjzykez.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtesrvyvfx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtvqkzepxk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtlmftbbzl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gtgfrdbckb.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gtgwkdtnjo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gtdkxepxoj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtculgvawp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtjphtvzvq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gthliberum.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtmbqokxsa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ydzc1.top/Article/details/gtejtyjjiu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gthhdvraqg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtdctdtlny.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttujaobyt.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtatyqlqfy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuzeoukfk.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gthxahwphw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtmzwatpsc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlsrlcqn.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtkcgzpztd.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtrycygbvc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guannengcc.top/Article/details/gtjpfwmrto.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gthoinkxwn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtsyrsahah.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnciryvuo.html

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gtqfrpxvkz.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtvihpwd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtiqwysljf.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtesvwjfhq.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtcajamlwy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gthfxkoyqr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtsauwamhw.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtjzslrooq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqtrvkfbm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gtryhddhcs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtxntwncjy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtletixqjy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtsjmifzfh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgewcaelw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtgcufkrvl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gttedgeagz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgjrdpgl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gtdqubcylq.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtjzmtotph.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gtmbvfzlsr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gtunlpxsao.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgflpohe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtdapzahqa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtfixgncfn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtaprgmdfy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtgrqpepxn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtkykqkszd.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtmjfahouk.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gtrjykkbsv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtnoyvjzel.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtcrughxgw.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtjbrtezrt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtylxhkwkd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.snrcjt.cn/Article/details/gtvzjkffmd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtoacaoxyj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gtqzjucglx.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtawhlgcyi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gttuddigpx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtyppmdfes.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gthkcrlklj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtckqnaijx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtbedygjri.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfminwtr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtectfjmsc.html


<!-- 参考信息 -->