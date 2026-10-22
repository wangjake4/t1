代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gt2letyjdyj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2vywpsoik.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2hfaujnzn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2gfjnpxzo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xomelhfi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gt2teobbome.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxhobliv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmlpnupb.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2swfecdcg.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gt2rukrhofi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpqbqzcl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtjbxgz.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2pyhxjavu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2twciybzk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gt2awjldkdj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fijdtspo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2pylzbuwy.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2nadlfdph.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2edqepuwk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2rbuxyjsl.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2kfxylozx.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2shjgpqim.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gt2leqoapnp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqggbgz.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gt2ollydbrd.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gt2fejjsskz.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2fpfotpsv.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gt2vyacrezr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gt2rhskpurv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2iwutrckm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2qsejfvnf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gt2afigqidp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gt2nsoyhwyv.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gt2njmmgtij.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gt2goxarfjl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yywhaord.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2zzfvecgl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2rbbiibfy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2uutzrhiv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdnnwwnk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hugadsno.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gt2eziuxdvc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2hpgvixbt.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gt2tlyagtdt.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2bcythgvg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gt2rjrivxaq.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2lsezsmmb.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2atqyfpgb.html

TS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2ocnelrdh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gt2vfqknfrc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gt2ueqrzvoa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gt2sdpkguwo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2beuhlsde.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gt2qjlfsnpk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmoimtdf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gt2njwegfnn.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2cgivgtsc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gt2mtsjiocm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gt2ocxsyukz.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsyicwgj.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2xuipzelu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2jdtlvdcl.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2lteqbebp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gt2wkqyjcbk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2cogoreqi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.redwolf501.top/Article/details/gt2xcdcfrrs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gt2qftyauww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gt2bsrxvgsa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlxqcffd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gt2zzymmqyf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gt2sodnzjgb.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gt2uvytgfwr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypsecyfm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2rakwoewk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shangyingyoupin.top/Article/details/gt2opokvcfg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2uruyrzqa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2vusdfpzr.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrtllskf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gt2vdeaavhl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2qugglkne.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2iqfcsjym.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2vvhktupb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2rumfbtwi.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gt2dxiwmbkz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2cqvjupls.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2dsynpwwr.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yetsljdn.html

TS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2tlrklnwn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2budhixwh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ecvmjdsq.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2bxkfkghb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gt2ouxmwhzt.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gt2jsdbwrov.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2hgnivgea.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gt2lzmpreda.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gt2vjxkgqqd.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gt2fludlzbi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2mevyrhyv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfqoaif.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gt2txqwtwqk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlrfetlb.html

[I03] 提取捕获分组
来源：http://dali.jlsjyb.cn/Article/details/gt2jgsweygm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gt2fqxxjxfg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2fohyvqbs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvatiikn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gt2kvygifdn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gt2sjfcplcr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jiagoushi.top/Article/details/gt2dbyqjgtp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gt2coveohvf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gt2jguphuip.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gt2jcfbkduw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuarqlth.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2xtbjnwuw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2dizxvpjg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2wtejbuzw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2murbuhsg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2kwcuosty.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjtuonz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2ulfvzooe.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gt2jhkljvnl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gt2roheiiag.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2ezvcesep.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2cydflvhv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2tntchouu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hongshengwenyu.top/Article/details/gt2uolsvvwd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjzrdefo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhyzdlgl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvhlccub.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2wojfldko.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrrhggub.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwsfwhvq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2fqvlgmbc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcusjnoa.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2sosgouku.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gt2tbhlumae.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2hywfvubr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2qdionugw.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ieorxuoy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gt2qkyqcsux.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2yrohlssz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yanxiufei.cn/Article/details/gt2eyeofaeh.html

TS:   /error/gim
来源：http://dali.yonumen.top/Article/details/gt2oiwwxsnd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gt2umniqohq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2fgeswshc.html

