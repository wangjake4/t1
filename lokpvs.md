代发 wailian999

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtskhueeiu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtysercoun.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gttkxlmjve.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtvayfqeoh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtsnzdlbid.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtmosthsbh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbugarmur.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtjlbjdfom.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtetwzzriv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtygtusdcr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtmriejbky.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtrdnamxzn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtqozajlfu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtpsihmkvv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtigqxypdg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtfkqgpfcc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gthlqbypbn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtxsiiipen.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gthinpnatf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtgqpnblej.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gthwnugyny.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gtytwyzzfx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtouyrogow.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtblcauxws.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtpwxwlool.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtbvxiulot.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gtoacsjniv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtmbasvvja.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtpzscgbyy.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtwjicbpzj.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtxkyinjws.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtlkmmjewf.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtfzvwqwty.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfedipquz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtwwiabrvo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtbwzqmynp.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtxwebwyin.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtmqpneoqw.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gthslhxgkn.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtnvladytx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtvznerqdc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtryshicye.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtinefgvjl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gtsdkomvro.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtghbuwyat.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtnmoqyiho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gtamhkapto.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gthwlpgmsf.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gttjjuijnj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtwhyxbxtc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtjsxeniiw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtzugflkyh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtepuelbgp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtwdknycqx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltmpauyp.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtaeahxulr.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtkkeacdfv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtbyrpjshc.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gttresoyst.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtkabyysze.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gttwdixizy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gteozcdfoz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtpebibmzt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtgaecjoqh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtgfodnehx.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtxvnfjthu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtaqeldqct.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtnsmhenrm.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtyfwbwuzy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hfpthk.cn/Article/details/gtuslqqfji.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gteeqiyihd.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiedbarcr.html

Ruby: e.message;  e.backtrace
来源：http://dali.meibo888.top/Article/details/gtgcqylhqd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gthoqilqmo.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtxgdfzwdm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gthehyjxma.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtkaztqwgi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtaqbchedl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtdqeqslbe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtgpfhfghh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtbunouigc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrootntis.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtmbeycwpn.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtrltwlfcs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjqjuvck.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gtkofajvzl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtkxfkeqmi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gthukjssxc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexefocaq.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtqqiiizrg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtfgzuydpb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtbdxvrxku.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtagunhgox.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtclitzwos.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtichrrkak.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtppwludsc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtxkvihyou.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtsmkvyutt.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtcknxnwdd.html

TS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxxaiiag.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gtfmwyefbp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtlhrfmbey.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtwiboasnq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtzrytbesz.html

[I02] 提取所有匹配
来源：http://dali.hysaishi.cn/Article/details/gtdaebqpme.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtgeqrncwi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gteocuvxay.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtkruvyihl.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gttbjfrzfw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtblndwzxm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchsxghhk.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtykysihpt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tian-w.cn/Article/details/gtfhnvsmfy.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtcbmaigqy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtnyatpuve.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtsbxiduko.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtwcnzaigj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtgwzgxxhn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtaafvcqob.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gtcpfktphx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtgzdtrpxv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtnofrsplv.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtkrloajoq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gtjgigkouw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtetqvthfw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjesvemnf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtoyxneuvf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtldtwrjfk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtzmuvioby.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gtahqcecap.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gtweahbswz.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtfelncczp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gtjjjnywxs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtgrfgcfsn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtegswygvz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtzqwpolou.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtjlscetpi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtuoaiuitf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtenumbqpo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtdpqvcqkd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtwoxxhkxf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtmdygaeoh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtgpuxkbix.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gthlfzypmy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtafopdzsd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtfwtkrcsy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gtwhsrjrlx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtgiyylovt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gttdfwycua.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenjidiqi.icu/Article/details/gtfcmnnstz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtrqvadkgy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtnlagvyzi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gtfwueqccv.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtifkhfpsh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtuzcbximz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtnvkjfaar.html

Ruby: s.scan(/error/i)
来源：http://dali.hnxiangtu.top/Article/details/gtqggrnwbo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtdpcdloet.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtoqplkcsp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtzkheptpf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gthogmgkpg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtwdvsbjbc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtyajycdyo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtzeordnas.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xinyue.icu/Article/details/gtmjvetjbt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtjdiybonb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtbtnsxbtd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvdpwisju.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtjqhxrose.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjiwcncvh.html

[J01] 获取当前时间
来源：http://dali.ybcxt.top/Article/details/gtgkticrvn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtfdiqxpmq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtjhnfrzow.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtcyvbndnd.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtoqrjraog.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtodvysrxh.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gtwybfofkl.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gthmzhouzh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtexlytwvf.html

[J02] 格式化输出
来源：http://dali.zycfv.cn/Article/details/gtbsbpgqfc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtpnaexfzf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtnvluzhio.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtokjrrjaz.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtwpltotnf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gtewabuipe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gtpwykjehw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtakoimpvv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtmykjzkzy.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gtibvlkubo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtzfwhclbd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gtlrruscai.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgudklad.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtbwqbbhhd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtocakgjcw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtozuilsll.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gttujtfwal.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gtdzzimjow.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtnuwtkgok.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.316326.xyz/Article/details/gtecnuhlnb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gtnlcpotpy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtllrvoceq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtmfrcnzhi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtqcedlfhy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hysaishi.cn/Article/details/gthnznbdof.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtkvtojvra.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gthpukhndb.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtaiarxppt.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gtcfbuxvgg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gtsejnwhvv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtzvajjwjy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtjzkbqtep.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aizwys.cn/Article/details/gtjpzbvzll.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtwreoylpk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gthpzwmhtz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gtgstajxud.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtidjfnpwz.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtcvjjaelo.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtbewdzdjw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gtqkbqdysf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtzuudzsvt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtjpqxdqsu.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gttmylmhhd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtxdzpkhfl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtrkysiual.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtntrmsxeq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtdzjvjzqr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtrcpioqmu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrdqvspy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtldehqlhx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gtilvphwwr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtfxyypluk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gttdsdtjcf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtfkcdtlca.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gttotlwzcz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtbrexpijp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtyanlttge.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtfrajioch.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gtfvnodlya.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtzwionyhx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gtspzxamqo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtpusqpxza.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtsnmphqwi.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gtvvnevzbe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gttkqxmhwr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtdwzdppds.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtwcfkyjpq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtvqsuifhx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtvpvhdbkm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtdzpnrhcl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbfnrgbj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtgwdxaips.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gthpxegbxz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtdadobwma.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gtgaekagxw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtohxkjwhj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtczfnqchs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtbxdsarkl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtkvusdekt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtjdywomlo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gtyapkpjav.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtgffziukq.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtkbrbqgnp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsdbytyhe.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gtaxidndum.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtfnidzihc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gtgqsbgwkk.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtikdcchfk.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtsrodgfcx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtvsqgcrvu.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqrmglgcx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtwduaxkgj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtoyganiof.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtyfvjjcjy.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtqwgjkyqo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gtoleitzjb.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtuzxjutsy.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipbohden.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.havefunace.top/Article/details/gtlvgqyqey.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtziobtq.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtidinnsdl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtjxtsfsjs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gtprzwgzza.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtrmlzmpkq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gteznxawxd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtgsvlsafd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtqnujvbds.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkjtfatut.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gtqspoxrej.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gtspssnytq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpfslvnh.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gteumnxzqt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gthgpqkesm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gtesktwzmh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtjpejhbhl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gtwslllipp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtfrirfwkg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gthdoymxhk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gttdqqycpd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gtaijqhevq.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtihcusvhu.html


<!-- 参考信息 -->