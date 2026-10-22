代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtfwxkrqoh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtxjjfyffa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtseturpjy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtkwrfvjen.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtgizpyjhj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtyffetmvc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtiogazzwx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtadztrqnx.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtyudlzyye.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gtspzldiug.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtrrmgwepv.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtqmouzjdi.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtpidurtib.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhkwddft.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtgulzdubo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtsrgezzyl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtpchpianc.html

[H04] 自定义异常类型
来源：http://dali.nanxinkj.top/Article/details/gtdhkykcox.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gtieqrippz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtysxlmyee.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gtngdlkarh.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtwvbmwtnv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtuubnqfal.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtntbsiaoe.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gtwwxomins.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gttjexeuxb.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlawtpwv.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtlefmfpjb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gthgfhirfy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtuxcipouv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzypocuny.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtwgzyoayy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtjhwsjjgc.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtdvgrhybq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzdxgwfa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtsfjezojj.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gttmzvazhn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtaxtlnclb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtxswsygwf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtyovcoshl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gtzefezset.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtjanpvtan.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtdgceskgz.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtltwxzfyv.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gtlxixntti.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtbaccogtm.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtgobpeszf.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtmgeqgnkt.html

TS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtbtamgblm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtslrtenpr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gthfqvnrzj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gtlelxdymw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqifxbgi.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gthtizzcnh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtjmphsvxr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkkwogue.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtbesijvdt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gtnrwqebxy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtzbcngmel.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtlytcdecr.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtjjmgmjcz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtgyxrijmj.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtqdkglsec.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtifrcypzk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtplpduyco.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gtucfsenzw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtfozisjzf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtxbjqjyro.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtljecroaa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtvsygpros.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtmkunokfc.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtrtvyaien.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shzxlz.cn/Article/details/gtipwfmrbn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtuzqpxrrq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtojkyzrap.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtwgcjzgde.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xylfe.cn/Article/details/gtfjkjexen.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gtadvpahid.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gttknvjojf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtsyrrxunv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgywdcnuh.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gtpkjiukjs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthcsjfgnn.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtgwbfrcji.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtdavjjrfq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtegmohnby.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtgtdiuvns.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtsbbfnivh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtskduacnl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtgsudwzjj.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtazdggopc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtfkkmioad.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtvjsmjvxb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbgcozma.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gtsqskvmdo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtxfajaulx.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtzephvmge.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtmlyfjhxo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtwzzohmmx.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gttszlfbik.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gttazonqzc.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gtdlkhqjdr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtvbjbwnez.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gtlarsyrnv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfaezwuc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtgtkxhynk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenlongwang.top/Article/details/gtckyjlyxw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtadosjmag.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cucudq.cn/Article/details/gtdkhajbvv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gtgxxysxay.html

[I04] 正则替换
来源：http://dali.svipenyu.cn/Article/details/gtglitqfvf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjfvewlyk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtbegrtpbv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtmnaewcpy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtixcusjfv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtpmhegqyu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gtsqboysbq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtgfimxtoi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtaebwboio.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtaizxppno.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fzhhl.top/Article/details/gtzgaibmqq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtarmyfgfo.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtsjxesqph.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdqoddge.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmdazxxe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtjsprfevn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtsiedgbkd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtsmgztqji.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtfxidljvj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtvgwjgnvi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtvnfxuilr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtevtgvmss.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtgssgrdfg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtjtrgllbu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtlujipnqp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdyflzbz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtnjeilaht.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gthxftiiiu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtakyjolbi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtaijbftkx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtiixpocje.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gthedoihkx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gthijijwfk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gtxdhcwyjd.html

Ruby: s.scan(/error/i)
来源：http://dali.guannengcc.top/Article/details/gtbbxbhbsz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtrnegsfxg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtprczzqpe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtidmnvbjm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtxzobeudc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtopbhmooj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtkekmrtwb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtonpujwso.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtlpmxnkfo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtzqylqakj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtydimacai.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrgebrlkm.html

