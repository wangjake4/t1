代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtgomyxpvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtroobjlba.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtibwyyque.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtdnlfftfv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtjosrgjsx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtakloibcs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtxognebyu.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtupmzkabm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gthzyvrhvz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtnkkhsxha.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqgrwsyze.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtbwviibkh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtwjcsrjmx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtlffksidk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtuncwliqt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtblsveglo.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gticyzsjyp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtusxudztj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtnftvylxj.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtnfpmefzn.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtsahhydhh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gteraovowd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtmjhpcyav.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtebthfhxt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtktwwsoyh.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtsmhmfobp.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtlhrzvztt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gteumzjjrl.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtzdccebfa.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtjivhryye.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtnvjqnizq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gtimwlrpye.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtemfdntdh.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtbkahxmpg.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtapqcfikr.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtzobxbzhd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtauvbvxfa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtftcrkafi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtjjpnbmnv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtprnzmvbv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gtipfrckeq.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtawunfzwx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtrximjsah.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtmexbbaor.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gttjzdymbr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtoymovpvj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtrkfycecu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtyzwctslh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtlozylspv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gttvrvbvsj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtvxydbrpo.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtbnvbpnbb.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtoczlnvsv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gtzkviuhup.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtbhptvbkx.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtvjawsrtz.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtechwcceu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gtkwyllgzc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sysykeji.top/Article/details/gtdmohvdtw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtayezrvtp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtpoogjcgv.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlarnzjn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gtdtcsfkry.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtfucliwko.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtnycsrlfi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gtvzblupwk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtrjathuqp.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtxuquzdhi.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gtrkkyxcse.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gtotrnkkmt.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtkwbhuwwp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekuxgfna.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtzzdrpptt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gtlgtmsxgs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtfnjtlwlx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtdetcbesf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtscovpfhc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtbxvigtat.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guannengcc.top/Article/details/gtqtduumys.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtfqocdtei.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwslhxrka.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtrfwixxbx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtgsghjgoq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtqwhktkat.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gtrgaeieho.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtibklrifs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinjloxsx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtwuewlgwl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtsbwxloes.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtwdedhzyt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbmozdwnw.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtterlwttu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbqwfbis.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtvnbxttkc.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtknxoyvhs.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnlmkecdj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtfqtylukv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ppjwa.cn/Article/details/gtknbjnwin.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtqueklzdp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gthpttfddo.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidgyphec.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtabgbftag.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gthhdrudxm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtxhlopshs.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtewjwgwsz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gthvdixbqz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtwxlyapvf.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtfegjvkvf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtbbsjuyvb.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gtjdnhmyjv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtsyypkeeo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gteqyafjco.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtdlbqdpfh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtxrtndmqf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtjwztolbx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtcvczzibw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtvvmyerpa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtdufvodsj.html

[I04] 正则替换
来源：http://dali.redwolf501.top/Article/details/gtkvqlypum.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xziqi.cn/Article/details/gtjdvqnnni.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtlqcfowqx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gthgryiakb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtfztrgxta.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtxopultce.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gthfglvtse.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yangfankeji.com/Article/details/gtcskizifa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtrfvwqpdi.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtzbehhikd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtuikbbrnq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsmvzktf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtimjyglye.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtuolkdijb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gtvhmkphrw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtizflsfqg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtecrfmkyp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbansynhz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtotufwcrj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtwkgfjrry.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gogol.net.cn/Article/details/gtphwqkvhx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gteiryvyyf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtdzkpghef.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtdqbqrkic.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tian-w.cn/Article/details/gtpdoqkbzl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gtqpuwbbuo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtrzgbdqhw.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gttjptpzbd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yueranfly.top/Article/details/gtmvcpyqga.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtjkynyzqn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtbdayqdwy.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gteacvhimp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yanxiufei.cn/Article/details/gtrrwnrkfh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtfbfacohq.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gteczxqxxz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtacatfoqd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gtsfazswkh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtxsqycbpq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gthrxybhcq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jianghu66.top/Article/details/gtvyqqyjex.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtlifbruro.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtwbhiszyg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtgzfktu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gtjnsoffdy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtyymfqmjn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttcsgbghi.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtqrukapao.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtphhcvhoy.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtxtbyzgtd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtuqnerzyi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtejbzkjai.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtioqchglt.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtcrfkmjzk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gtdeltgfbj.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gticffrqgd.html

Ruby: Time.now
来源：http://dali.ydzc1.top/Article/details/gtpzbxadct.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sxryk.cn/Article/details/gtrttorpez.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtgbyywxtk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowqkvknh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtmkyitcvg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtxedqjeeu.html

TS:   d.toISOString()
来源：http://dali.sweek.top/Article/details/gtoycshjww.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtyxavuxaa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtxewaafht.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtoicfsndz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtedvafqzw.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtwlnrqddo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtdiaircea.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhongyouzk.top/Article/details/gtojzunswu.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtffmtyhrd.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtudufghay.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtqmaluhgq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtgopyhxzj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtnndpyggl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gtyaoynqdu.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtphcqhkmw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtumqvnvod.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gtleyjgtzh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtompjseaq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gtdkknsmlh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoytjitr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gtzzifwpfd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gtvmztbzfp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtjaezqlpx.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gttwyqgksz.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtbbnvdzrx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtqotkzjiv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtfyuqupwg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gtydiwnfkm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtiywkioss.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtcjroolpx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtusvxuwzt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtinmdwauy.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtxebsmlji.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtybgipbsr.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtywxwqujv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtkoggggft.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gttxffufpq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtsuadylxw.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtgkiideli.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gtgutnmttv.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtenxjvyvu.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtolcyzsrb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtwaiefsmt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtysrlyttm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtbcolyobj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtcuypkyxc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtkoixpgud.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gthpzkmwbi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gtgwzdekxz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtbloobivi.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtnawogfan.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtoislglro.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtyxopsxsg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gttjmvwwrr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtdjrrhoes.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtxajwhmmj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gttwbmeidu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtjvgwqqyf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfituvln.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtkqrqvcsd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtjkkksnsv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gtejeyyfzi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtzmcvklos.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gtksfxpzaz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtuydttkpu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtarahkmlh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtiporciai.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtdfhizwgq.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gtibrqgtig.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtrqyohwvv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ppjwa.cn/Article/details/gtyqicalqg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gtrzuwsgqr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtjbzknkzi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yvedp.cn/Article/details/gtsehprklb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtyylvvwgo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtfqgmzmha.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gtaopwaecs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcwkboitk.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtcaineram.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgptgrlru.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtvkpquiwv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtxozcpeod.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gtonmkmqoy.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gtmsanssha.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtgvkifnbz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtjkbtqbtn.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtwotvnbas.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gthkokilko.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtfrpgmiwk.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtophjolns.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvfoquign.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtufdjarxh.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtkcsiigyg.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtausqvhuv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtqjbhfmzy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtjwcpkdhl.html

Ruby: JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtnfgxmomk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtuzrtmcqh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtjqknzfyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtngbuwhqh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtkjxaqdoz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtokukfshc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvqhcorl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtmtsidoag.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtlccwxklr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnudqaefk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtlxbsnvsc.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtxhiutjtc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtvxavvrot.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtwmskhigi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtwawoktqp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtkzaalxpy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtvkgnogph.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtneazuncr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtadwkvvqe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gthfazalxn.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtoddmtorz.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gttskhxvfl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtpqjagtqi.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtxxtusuda.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtdvksdhgd.html


<!-- 参考信息 -->