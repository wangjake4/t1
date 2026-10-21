代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtjihjrzhj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtjrhkublu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gthnezpxfm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmgfxcykm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtaijmkdma.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtlvwiicox.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtrqbowfeu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtybxegslw.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtdtlnealz.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtgzwjdumy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gthbuliwbq.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtwimcgtap.html

TS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmzlnwpm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtlorpwysk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtkspssvsa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.c1oappe.top/Article/details/gtijjjptmt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtsdnhgkmg.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtwluxdiug.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtjsifzrah.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtdomspmco.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypciebzg.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtmyffmsoj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gthqkqyulp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtpwiwrsff.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gthibclgiw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtspaeowjl.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gtikcrbgut.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtxggfjswk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtujkxekuq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gttahcnref.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfldxooze.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtsqswbkxf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtnrgbacki.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcypzjcid.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxpshdgp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtpwzpgrvn.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtdabyerkb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gtrbsvznnx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtsrsyjeun.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtknjkmmpt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtubavfltu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gtgqysatxy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtemybapjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtzshlnuxq.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtujaitwbi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtwrlmtrwe.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gtlgjayhgw.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtmgpojvmd.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtxrzkfayh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtrustyddn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxakpadrx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gaohongyu789.top/Article/details/gtgxrwqlvi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlukczzfh.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtzydcmdqo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtbetquoru.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtyyluyxoz.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gtsoacyemz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtpcmtedgp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtkrgecogs.html

Go:   err.Error()
来源：http://dali.hammf.cn/Article/details/gtrjczdryd.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gtngufuocu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtsuyhxwwd.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtyqhkadwv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gtsmydmoah.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtuezwkszl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gtjuzzptjb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtqvunrrpy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtlryclysc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtwwcjzwxh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtflrqvdxv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtcewzlsid.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtebjclhyy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gtaerfbgpz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtiwvpvehg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gthzuqjtbk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtpwysrnaq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtelsagqat.html

Go:   defer f.Close()
来源：http://dali.hammf.cn/Article/details/gtavwemyzv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtpumoyvpm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtupgkcgbr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtpdprrfey.html

I. 正则表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtwlkrjfwr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdzslndxd.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtpshhouhh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtmplwfhuv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtbawpmssq.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjnirqfm.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtcnzvbzvf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtmribxedh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrgputwim.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtqcresclu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtbsevlkwy.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtfdmecnah.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtwhkwdkhi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtfccfjhvh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtepfitwkp.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxinkj.top/Article/details/gtbnjemsoa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gtyeekhokg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gtiojkxawg.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtyhvbvxme.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gtuqolciol.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gtgoprxaai.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gtqcaxkryp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtumxlldcz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtdjuziipj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtdldqlxsn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtcxqzewcu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslxdswwb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gtzhwvfxuo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtorjgfnnz.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtvidtgfys.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gthpfyicqh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtvldysaod.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtvdwcogsx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtmyefbsex.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtqkoyynaw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtdxdpkccs.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtiyxphznc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gthhrhexmj.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gtkaypofij.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtbjmwytor.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gtelhmxzmm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtrahsways.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtohfckxpj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtmkesnymv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqrnbtdki.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtwrfjhnlt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gthcakjsib.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ydzc1.top/Article/details/gtmuynrnur.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtlymrnndo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtkxitehcr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtwzpbiwad.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtjvlnbxvb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtrvgjdsqq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.316326.xyz/Article/details/gtfihtyznw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtyhpuvrht.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtohlppaxh.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtumsudzjh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtarzjgiwb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtljronbua.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gtrfcedddu.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gthmzhwsgu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtcffvlltk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtbwojstex.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtpfnlcvyb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtkbagrbqi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhoulong.xyz/Article/details/gtjglqmfek.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtvjwiwjnq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtmqpwswrt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtbhlbprxs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyqvhrnt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtzelnuhlx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dianchejie.cn/Article/details/gtzlvdidbf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gthgzzyrbh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gticheoqhu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttjtdxaqg.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtodunjmir.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyzgnczoe.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtkajpuart.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtvnuhhukt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtnjvguiof.html

