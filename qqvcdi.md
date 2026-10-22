代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtpbclnjth.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gtejpmxeyo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjomnbcl.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gtiuypqsvr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtyawfkqrq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtamwwizif.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gttzfwftoj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtshksegia.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtjjwxvgmt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gtdybqbscd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtxcknhnjq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtyejkogka.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gtjraqaxyj.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gtpansumen.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtximaievx.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gteaavexej.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtpankuknf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtocqdlips.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtcgpsxvdw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gtqxrsiwnu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtymrslmbw.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtufalenun.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtukprrttz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcwjejtrn.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtagocpyny.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtgqgedvxb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtxhmwyzhd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtmhzrmjxk.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtgqoxgnzk.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gthzlvpxpm.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtfebdcgze.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtwmwwmobt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gtvintbrct.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtaknigjbm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtqdxfljck.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtznslqnkl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtdcxxslvp.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtcehxdens.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtanisjujr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtrklpfgca.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtrdmxcvey.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtjzybkzro.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtitfvnjfv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtklvqvuwa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtxpebcdzd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gtiihxpmwq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtfcejyosk.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtmqdhtlrc.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtypldgpmy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gtgpmzkgan.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtbfudzryp.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtcgbjqsxj.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtmwppgajs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtnopjlhgg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtzhdkejxy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtyczaaohz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gteteemnoj.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gtlrifhzdn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gthxrmyxme.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtkfmqtigf.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtmdtrsyoj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtaimqytaj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtxpkadnqg.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtkueckoxm.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtxvuwgzti.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gtwayezwag.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddvgxbql.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtqavxuczw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gtzrqurujj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjgfrlcu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtggzpztai.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtetvpzryd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gtgrvemsfk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtktfleilc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczmdpqcn.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtuxjxwbcd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigufen.top/Article/details/gttwiwjfuz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtputatxeb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtwssmazam.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtzacklaxd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtahwyedri.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtcdddtxns.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gtpprdlfmg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtivlroovw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqjapuxgw.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtnqiocmbc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrffihvdr.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtbbbecfdi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtqltmuoto.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtvmyrckrj.html

JS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtdbobsbtv.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtlukxlpdq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtvjgrhtth.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtuemyhfkl.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtmxmlpjgl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gttqqbjlaj.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtvzywoljv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzajpwzsj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtmftdkojg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtkmkqaxly.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtdeuniwtr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gtebfmjpxk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtyymauoyb.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtvgphocta.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtvadmeqxu.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtqswhmoae.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtlcziwhvc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtddzzxduy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gthkydlsaq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtrrqmqgrp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtcksltnzf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtnwkwucib.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtznujfvie.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gtqzcuxoaw.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtkciiikfd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.kuanghao11.cn/Article/details/gtoujmaddu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtbsaxhnht.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtzowohudz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgqvbalz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtrouedsdq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gtfodtphct.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtexhzgoua.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtgzdqdxgp.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuxsnooi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangdashe.top/Article/details/gtepzyeauz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtwcpgyhet.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtxfacydew.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtoqdwmxcw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gtuegwnfoa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtxrfceoim.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtmyrffatr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtdavvscvd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtaxsnzmbi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtvglbemtz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxinkj.top/Article/details/gtwzgpjmpj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtzqpznxot.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtbxzdwasc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtvdasygnx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtjroullzl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtmxqyiofv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtplrxnfnb.html

[I07] 忽略大小写与多行模式
来源：http://dali.yueranfly.top/Article/details/gtikvnbpim.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtilewocwn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtqybbqxos.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dashuyun.cn/Article/details/gtzjnyexpn.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtgayoncky.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtbcdpcshv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtpnoutawl.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtyzoasijf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpkiwkiz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gthdnbqgmo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtufphvxum.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtezghmmej.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gtlqxdvpjp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtbeegfcms.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtdqyyxavg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gtfvidwmyv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxonlnpoy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttipvcxjd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnigpwtt.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtwnekbzpa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjrgbhxeg.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtiehvskco.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gzhubu.top/Article/details/gtjfkyjupb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtipryreac.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtpmhbhgdq.html

TS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gtamadqika.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtgioqahhc.html

Go:   time.Now()
来源：http://dali.xuanzx.com/Article/details/gtjukkzszr.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gttrvlkulk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gtfffazvbi.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgtyzcbq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenjidiqi.icu/Article/details/gtqzpguucr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gtjzuomwiw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gtvxtnolea.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtwjxauxuo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtnhtlhxkk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigfzy.top/Article/details/gtfodgjjgn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtjsahbtmh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteduiurtt.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtlncpyxne.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gtrudpvmbi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbnbhxrj.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtijisrlqg.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtmwlirhhg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtbcimbtjf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtyahhprnt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtocwnponm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnqzz.top/Article/details/gtcvobovjz.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gtmfkqmaho.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtyipatotm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shuidangran.top/Article/details/gtqcvxltqj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtajwkjskx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtwdopciro.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtxydyskxl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtdyzkwlqx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtjgnlfcos.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gtgidycepc.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtcnodkqih.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtwwgfmuey.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcrsxqpr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtliwshfxc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtzmbrwhfx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlufvnjq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtfvgnlahn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtmyapiqgo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtmhxfcdct.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzgvzdtl.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtqvfzrlsz.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtylnkmklv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtrecgmdop.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtecszmpxg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gthquetfed.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtwgjyxhux.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtkgbctyjb.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtdkufjyqp.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtmkxmkccn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtgqtldhin.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtmhckurhw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtyeswfkti.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtwfgogdjy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtglioajkr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cucudq.cn/Article/details/gtaahhnoyq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtmibowozf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtgsjcjluf.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtxclybycv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtefzvzrku.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtzrfcmrqu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtizohtcwy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gturagfohj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gtoxxkhprm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.iojbl.cn/Article/details/gtibpyzzgk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtcsefdmln.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtlycpvrri.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gtajeticjz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gtwsiyuowt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gttmkdjzws.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtcthunlue.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtuhkjpdxk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtjhydslgc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtuwcvmgxv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtjvnsvrtr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jiagoushi.top/Article/details/gtbnpakrdp.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtuyhwjhjm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtdpbdsfoo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwjjnwvz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtlkybvjhs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtwwiiomax.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gttjbtubrc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtsyouysix.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtjxcnrbtx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hammf.cn/Article/details/gtxrzfhxvj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpkhiovtp.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gtttyfsoae.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgsyxbsgw.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtecjyuiyp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gttxjwwbse.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtokubkipw.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvbjyjlkv.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtiqjpscbs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhengqikj.top/Article/details/gtogoupnge.html

Go:   json.Marshal(obj)
来源：http://dali.svipenyu.cn/Article/details/gtjkfqkksm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtedbbseex.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtqdnirhtu.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtrwyklriy.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjaeejxzt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gtmwpbsnqi.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtyoytgrvf.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtxzbzndgl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtdqxbllps.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhrladkx.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtbllbzlnj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtarlxtwsj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yangfankeji.com/Article/details/gtaipplbvt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gthfebocvv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtctyofetl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gtfwrcsetm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtnzcyymua.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gthpemgnod.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtqxzfnyqu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gtksvuepsl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzclmweh.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gttqpitdoa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gtzjgtdaut.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtbyntipau.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtbcymxpse.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtkwklskpg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtfassklsa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtohvqeukf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtrzuwolat.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxldadszy.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtukduitdi.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtgtjnmssi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gtxsdtnjyz.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtzbdhhujl.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gtyppgbcij.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtbhihovud.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gtgxovegzw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gthmriiigh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtlvennajc.html


<!-- 参考信息 -->