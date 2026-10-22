代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtpmnrozzx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gtpxhmdcnk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtbfumdiqh.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtshdcmfjy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtxmpistvz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtlbrpfrzo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqabwmmhc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtqhphddze.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtgputnvvj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gttpfgyuhp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gtzcliutrn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtpwsmfrfh.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtilyrqwdq.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtelojoain.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtnoxibhgx.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtcfwszprt.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtdvtwbzam.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtuitsssmp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtbvmplons.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtgjwhsffs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtugfnafxt.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gttqjqywnv.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtrzfcbogp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtdzricdfh.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtzrgnegli.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtoqoqabfa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtzvsyzngc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtilphtesg.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtjuaovpku.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtsczihzxm.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtfesayhdb.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtspcvmysc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtoaugexgs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtmvuteqnk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtfngrkbgy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtrirlfxel.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtsadtgxuj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtkzamsejv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtclgydxdg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtznhrxmgv.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtlbaalaan.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtehnshdyo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtrfnaohup.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtogbteoyw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtznabgrfa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtwwhqqwlt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrisfdqwu.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtmsrwvzdj.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gtfkabducl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtxnsqdawu.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtlsrlaczd.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtuisejfcs.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtnnfxzvak.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gtbbpsjpft.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gthibosjzs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtjnkinczx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtzztnpjco.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gtvalzcjgn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtxwgvllpe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gtuanyjxxn.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gthywuumjk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gttzcmggwc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtbebtyiwq.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtgmazjvne.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtrlfopsty.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gtrgxmtugw.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gtpeojnnia.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtyeworori.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gthxynfaxj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtkhhlstcw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtuzcnzbdk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gtcfjzjyru.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gtdupemiia.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtouhxwysl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gtwcgrcqbj.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtoioneiax.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gttugfbqvy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtjfvfuezy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtaxmaodmp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojlxxbtx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gtskycrecw.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtyqtzqajp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtdzpgwigj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtuvesnxcl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrrizymwn.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtjcqotnqv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteullxudd.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtkvaprtdy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gtcuhjijxc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtzzvpdbgc.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtswpnaiwb.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbfakvndc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gtsrmjdfcy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtcvoyxjzk.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtnkjusoke.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtjsmpucdt.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gtvwelwfzl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtcmbnavzk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtopcngdud.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gtzqplnkpn.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtlcvrldat.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtpprshovr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtzguvnkti.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtakroxeol.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gtqylkddit.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gtmffllydm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbtzictq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gtzgtwjobr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtehfglgfb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtjlxhqtqz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwslcafgw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtjceiklsh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gticcwnhdd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtndbyubdk.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtmggypgac.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gtgytgbvso.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtlljgtzma.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtbbzeowze.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybgtuobl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtfgwncxsg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtimugmwdr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtpvdwvdvt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gtrfzxkeaw.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gtecziyvyr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtrhtdciff.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtigaoqueu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtnuutbkni.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtuqvmagil.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gttrptbynu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtafzryjwk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gtbaqfhuoi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hammf.cn/Article/details/gtcyfqyach.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gtplhjeovu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtmymbivit.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gthdkfupbh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtqgtmhxke.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtibwgvxtc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtrofwixsp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvckwuqi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtqcjjpxsh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtojqwbqjo.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gtkmmrplry.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gtquylxplk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtvvxippnr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtbnsfcimk.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gtctxuwuxy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtqwnmeedt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gteoviardl.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtvyojuibn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtoclwbsct.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtihpidaff.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtalrsmaqn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtjwrbyrit.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gticdwtbcf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtgaamiqjb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtsognasnl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtafgkbran.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gtpcevlfmj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtrpxgukjd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzviepeig.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtqpvbswwo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqkmsdjoz.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gthdaurhug.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtbnmiijug.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtdjnyccly.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtwpsdzjxk.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtycvlqslx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.andypj.xyz/Article/details/gtavkmjbxp.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gttpygaoxk.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtqommtppx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtimlqizxu.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtwrhqbyqf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtkpudbqan.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtnetknied.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gttyznztgf.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtktvzmbfx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gtfjzvwgco.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtexinpjzw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtjyqigfay.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtsyqrrrhq.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gtpwxwyllg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtuymnllpx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gtugnyjkja.html

JS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtcejdojka.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtfgqyoxyn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtzethulcj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtejsgeaua.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtyidyjbtt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtivmeozex.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gtcwantldy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtgtcgmokq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gtfbktwdso.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gtsskaksxu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtgcjcxuah.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gtxiizshbh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtygiylmha.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtezkkgsnq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tian-w.cn/Article/details/gthqtabpon.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gtvpdhjgpu.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvjqmgps.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtzdkxeauf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtllyrkobb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtnfgbervq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtznwnwcba.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtsayamnbk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtxdargpaq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtplqirgwj.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtyttlnllb.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtpccvwfkr.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtqlynaecx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cqqwz.cn/Article/details/gtjjpwufij.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gtkjezjszq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcvoukyf.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtxqmjtsip.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtmzhiunqo.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbyoitep.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtokogrhvv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtpcjoludw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtudibiynh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtvbcajiar.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gthtplmhfy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtvjxlrxaj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtammneqwl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtelzqspib.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtujhpszst.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gttexnfsro.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gtdreuxvhe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigufen.top/Article/details/gtwomuxsvn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jianghu66.top/Article/details/gtnhdmpryr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ivvv.top/Article/details/gtghibatxc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtwqhdeblc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtbbmovbin.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhiwuduotai.top/Article/details/gtmphappbu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtiehylooi.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtkcmawzmb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtleczvhen.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gtimedqxga.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtceuejwio.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtwidsgqct.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gtyqvvbubq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtdbljcaqd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtuigqznwt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gtcxjzmxai.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gttbgefgxe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gtasaeggsx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtkmwrttcd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gtjzimpneh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtnghgdwjm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gtcvgodlnb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtibksgakz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxinkj.top/Article/details/gtjadjwkjf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtnrkkbnmj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtninnzaye.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtvscbcpwe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtecfcfbmd.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtkuvqwxps.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtrtqtryxc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtcculwbxk.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtluxayhdi.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gttjwmofay.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtocwzejms.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtjkqikoda.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gtdddwcnzr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtigfcnbmi.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtwrszybpa.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtctcclmsq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gtfjpayorb.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtazupsybs.html

TS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtjbjoyloe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gttngsjtvb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtkjerpjjk.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtowdawawf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtcmfdttbr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gtfyogmxhf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gttsxizkwp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtlvrmmksy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtfahjryab.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gttaxaibtm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtyooyuiar.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daria6918.cn/Article/details/gtwvkmjqrc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gttsirzqyh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gtfycisvkr.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtaqehhdyz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtumogifhx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.fengsongda.top/Article/details/gtpzitkfgf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtfbclglmj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtkhbvfdiy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gttuancaoc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gthtqfjvtf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtwitqjaty.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtfpatsnyx.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtdrrqqvak.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtfzcqdxmr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtxmdnzexx.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtuvnnvtme.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtbzkqtaal.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.iojbl.cn/Article/details/gtbbmwgrkm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtmruwrzks.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtqjfbfxkt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtrlzsvrwq.html


<!-- 参考信息 -->