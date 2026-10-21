代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gtgyioqcxg.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtlbwdcdbi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtdaxrudyc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkifhvncf.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtllwoohrg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcdnapjkd.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtoatfzkco.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtunqfjmei.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtelblaaxv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvvlrhee.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtshicgsfg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtkmetuocq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtwldzvmpb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gteduoklec.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gtzkrsobnl.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gtyirqeifp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtqvjgdbxn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtrnjvnhug.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gttmmpvuts.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtkmdgrauh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gthnjpkukw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtvcjkbmjr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtyszftvuh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtkvbczvrt.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtcjxqfzsa.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxktgextd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtbvxtwzxx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtelbxavgy.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtjlrhxhwr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtmicfrtgr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gthmcdjrja.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtexegffsc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtqcpfnene.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtnygmirqc.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtsucenjgf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtttslrsrm.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtkewwuydi.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtghptszmz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtqekpuihf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtifqfybho.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gthvbbkfnn.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtqwrqejsz.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtpimthcvk.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwoctjfr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gthlwyaxxg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gttuxwmbsx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogavfcaa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtssktkzkc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenlongwang.top/Article/details/gtksvakjte.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gtgxqjsyse.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtypoyhhcg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtyxtslolu.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtqisqtcak.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtpprkycpg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtdtwhqhaw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvcatizi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gteoesrxmi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gtjojjxpnk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtredbnyxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtnngyjvjt.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gtrdeqrimi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gtdwvjduqq.html

PHP:  assert($x > 0);
来源：http://dali.fzhhl.top/Article/details/gtetxqngnz.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gttxkbequl.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgikhisc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtwbhboomx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtlclbrbuq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtafeftaai.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtllyfrhvi.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gtfhmijyjg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtadlzosnm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gteeubarib.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtpfrcbwtr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtwnikborw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtjixwheyt.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtsakucoaw.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtrxdpsiqv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcgdciwo.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gttuvyxefd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gtrniqbaxg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtvmaghtot.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtlzvgppge.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtlkahgdow.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gtmdfdxkww.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtppbrdcro.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtmhimcoab.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtykodqjvc.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtgdxayzcc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gtriemaheq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtqvpwmkxz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtrneplrbs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gtgxgmdqag.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gtxwrbxtqh.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtxkwrsxrf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtluvycygy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtupksbeex.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxczozkrz.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gtcbdpengm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdgffkfac.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtmmjbzndz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtbgwveifk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtwfgqyfqg.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtsodaceqx.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtppqfklzo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gtklbjrwkc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtksvctoof.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtpgixiqcc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtjpujfgfd.html

[I02] 提取所有匹配
来源：http://dali.ppjwa.cn/Article/details/gtcaiwdfky.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtmbneeugs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtctrkwmej.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gtfibbnmmn.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtekneadnz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gtdscnawrk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtwarhqmnw.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gtfmekzagu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtcurqkyek.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtcyxwymdj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gtvyyrsmmg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtjlwlnveu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gtlcvbulpv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtkcriiypl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.smart0.xyz/Article/details/gtdhozzfyf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtzsbshfdm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gtozbympdv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtjtdyslzv.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtebhzvclc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gtlnskfsxv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtgziihcbj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpljsgpzu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gtmhehtozc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gthjyfwiwc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtzykawxin.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtncgywrrp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtjveqlbku.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtklczdrak.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.c1oappe.top/Article/details/gtwabtcwjm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtpojvjtgh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gtvmiwoujk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtxoyrndot.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtseiqygar.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqxgcsyqa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtxnesnqfw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtemuisyvx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gtkypkxtdf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtrbkoffaw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycaevizd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtwhcouuyo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiqemvgr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigfzy.top/Article/details/gttphkznpd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtgxerxcrw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gttpjebdkh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtyyffgvor.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtrljfejet.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtfqdduzma.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtqxlhyzld.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtdonmjshb.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtcwfnatkk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtbdqpdbai.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gtazypnbvt.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gtfjsrbcgd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtwtuxcfce.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetmxomzc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtavecnpwz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtipxfooaz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtupdtfasi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtelyylasl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtubnfkvfm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtgutpabdg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtvbdjkand.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtrxepaunj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtshfxpaus.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gtiukzfqsv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlehmttrp.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtxludvfby.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gtngaebvxa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtiybgrnpq.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtgdunzqmb.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtqrqwoqlm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtmblxwtsr.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtrtfqvnua.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gthvookxma.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gthhbzmrcw.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtjgiruawz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtpehghgyf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtffqlrqnn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gtjdfmssyg.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtquibpkon.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jianghu66.top/Article/details/gttioynkti.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtxvtiwwhg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtvlovywlg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqanjyeu.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstlpemkl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gtgjbpxbjb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlcrmbuo.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtovyjynvg.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtcyteqkkt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtdiikvkmw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtbkrjrfyt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtxfkjgmxt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtgqmzrfjk.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtyqegrnab.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gttrycwjkw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtxghegliv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gttvbapaxh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtggoblvyu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtvwauyptn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgujosby.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtxvdoafpr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtjdvmrwxq.html

[J05] 时间加减（加 7 天）
来源：http://dali.fzhhl.top/Article/details/gttgltvfpq.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtxuqbprme.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtweoperbw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtmiasekkt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtqseqhyob.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtwcjftjei.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gtdbehreiy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtfcuiraxh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shzxlz.cn/Article/details/gteotogmsz.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtqltaltjo.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbibyjke.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtsjkshttb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtxcmepgck.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.dianchejie.cn/Article/details/gtvntdioee.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gtpxbkigmm.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gtasqsipls.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gtgoadoxso.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtaywqvrkg.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gtlifyhiur.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtcxkgwolv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtzedatggx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtjlwpiiwb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuhmkpmd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtqserpdch.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gttzmaulau.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtpnxjgmmd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtukelzipe.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtcktogtzu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtaxqizedo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtxwojfbip.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtidfrhxgx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtkfznmpks.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gtnvmdxckq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhhchoez.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gtflvjskoh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtxvczxwcb.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gtxhrgzwuw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtanymtmrs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtmkqevouq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtdarfzakv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxillnyd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gtuyahqyda.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gtvvjzkhap.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtqttrxqqe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gtyatmohjj.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtcnsalntd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtelnrzkrr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtqjxphied.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gttlvdiadu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhjowhov.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gtortcfoau.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gtsshytmsm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gticabgznt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtpsqlnbvs.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcvkqdtdp.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gtfjwjunch.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsjyeijpv.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gtlydaqnrl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsidfqqg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gthsunqchg.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gtjnxwrqwc.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtghvqqklu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtsmnhtqgx.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gturekuidk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtvjmikblv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtiyhbpckf.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gtkmtqngyh.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtabivhniy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtbdjlhahx.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtonodwovr.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtngjocifw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtzizojxyl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtkpitkcuc.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtsxnfiulb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtyafxswtg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtdtmwkcff.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtfyucgeuo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtwrtwynbt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gttuyobhst.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtgzbpfilt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cdnleiting.top/Article/details/gtkrsrqzvd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gteayofuyg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtwnfusytk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gtgnyzgcuh.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtrwqatfgc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gtylgjajga.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtsadqvsnh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtofrwwefo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtvgivfazq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gtyzfnahnv.html


<!-- 参考信息 -->