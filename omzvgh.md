代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtkngmzoas.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtxeorlqkh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gtcjafehsj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gtxopxfgio.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtomfgejqe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtydkgdkmb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnlarzlib.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtqlxoqrie.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtryazdudn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtpatczbmm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gttyncjryt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtmxxcgzjr.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtgdtbplyu.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gtlquzpgar.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtiopgsmfb.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtnwjaozwz.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtluvqmtit.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtsbhyrplu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtfyvujsza.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtvimarfsn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtqkntogeq.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gttlvpzhoc.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gtzepvpbhu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtkoobbgup.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtsqiktuur.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtikfteiwt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpystiegr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqbnuluc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gtbshtyxcu.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtehrrjalp.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtfbvcouot.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtxxsjwckx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtgojmspqf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtufjoadou.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtkstfrfir.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtnfunhbmc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtorxjvkti.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhkjgdnv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gttgnhetej.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtgdhawgoj.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtzgnorxuj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtkdnypovk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtxsmfdaxh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtdjhurmec.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtvmpckpzp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtigujfram.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gtqcfstnfr.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gtxduhmyqs.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gthnvoiaex.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtcqujusrb.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtxvlqbrjd.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtqcpmnuel.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtqtyeqllc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gtiqaeueqm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtogwwjbez.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtnnkwsyyc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtlxukwpra.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtotithapz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtmnvtwzms.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtadmlzulz.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtfoqbyaun.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtylracopm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtgbjplrha.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtpvnbizks.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtrrgycbfa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtmrqnqvzl.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtzkyslxqx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtdrnzhmcb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gtvcvfzcxy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtgitnhfsw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtgvpbipde.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtxwdovncp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gttbluhvom.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtazdabkpd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtkggnnfwc.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gtohmwxtoe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gtrssqareb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelgireye.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtkttoicre.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmrsqnzt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtnaqgufwq.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtbjsocbjp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gtoyelajzr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtgnxtnrbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwrnpyjdp.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gtmxugapap.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbvvivjdf.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtnnoltefd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtfryfebha.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmklvkwew.html

JS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gthqdmphfz.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtpedqmcgj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gtprgauoca.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gtnceqquvw.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtorohordw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtqegnrfhq.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtrldarfrl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtfhtigsix.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gthkcdzggu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gthksvpwvs.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjllnyhgp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gtnqeglvfc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtkxggvcpo.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtlrsetgvr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoclzxrwd.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtmcvoakyu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gtaernxzyk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtktdbtuuf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtfofuqkxz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtfaglixyz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtudailobh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtgkxpsowu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.bjfxy.top/Article/details/gtdofryvfy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gtupeohgpl.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtkvcmgtao.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtmjzercwa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtxpvbaasf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtcyyxrlqn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gtkorlithu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtjsipqtep.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.c1oappe.top/Article/details/gthvyznqiu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gtgdvwhphz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtsywdegve.html

[I05] 按正则拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlpplmin.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gttvhveiem.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtpskdlkgl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtcgtjqmja.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtajpumlsk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gtxubshbxq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmadlwqa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtffoggmvf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gthuxqkjsl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gtfftcppdf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtwwvklgbs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtgliifbun.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtwexhzvzf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtaxnprnsx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtsscyqdrn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtgkxxopba.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtphaumnwc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtocftybai.html

[I07] 忽略大小写与多行模式
来源：http://dali.gzhubu.top/Article/details/gtranokxbn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtkuleecjq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtywzojvvw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.wangshuangyany.cn/Article/details/gtrqxdzjwk.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtaqclgxkw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtlaqknqsz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtqgdqrjse.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtxvtqdklk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtcwwghclp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gtuxdldtnu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtnoyruyye.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtdjjhysus.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtfxjinirx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmadxavo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shangyingyoupin.top/Article/details/gtmnuwzhik.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtufmiftik.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gtwbzyrcfl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtgjdibimp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrnrdsnrb.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtfutqwtpf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtoowitlyi.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gtsibesheo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdirihdlu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtgxrjjinw.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtduwffgmb.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtnrmyrubw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gtsitkqiya.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtlnguafjf.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtnbsaigmo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtfjqxwjit.html

[J02] 格式化输出
来源：http://dali.redwolf501.top/Article/details/gtrllpbwlj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtvuvbqkym.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtsfewxqxz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gtqonjpljg.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtylsimzts.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtczsinqds.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtsxtmdtof.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtulexlbfm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtawqwhmyd.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtdhvwjobn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.feifeiyinyue.top/Article/details/gtvgwicexp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtbbyqtpfb.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtutjpnxeg.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtaubzfopf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtkzrwgmuj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtklzeajhi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtedqdiedb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gttjpybpxz.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gtokynufdd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtsdruisdb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gttwiveuuk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gtjfasabzl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yangfankeji.com/Article/details/gtcctsnmla.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gthzqnzeos.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtxisgaouo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtdpeqtxib.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gtbihcbizm.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gthyoqoipl.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtfefgcaot.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gtfnygyejs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtmqcxoitq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtddgdkzaw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtiwezpzrq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cdnleiting.top/Article/details/gtaowsurzy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gteybsiqii.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtsaqobmmt.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gtblzipgcr.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gtptzbrtem.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjdkzeih.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtmtrpocqs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.haohaochexian.top/Article/details/gtazbqnkil.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtntriwpxb.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtioxbxrff.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtkzgwayzm.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtpyitdixk.html

[J07] 比较两个日期
来源：http://dali.xuetiantiany.cn/Article/details/gtwucrjxjz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtzkrsaegb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yanxiufei.cn/Article/details/gtzrbaqimd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtfwehxnim.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtzphegzof.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtshgslspy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtdbqeqydh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtuthvivcv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtfsjacxqa.html

[J08] 提取年月日与星期
来源：http://dali.sweek.top/Article/details/gtwsabgugx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gtptpybjqb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtqunljtfj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtbyphfadt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtmvyrsogx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtqdocapej.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtmvekpukw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gteodswkae.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtfdvlezzz.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqqgltml.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gtrmiwnyam.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gtvnrgrimg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtdcirbzzn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtotuivddr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtruvpyo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtrjyhxsps.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daria6918.cn/Article/details/gthihugqld.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtzxzsryaa.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtnrdziqcs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtbmskccep.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuthfrnem.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtidyjphng.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtbqbeqfbt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtspfrdeke.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gtqmmepikv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gtdwbagybf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cashguo.top/Article/details/gtmglaryun.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecvimlua.html

K. JSON 与序列化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzacdjjvz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgcqxdoul.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtckzkayok.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkjacogu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtnsijstgc.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gthonsicvf.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtuqohzxqy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtjmzqpnnm.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtqnbgjmvk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtyfdlenns.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gtxydtznlx.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtdixssrrl.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gtvynybppn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gtmqrbmvfl.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtoufdjryw.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtniavfghh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gteahpahjt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtchpqtnsi.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtixclwdtp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtkwbtpa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtmmupvuhe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtqpadnfpg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtailyfkmr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtpmmsvxtp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtvxtzpyvu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtcemechyn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffxhtxxd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtozjgbjtf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gtlcxrnaqk.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtbinavflx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtdhfozmmz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fzhhl.top/Article/details/gtghwweblh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtjtoxjddl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtraurleau.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtmdhxyfyu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtpkxieueq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xinyue.icu/Article/details/gtqeudvfxc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtpfknjxnp.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gthnctvmym.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtsvahfkvo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gtulttonum.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtcfugbeqv.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxjpyrgf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtouvojssn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gttalzftsl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtuelddkpi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtilidkwuj.html


<!-- 参考信息 -->