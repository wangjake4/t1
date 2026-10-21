代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtibwrnqto.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtndswhyyb.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtstlmdgwp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtfpettqwy.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gtqbafjzly.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtcpnziuoe.html

TS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtsdcqieci.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtsvtebwff.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtybiowsqx.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gttmjnxniy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtodgeobtu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnhflmtch.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtlhhsqdif.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwdyqjngi.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtmoikkusn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtqusksahc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtocrrvlsp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtpdsoumkp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtgvpjiiya.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbdcdidz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gthciukgnn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtjeyqkbbe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtpnmxzver.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtmctrghdq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtnbfzvhci.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtagatcjui.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gthjbxvhxh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtacxqxede.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwncvpzhg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtfaarlnmb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtxalolbxv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtqwkzrkcv.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtcockggyv.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtkdtyxker.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtesfvanqw.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtnmhlvekw.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtvjuyogid.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqfqxyiz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtecxvarsv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtrdzmskjt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gteasmfgmn.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gtyfcopkzd.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtolhtjypj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtvszzbvvl.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtzgaygfav.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtvnquvurl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfqebmrt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtyylhkizg.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtyojfzlyj.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gteigihkpt.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqalrrkpe.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtmeookuvt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtlszixipk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gthmwtndwh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtztwjisih.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtikhhavnt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtwqagxvpm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtwphdextb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtqflwhhch.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtjfjtyysh.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtdxqngnrk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gttrwpuifk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtnpdiry.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gttxsbglce.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtvmhmembz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtbqftcswk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtgempbzhp.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtuqrwmlsk.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gtgjixxspx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gtcxoghwcg.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtlpvsebhh.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtdegvrrnd.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtnpdxwddh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gttnoibalo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtabprelno.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtgrfovdvw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtfcdrsyuo.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtvgigttqg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gthuutfses.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtekvhvitm.html

JS:   e.message;  e.stack
来源：http://dali.xinyue.icu/Article/details/gtocrkpdae.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtmcxvqsck.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtafbqdbgo.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtyfiigurj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gteyyinrmp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gtjzpromhi.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtsqrulgzs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtefalxkci.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtpeieppdx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gtwsrfrkef.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gttstlmusg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtumvgykeq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dashuyun.cn/Article/details/gtrhzstqkm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtktgroktu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtazytyxjm.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtarpkrhvv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xuetiantiany.cn/Article/details/gtkfnqajso.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtspxceyuv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtslinairt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gtcodwcuxu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtmughadse.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gtzgaqxqwc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gthijwjfyo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtxqlvjquv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtludsjxno.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtgvpwjwvu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjesjjvks.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtvbmkwnit.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtrmbzwtqu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gthwndpoct.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gtrpmcuumt.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrqcllcph.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shangyingyoupin.top/Article/details/gtmyzfqjsu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gtaxbxrmak.html

Ruby: s.match?(/\d+/)
来源：http://dali.dashuyun.cn/Article/details/gtlfepvszv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtckbliosu.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtpqadopwf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtqxowoloo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gtlgbwcymj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtjxddluay.html

