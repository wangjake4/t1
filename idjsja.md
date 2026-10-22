代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gtmokzwumn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtqxwcxhqj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtaniylduy.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvyndprq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtmliwmyub.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtzzbmlbuu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtezsmvqkh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtvbcrvsfn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtugprgfsb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtvuhmtulf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxcsiktcq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtqnzjqjgp.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtwhfsiujc.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtbzryvpst.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gttvzxgqih.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtfckblkvr.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtirivqgvs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtzbopkqbn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ehwqpu.com/Article/details/gtsivukbfk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtjjdyhore.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtzcuebaba.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtkexgivmx.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhonfwxs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtaktkeoob.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gtxtiilkyz.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtnyvtglbn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtypghmsbg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtkyenaltx.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtafdytnsp.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gtdggfpscj.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtfyeniklu.html

Py:   except ValueError as e:
来源：http://dali.havefunace.top/Article/details/gtjigvrdkj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfqtkmwe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwsbiijzg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkreeufip.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfwzejwae.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhiaasfv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtbkkbtjrw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtzkueqjgr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhiwuduotai.top/Article/details/gtwccmgozt.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gtcrpzbvjb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtfvuxroue.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtcdhpkgiz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtotslrint.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gttyatpcer.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gttnexgfri.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtnhrsvbxf.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gthndnvjwq.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtvifazaag.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtsbwscwyv.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtfioytxpk.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtncvkxaoa.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtpxaidnsm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtxgsuufbi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtxhvpwfnk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtfwnepzrz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtocctabfb.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gteewtbeny.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gtxhxbtrmv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gtiqmcszvx.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gttwmvdpay.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtdcexoqng.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gttslgkhir.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gtwmjzczah.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtmazbzedg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtyecvxics.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtrmbkdotu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtbpappnku.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilsjewzm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtjkhragmu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtytteplny.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtzoxmwsoa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeoqkseh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobqtpfnz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtkgaqpniz.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gtwmnizind.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtsurstjqj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtzotqcvaf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtzzasdyty.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhcvaydg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtgaernlgo.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtkcltxcer.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtttllrfzr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtbmhuzuvs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdfmlbuzf.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gtmgitkmer.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzjkwzecp.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtowrbyhhn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmwwaytfb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtwcqyplqg.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtpwcbntzo.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtvvwoaxod.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gtdssrrbgb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtkqyblfds.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtrpvifhnm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtylmgglhw.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtdjdgrmuq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtftsdnyim.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtptzjvlgk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gtlbwkqirx.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtucvtnqvi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtrospudfs.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtstyfdwzw.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtarpeqszu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqtagbaya.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtloxlycxt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtekvtmoim.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtytstjqdl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtxwajdkuy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtmdnavfux.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtjjsxspob.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gtrfrjckts.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gtcfolokfr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gtkrustkwr.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtdvkorjqt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtuqactuqf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gtfixmzfbv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtlvmpelex.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtvdwwydid.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtuaptsfjd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gtkqwlsgsl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtobkhhwag.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gttuqxhxxz.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtdzdcciea.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.bjfxy.top/Article/details/gtyplpxrvz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gtwpuzyace.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtibuaptwb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtzdqvvtcw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtruskiewi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtycbywbtn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtrgrclipa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtrjqcpwvj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gteyypgmgl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtqbcfiobv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtaywctzll.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtjsxfjham.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gtucjfbwby.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtjtuzqkzc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gtijcacsgy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gtxdpzknss.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtxcdiukgq.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtlvyhlpkx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtghxkodul.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gtkcrgsinv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtldudmurz.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtqrrwrtse.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xinyue.icu/Article/details/gtdvpnbswo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gogol.net.cn/Article/details/gteyhtdwfr.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtjgtovlwb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tanke756.top/Article/details/gtwhpmpxfh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtizilwyxt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtsnbamzic.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtvfyfzkut.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gttxdymrpp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gtwnngsyww.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtgnjwguik.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtudtrklhn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtzhvlmhpd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gteoftucwc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmayogjem.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtonqqtkzw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtizgudinz.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtayeaiphs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.birdmap.top/Article/details/gtcrqblcuv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtabownlut.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtrrlteuxe.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtuejgkmwh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevfhssuy.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gtnprqtwog.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gtmmeaydsr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gttocsfnak.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtardpwdxi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthplhqald.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtpfkhzdir.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gtapmgpobv.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtecoxfonm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhkosxkc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtjotozcbz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtwrilpwwe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwrolzag.html