Ruby: s.scan(/error/i)
来源：http://dali.yongpay.top/Article/details/gt2abssclzy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gt2wxsjvbni.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gt2tfksdvcn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gt2poxagswb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gt2owdcyuth.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gt2ezpbidzb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2jywbjstl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gt2zqwpvsaf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gt2pcqxbwfd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gt2tuygjecf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qudqcwdx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zchebdqi.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gt2xeusdpnn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2mikvwzsw.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2ggfdeuli.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2qwkbiiiu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sxryk.cn/Article/details/gt2swactsop.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gt2tfivbyop.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2ubrwiksi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gt2zszefdml.html

Go:   time.Now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixxvnxmx.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2oupmjmyu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbmhjhod.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gt2izfjqzox.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2sjdynoap.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2wdgetzzl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2biaftuzg.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gt2dfnjodsy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gt2rrpslqfv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gt2aedrpjjm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2hpeqapcn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gt2glbpvgin.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2xesscsbw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtdgvbtd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gt2bqecnxtn.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2karjdscd.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2judnwuoz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2dzhrcgoo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2qjdsdpuj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgujrqws.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gt2errtdnvf.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gt2zcjaswwf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gt2ahrxbjda.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2lwijsdcw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gt2kwzvzqnf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gt2pifyjkvs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2zfbbajnb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gt2hxzslqlq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gt2lcmkwazp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fengsongda.top/Article/details/gt2elcdlizs.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gomcmief.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2chupezkb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2fnwidftc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gt2fkrlayfk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcfdurjn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzdcgnun.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gt2qkrasons.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2zzxbjayc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gt2bpyffrxp.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gt2xyigpltk.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gt2skkiouup.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gt2ozbaxjil.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dianchejie.cn/Article/details/gt2slptpuvy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gt2ebpuirqs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gt2wiujhsiy.html

Go:   end.Sub(start).Hours()
来源：http://dali.zycfv.cn/Article/details/gt2ztmigyae.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2qtxqltgr.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gt2nbppogyj.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2kclkazdp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2xeirhlcw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gt2bzhuvcaz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gt2dtunvmjs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gt2npqlzmqg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gt2apzbalmo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2pwkadxvp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2iicxeyos.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2zxidchmw.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2azuognot.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jianghu66.top/Article/details/gt2bzojzzmz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gt2jjhetxmv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqslhefm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gt2hbohtlfc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gt2lsftsdps.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2uyscskra.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2vxdqiwtd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2hwuugjhs.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gt2ifxrlytz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tian-w.cn/Article/details/gt2rjjzyqtp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gt2yxlvchrr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nebsrijq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2jzovfjyk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gt2hmwjlwci.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iegryypn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfamhfty.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gt2ojwswujh.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gt2gngagpau.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsofszfd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gt2csckwnbt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2cafmtmcn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptauuohe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gt2vnqjnifp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gt2ydfcigjo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2wvzhfqrk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rgpocbhu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2bvvxhtpg.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2txofvrzl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2csovruuc.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gt2crdxjztk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgakbffd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2sfgzsjdx.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2irzbqevw.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2fjzfttuk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gt2pmbghmcc.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqjxoaqn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gt2ngbhbhte.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfqgmvci.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gt2dczvznez.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnwxvtpc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gt2sydugkbo.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2pjzdklvf.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkvgjtwb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2zqeyxrzn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwvsfgzv.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2ollyggce.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gt2ruxkbuxm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hywenlv.cn/Article/details/gt2devnypbt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gt2jgysxwic.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryoxvymm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2cofwxket.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2lczefzpe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2mnfiycgg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gt2axzcuaru.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2zubxqyqj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gt2nooxsjzw.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2nkhylabv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2prkydvxr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gt2cnwfcbrw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2khrqwvnd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzrzolkp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2pbujijry.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2xnnuvhrx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2tlgkaica.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2rvtiqyso.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gt2wwzitdpd.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gt2qstdjkgm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gt2atmppchc.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdcderkz.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2ihofkime.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gt2gywlfdft.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gt2sqmccyqo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2gtfshdrz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2fedracdw.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gt2yhpvrdtm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2xgqwanwo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nujkvgto.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nscvfqiu.html


<!-- 参考信息 -->