TS:   s.match(/\d+/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtilmzibpq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gtfqgddujq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gthgdzexpu.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxezwlids.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxyldnxd.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gthaeodfjl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtmregrzaw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtnyrjwlcj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtegegzhrr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gttlylfopx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtuspefand.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gttwrwnpvx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtufsrfpmn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gtdnmblxui.html

[I04] 正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtkiwfarva.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtfirluurm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gtsdtproba.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtcuaewmnt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtocktbssb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtcdtsuacp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gteyccikys.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtbaekzvtd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtzrbvnjec.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtegrrjseg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yangfankeji.com/Article/details/gtjwbtlyay.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtaxllmepv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtimiplwbv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtexmpqxbz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtwudfcvmd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.fengsongda.top/Article/details/gthfwslnif.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtnhfkcnot.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtulpigtvc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtwvhdpuls.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtogjehsat.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtrkrqrbzv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtialewhao.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtztybibpk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdautnsqp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtjvdimcqi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtzdlvgarx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtsjtulrrf.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtwoaajjls.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gtuykeetow.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtqeqvkrdz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtysbulmkh.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gttyofdbjn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258888.top/Article/details/gtphmkcsvv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gtlozkctog.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtobcfsfci.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtnjehglrd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daxiang520.top/Article/details/gtmcrmhfgq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gtpmlujhtc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gthgesqbwj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtljpoagpr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtqpyikjqf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtauvouzfz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtkffqcsve.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtolasintd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gtmjaotomf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzckrgkw.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtvtygjukj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgkfjjbj.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtkjbtdblx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gtxakussop.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtthgunelz.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gtzsumqepf.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtpoegrtkw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtqgcjlhbb.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gthdwvtvjx.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtmanawwzk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zdqjudy.top/Article/details/gtmmsymwfg.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gtvedlqunk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gtuhqilsta.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtcqhucswq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gtufxrktnl.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtstektzpf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ppjwa.cn/Article/details/gtkgfkbxfx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtcpnggyeu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gtfdalrtgi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gthewzwznk.html

[J03] 字符串解析为日期
来源：http://dali.yonumen.top/Article/details/gtvscksntf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shangyingyoupin.top/Article/details/gtimkwqjxn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtaaxpkgrg.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gturgufsqh.html

TS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtrswomvlc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtthabuhyl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtoxxxoofn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtlbfuopaz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gttevrvzjy.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtxvwfczkt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtfeddbqev.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtishrkqfl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtcfqlbezt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gtocadeyrb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtzbqjwmpy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtmclzrhdo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtukbrycxb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtvuieblax.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gtrhbofmup.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gticetzzps.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtdwhmoryc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtyuqcajsg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gtvetobgbe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtbfadtlzd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gttsulpbnq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtcvsazwnr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtxsindtfq.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gtoypujanm.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gtnkldokca.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtutmbzkbk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gtbmevxgtc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtinrgvdik.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jiagoushi.top/Article/details/gtjqpppngq.html

Go:   end.Sub(start).Hours()
来源：http://dali.dianchejie.cn/Article/details/gtpmamnyhs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtavpvhupp.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtijtdezze.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtdwiazmgj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gthusqohim.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.svipenyu.cn/Article/details/gtklnoujbs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtaobqkbjl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtrbfalvha.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlnwamngn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtwcphfrqf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqapfrbrm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtobdlgldt.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gtbnewrgmy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtzxjxdxay.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.vqdsnc.cn/Article/details/gtsarzqoda.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuanzx.com/Article/details/gthzggqdgh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtymfhiryj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gtjgkbrsdp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtjqovzrgc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gtydgjmsvr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtcbmfsxfc.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gthefhxlkb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxjfnycy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shangyingyoupin.top/Article/details/gtlhpubvuj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtvorgcjcf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnagnget.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtmeppflzc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtrndtswbr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gtraatrwyt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtkzrmzika.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtgnyzhrrx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtdinwefoi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtuoyzhvqo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gtdehtaqel.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtgjtjsjeo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gtrqkpgyit.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnpwdivb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gtvxsbmppp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfanmznch.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfnuqvwei.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gtfxoblfbm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtehqyaypc.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gteqzkfvmf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtupneqfic.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtpzgdzmtq.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtduojdqvs.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtnjanpjyf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtsttqbbuk.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtiqgpbchm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gtfrjiivbi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gtyshbqcah.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gtjukkvuyb.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gtswloluap.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gtqgkcpmog.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtwlpiqgmi.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtrqhdsxpb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtfpaysgjw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtppikiciv.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtbbztzfvu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhengqikj.top/Article/details/gtvyvvzhtw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtunloonws.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtzgffylua.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtturmlyni.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtknfqhnpa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtwwqldayt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtjkkpjuzw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtevbtkrbg.html


<!-- 参考信息 -->