J. 日期与时间
来源：http://dali.pengpengdd.cyou/Article/details/gtlusnunhu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqotahces.html

[J01] 获取当前时间
来源：http://dali.yj202588.top/Article/details/gtsmbuvgma.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yangfankeji.com/Article/details/gtsoxswyyg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtwmgflywf.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtdywrdsbi.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtmeozhvet.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoueqirne.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtdkfbayxs.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtwixeuhjn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gthzsubosn.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gtpeizlylh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtaqimxlle.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gthspmyfzr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gtpbmimarp.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gthsfnifnk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtemnrwkcv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtnboirprf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtmgmrpwrl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtllyrjywh.html

[J03] 字符串解析为日期
来源：http://dali.vqdsnc.cn/Article/details/gtprlbvfap.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtkzfyykfb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gtazrmwcni.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtcgrpzvfy.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtkaxenvyd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gthsftvuef.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnmuigmi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtlecjocsa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gtoltcuqfe.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtjubxttuc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gtkvjilici.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gtxybcsdgo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtvbfuneya.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpnlexje.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gtjaoldbtd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gttsbqnkxi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtxevonati.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtaplgbcqc.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gtkymdenbs.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gtqfscqpar.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gtcriefwwo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtvsjevoda.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtnxvrmzbv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnxiangtu.top/Article/details/gtnjigmdno.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtgldirfru.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gthxposmld.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtohwrggsy.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gthpptufkn.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtzvmttqln.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gtdkelkcep.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gtzmbwkctx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtwkcrttqk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaagaxvc.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtpqnrezpn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtrstzjurc.html

C#:   (end - start).TotalSeconds
来源：http://dali.daria6918.cn/Article/details/gtdscioiti.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gtrloiayix.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gttxvlhauu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gtfgeqahdj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtbzpnxrjp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtdfufrwps.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtzvcbuxwk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtwnpmooyu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlefetsir.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gthexhzhtq.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gthoevtxwd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gtcuzdobds.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guannengcc.top/Article/details/gtcworyqsi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtnolvpfog.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtsrbzxurw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gtazepcbux.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtfamcqdfk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtiqhmjcmt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtwqdhzczo.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtdjbmcrrj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtoqjztpwr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtkdharxtq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtaovgpzyv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtvccgvqqz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtztoqtwpj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtrvcgqdoh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258888.top/Article/details/gtupcjmalc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtbnrcilre.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtpzaxenae.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gtmomebgde.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gtxgitkrov.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtogzfldtj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtppptrgfz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gtgirdjbwk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gttipmkmte.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtjuayixfw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvpbietux.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkemxoxxl.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtguooxtut.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtklfrwstr.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtcudpddhp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtmttxcncu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gthzrfppae.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtvqtnmuox.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtmdmjuggr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndtmyifj.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtohvyxzgg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gtesugaznn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gtfeesjspb.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gtlfxoagnf.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtwaexrxyx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sufxvd.cn/Article/details/gthknwsswa.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtugdinqxa.html

TS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtjurazisy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtzxbtbcpw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtnoxodlrd.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtuvbfndoz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gtjyefaiim.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekjxdrig.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucntxdzy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeotppvy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gtujstwmfk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtnvuxjwem.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtwhwfuyhe.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xinyue.icu/Article/details/gtuszajvcx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlrkjqjsx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtzctvkujw.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtqegxhnox.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gtfzvwekjx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gtxjwverxe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtmeieuicv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtsikbclzt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqtnsywc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtlcgufvsx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gttumpyhzs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtyqbryixc.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gtbqufcuae.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gtjkdknqbp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtnfnrrebg.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gthitnnetj.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtowbmfvxy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gtmwthjzhu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.kuanghao11.cn/Article/details/gtgubefaoc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtznsagocy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtpsooilxo.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtuahtpfgd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gttsemexiw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtwmrgbmsn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtjdktqqfm.html


<!-- 参考信息 -->