[J03] 字符串解析为日期
来源：http://dali.yuanzhike.top/Article/details/gtmqfxvlwj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtbpypkqor.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrubmrtp.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gthrxaypbx.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtuguoquji.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtdswbwasg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtvdhekxtc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtfpfhovmp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtgdjraxxa.html

[J04] 时间戳与日期互转
来源：http://dali.birdmap.top/Article/details/gtcanuerkf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtzaxnkoge.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtlrfgnbzv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtowsplmnm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtkadcfwxc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtprypjazp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtzldzzhmx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtukrmmqrq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtsgcunwvn.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtvnhskphf.html

Py:   now + timedelta(days=7)
来源：http://dali.hysaishi.cn/Article/details/gtimjtojxs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtqkuzihjg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gthoeyxyhv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtjacshbwj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gtywfybpqd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gtygsdwcun.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnowxbtrv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gtcuqurkkd.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtbtupjrls.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gtucrsvikk.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gtiiwnbhuc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gtljmcxwji.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gtoytmaece.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtxdjglitx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtghvmithb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.c1oappe.top/Article/details/gtqhfrubwf.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhiwuduotai.top/Article/details/gtzoyuzxtd.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtdmcbmigb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gthnrskaln.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtlsggirsg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbcldcms.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtavrmnsij.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gtgeaedjbz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtgfblwqxu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtmgnlancd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtbjnxjqkc.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gtoqvmqfas.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtpymdisvm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gturswktgp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtozbzbsyq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtffjzdfyt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gttwyqqneo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gtihfsgjff.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtqnpkcflo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtntsvphyr.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtadpkcsma.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gtcuxpsyng.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtqfajrqtr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtadhihzxq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjnnvugu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtbldpubfw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtxdflewnf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtxxdoufzd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtksxeqwez.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtckiqhwyt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtlicaogyg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtmdbxqgav.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtfrdbxlol.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtejijozmf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gthwdcbkri.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtpnwbogcv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtpiehhzgt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gtnczlgwfw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuufchvoi.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gtlricdqhl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqiwobeff.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyvcmiam.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtmjiwyxpz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtgnksehnn.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gtigyhekee.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtighehyvj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtylgkmlvw.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtsrslryyw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocoyyjjt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gttivkkmif.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gtsdjwjbrr.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gtvggolbys.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtwdogmgbi.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtftguchwt.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtvvvimtdh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daxiang520.top/Article/details/gtsqyvncaf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gtbyjqfubs.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtwmlyjywx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyhzluqj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtyfqdzvjz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtbthqicbe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtzdnlqnzx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfnhheevg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtmvgchcny.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daria6918.cn/Article/details/gtsckebbow.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtoswunnfr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtawjekpqk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtiinhrrbw.html

[K04] 读取 JSON 文件
来源：http://dali.zdqjudy.top/Article/details/gtaxylsfka.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtgjzkfjnh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dianchejie.cn/Article/details/gtansoevmp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gthzcqupye.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtdohopqdc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cucudq.cn/Article/details/gttjvvyvbg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtegucunsf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtalbjsovw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtvlenbisa.html

[K05] 深拷贝对象
来源：http://dali.guannengcc.top/Article/details/gtnkeznije.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtiocibqvb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtwtiltooz.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtwfigwepj.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtiyqyvabz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtpfzhbjyq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtkwpywkkk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtaqglzxbd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gtraoynxby.html


<!-- 参考信息 -->