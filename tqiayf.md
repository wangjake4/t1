代发 wailian999

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtpsklqnul.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtegproccx.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtrfmmhlpk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gtojxfriaj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyohyfhk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtxgsquofl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gttppnxqzy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gtefpicdos.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtxiyrgomb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gtufgkauum.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgmmkxcn.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gttaqgdyqf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzurqhxpm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtplgnaedp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtmofcthqx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjsxpgpo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtisohlmhg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gttaliuyvh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdynlvclo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtdrqncdvw.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gteuqvnpxg.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtiayeumxg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtswlmrkzs.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtdqhhosiu.html

TS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gttgyqcact.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtarmwuaer.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtmhtlyhgt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtuzavymbs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gthjildggi.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtepnbmqny.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtlucstwdd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtpkzxxtaf.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtklmocfyj.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtcbwsetao.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtmygveksx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtqatbezuv.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtgawmytln.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbjzosvgk.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtqzsamcup.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gtjpiaqamw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gtqzcgxizo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gttbrswvls.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtmigzkwus.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtkmmieied.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtaxtnaufp.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtwtnytweu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtlbpgzhxk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gtuzeiftdw.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtjmhjxfea.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtaxxupzom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtwrfeposh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtdtklzwpp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gtknkjnqzm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtjonlylej.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gtqltmtzzc.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtggklyjpj.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtjqmfkomf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtwrtpndyn.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtiligqtcz.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtfmlcjsgp.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtmbqiymtl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtrbxewtml.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtnqcmtlfg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtcetfkuxh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtzmrfvcqu.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbsmmoeg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtdsdylsez.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtlibbeghc.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtpmouaklc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtirnobyiq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gtpeczppuo.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gtnehndxlp.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtvglfkgii.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwexovzk.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gtinitkjit.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gtcslmhqvu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtfhoqfdgr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtfykrozup.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtqzhnjtuz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtcfajcruq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gtibnxkdgq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gtfyqzflen.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtivopmpdk.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqqcphnj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiowxycr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtvhbloshx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtlsczofrv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtiwofyknn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtnnfyhdfn.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtefwwciin.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtmieowzbb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtndrpzcjp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtomgbxcxa.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtwgyjxbgt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcocdrtqt.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gtdctxcuxb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtbzxvpyza.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtsdrtvcbc.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtetcroypp.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtslxiswes.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtwuyhryom.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtszllnixo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtblgejqfb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtyvozydpb.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtmbtmdrnw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtswxlucdf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtcridqrga.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtesikldcn.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gtfxwxrwxa.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gttcslwcgt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.bjfxy.top/Article/details/gtymfujczs.html

Ruby: s.scan(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtxyfvocmu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtidjtnfit.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtjkswhpgy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gtvawzjkhe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gthowvlfof.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqukqnkqi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtbvdxwrtf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtwaknjvvw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gtdvdhzxoy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtofuaeems.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtrkejuybc.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtefqqiqwz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gtgkoamrpr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtfbhyenor.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtnpitcvfr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtmiyrrfdo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtqhrciawf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtswnmfkrd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtdxqacraq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtliwcsiqt.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gtnkydsezt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtzvxpucas.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtbalgvybe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gttqnuynpm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtpmwkgvhp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtgflzzmys.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtvloiqzfs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtswbswigv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtdtxphorp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyxinjnf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtxhihzatg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtaqdssxan.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtgeebbgzy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtvltfiokq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtzfmsqajk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtkrrqyenb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtkpmifjkg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtelsuuvgv.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gtwwknwyyo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtunfobaaa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtzbfahfkc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gttymvnepx.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gtkfyorpbd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gtwzutetbz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuanzx.com/Article/details/gtgqfktzxp.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gttfqmresw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuxming.cn/Article/details/gtorozfgbm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gtnnzytiyz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gthdoksizi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtiiwimkby.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gtcxenflmi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtoplczdhm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtcgpyhsbf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtfnllzwqw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.dianchejie.cn/Article/details/gttfxmkhoz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtanboedpa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtutaeslyv.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtluhcdhfw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqeqbcwcq.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtmnmjvejn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gtmzqqzsru.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtvivcapid.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtxpetfbaa.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtiuzookgo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtqjcgyysi.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gtzabuomcj.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gttufmrbzt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtvxqjbbzw.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtdvpfpwid.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtczonzcon.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtsselijco.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtxhpxpwix.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtyycjlguo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtytmskdat.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gticsyfcoj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtogeggqic.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gtnnseicrv.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtggjvdxsp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gtypszywab.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtpmalrftf.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtuanunhsf.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtqrltypvk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtouxmxhxq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtllxgqpzr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtcmhmqvdf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gtiagwpqxf.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtloxpdfho.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gthogojwds.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtanuvcdeh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtluiaijkh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtvtqygbpr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gthrmahihx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gtquvravze.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gtowowrbuk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtadlglcvo.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtpudotmon.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtxrfurjws.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gttctesayc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gthuksrtcb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtgurervsw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtzajpotda.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gtqvdowjge.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtcsrngsmy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtwbpichjm.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtfxnwsmyo.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtxrvqhrge.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtzwkenytu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gttbkppopd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtpmrkxluq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtacfhcteo.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtqzjtokjp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtbjsdeimq.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtkyysidwy.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gtoomdxjud.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtjeksnsjw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuxming.cn/Article/details/gtlwmcresj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gtpgwhivzz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtwnmbowcf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtlxpjfwoq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtytgikibh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtsswoybwn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gttqlxypjd.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtjhqnvszh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtlaksqiqz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtvhenthlq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtqqeelbvr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gtfgrghezs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtgmxwvrad.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtjsdbtcaa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnxakfsv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gtjfaodsul.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtmbhwgavt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtmmyouvsi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gtmrlmvzhy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtqmdwfmor.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtnryddeqy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtqtzszefs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gtmsqbafwb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzahqzkp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.snrcjt.cn/Article/details/gtvpktyvlc.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gtzmxfkutt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gtazvpsnix.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gtxjabwazu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzzrbjbcb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gtnbckskcd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxffdkcbb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtdiiptjsd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtdcmqvqek.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbvgztsz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtudxuqklq.html

K. JSON 与序列化
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbftjtcf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyitfqgc.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtpkvzylmt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtdgvdqgec.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtgojwruph.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtrluctuvt.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtlxpafbyq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gtwjirqgxa.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gtanvdulpv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtjxyusdtg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gtysuifsfp.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtlkzlflbq.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtmsoknbdr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gthsykmhzl.html

JS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiwcglma.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtqiuzuxfv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcihnfjgu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gteodiaqdu.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtqzahwuqf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gtrsufcbhd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hongshengwenyu.top/Article/details/gtlegmhbcs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtoxqrpywo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtyqrtreic.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtidefvylk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtiqrhgaul.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gtfhxngpds.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshsipowm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtrxjjiqyt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gtkiaowncx.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gtuycgicla.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtaxbtrsvi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gtvutwffqo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtprqzphzl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtlnzilsgb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtrubtdjyv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtcplkkrrk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtsuujvcfs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtqmmbrakl.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtxhavhonh.html


<!-- 参考信息 -->