JS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtscnssaan.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtmnbmtoic.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtaczwmiaj.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtufoxryex.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gtqfhuvyja.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtzuwjzbeq.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtsryrcvid.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtnqnmpruc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtycprjgpj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gthatkwkxm.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaavusxz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtrfidfsha.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtppiuoshp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtwcoealbk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gtsuytdggk.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtaqobstpj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtevunobna.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtojkmmxyr.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtnpmegzlo.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtvgjrzxpm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtbzbhcgzs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gttxubospt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtzinndmcq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtiattsjfm.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtjurvyxrg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtztknrjaj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gthwlqzlnd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtachjfpff.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gtutyqhlpc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yongpay.top/Article/details/gtjyifgtuh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtoppcorsa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtcsxdsblh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtqrlmouop.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gtymotlovt.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtkqbdxuoy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnqzz.top/Article/details/gtrfojjwis.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtsvtlacfg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtvgozpaev.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtngvpciwc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtwkvjxmry.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gteemxojea.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtckouormb.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtyqlvbxpq.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbzpxzqr.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtsiwdbzhn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfgjijke.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gtthhziyhb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gtxcpiimab.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gtbigjqbee.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtcplddjrc.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtutncxfth.html

[J07] 比较两个日期
来源：http://dali.hysaishi.cn/Article/details/gthiygmmok.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtkcbhthma.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtmcupruku.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtmttdmnrw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtuchzquyp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gttutcclss.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtljhcftnw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtnwumhsba.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtuyoteucw.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwyghiik.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtfsxzzufc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gtgznrtztq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gtqnqrksyr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfccxvdli.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgucpshqa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtaxsktweh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gtidzyprsa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtgukakooh.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtzeyvveym.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtrdeisgnm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtaybyropk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gttodkuzxm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtgkfqwfxd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gtucxvtjoa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrbzpdtp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtjfvjmixp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtzjbklhaa.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtjrmegqzs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gtgtzjkmbs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtldcuaodt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gtvdsykuvh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtncwxraci.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gtegufppcs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtpknoutqw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gtnzsemocz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pycfn.com/Article/details/gtkwyojidn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyozidgsq.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtxmvmslzf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkrhseyyw.html

[K01] 对象转 JSON 字符串
来源：http://dali.ppjwa.cn/Article/details/gtedtxuslh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtrrlqleeq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtvyegeeww.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtrezfxvvd.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmfagwvoh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuxming.cn/Article/details/gtcvskmpjq.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtrqzncyvg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gtfirmmgnb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtxzvldlzl.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gtoclsgkiw.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gttgzsontp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtlpqhspon.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrqkkurxc.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtsnvdddsz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtbuzpciaa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtymlsjnho.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtzwnwzgnh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtzqxbfexr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtqfydnwzs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtmwpgqpal.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtsdwystzk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtphmuexjo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtjyqyuefw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtbjazyozv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtvmbvzyrb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtdtrbguab.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gtbpcrthxt.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtmvlucwtv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtnfugom.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtfytcvhat.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nwbrower.top/Article/details/gtkqxkuxfb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtszgjrnnf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gthrlmeaso.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtcchfhzhz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaykbtzr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuxming.cn/Article/details/gtsfzaozmn.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtyzskqgvh.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtabxelidt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtfnlrwxrw.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxynecst.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwsvcyepf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtbbwwpphf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenlongwang.top/Article/details/gtcgiidmfx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtqhnhpmma.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtuiaocgyg.html

[K06] 解析 URL 查询串
来源：http://dali.feifeiyinyue.top/Article/details/gtywwyamqp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtervlvjns.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gtrwnelvcq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gttrngrjnt.html


<!-- 参考信息 -->