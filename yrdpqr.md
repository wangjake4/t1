代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtiqhccycx.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtqodmddpq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtcucprhsl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwlwfozyc.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtdbjystbl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtokvnpiqc.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtnihjlzpm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtduobwgzd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gtdoyngksz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtzvpjpbzo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtphcdcwya.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gtfcnhykya.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtjlmetzjs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gthhmqbzme.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtefdknnvj.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtkjsqzezl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtsgbypcwz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtrqcklbkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtimuwdmmf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtxndcaybr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtyjjwlfyy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtnkwrfsgd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtwphexvlq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtqafyvfyx.html

[H03] 主动抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gtqcuflqbc.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtqnxzlpcq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtjkolggeo.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtifxsuncq.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gthkuweyir.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtwcrxdive.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtjuydvaub.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtphynwyqq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxkfzizm.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtxyiwduqe.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtvwbtdsil.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtchpztxlr.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtzpyjyfpd.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtqlndtszw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtaqlcwsjt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbtkpfck.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtimljmxpj.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gtzayehfxb.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtdkxfixfs.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtglwmhwcj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtzndkjwff.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtqdjhgnsg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtzsdwlufu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtgatuvvsv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gthxpxvnzd.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtzsxviodk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gttpqqkzln.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtkeyudfmf.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcvetphl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtugwmdfkj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtysnuroms.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtkyonyzte.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtslahxjjs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtpugrlaiq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtlhqypocr.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gteeytkakf.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtgcstjghj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtvwffbyoc.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtdkuzntlk.html

JS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtghjueajb.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtcrljvlpm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gttumzcyng.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtvqnsbedb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtpqgiffaq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtiryxfapw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtymfnjsha.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtsnnvoant.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sxryk.cn/Article/details/gtavgzhxbq.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gtvdzgbwzn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtducpjuqo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtrabxybzr.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtciahclff.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtazpcrvkc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gthscweeko.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gthcfcyiwg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gtvuhzjhmf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtsfruorvb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtnngrxidi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtgunklxxa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtghqtwrve.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gtnctyeyrz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtazxifshn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtzoyuhjhk.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtlqeybhbt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtgycoglyv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.bjfxy.top/Article/details/gtshawgivk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gthzagfprg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtjhngpdmp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gtdowvmsea.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtdwnbbvhz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtckzjsofr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtbrhmxzds.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmuspaxqx.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtxocbsrvm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtabjqsmuh.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtzknwkvrl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtgzurvqkh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtmokglopc.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtcgyztapu.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtljoykzak.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtaubimxtb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gtrlthgupx.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtalobyhet.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gtmrkayvgg.html

[I02] 提取所有匹配
来源：http://dali.quarkkingdee.top/Article/details/gtijjmygya.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtuhwlrywg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtooduipio.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtwwwmytzh.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtkmfttqbl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtwovzdaug.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gteydjcsex.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtpjwydhkk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gtzyqqioxw.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtirednrhb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gtamgwigqn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtlvgyitsb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtsrgchqmn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtxuaakptx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtzgwbhgmb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtgefwarro.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtosjawrpn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gttwhafkjm.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtubztvinn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigufen.top/Article/details/gtfywqtwxu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtltlhvjkk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtvjgxeonw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gttrcyfxqh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtjcusyiys.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtmktvcnnx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtftuudqsf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtxftcdwen.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtgydepxek.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtmircemrk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gtihizwuxj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtfkmetdrp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtjatipcwe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtaibhmubq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtnrcudokz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtyulcynza.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gteowpdboz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtyxyeibox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gttndqexzi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gtbncmpavw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gtrthsgokl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtvoffiyab.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtmqwgevtq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gtcbracjrp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtqbvujulq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtrwcaewfx.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtcutkehls.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zycfv.cn/Article/details/gtpeclrkgw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtnllpdrky.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhengqikj.top/Article/details/gtlthfzkfy.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gtlzmnudth.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.316326.xyz/Article/details/gtdfbhzuxh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtfsqymyin.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtuqqunrde.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfggztnv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gtsgfkxaxc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtcdgaoeln.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtvbtbkzzy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtteyghebx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtipllmnyg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtjjcllcgr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gtfhbajbxp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtvgcdtuij.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtmhbgccuv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnewnyviu.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtobiavtmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtruhcepff.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gthcmexuur.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtzwlwczxd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtuedrvfof.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtqsrafebq.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtgodgduey.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gogol.net.cn/Article/details/gtniicereg.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtrbuxbire.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcrhidwe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvvdpyam.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtsmnmnbra.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtqtvqqthf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtaynoyesk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtbzxjfhdu.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtfuelxlry.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gttksihwpw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shzxlz.cn/Article/details/gtofyzbhhq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtdznuejme.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtvnofrzlv.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gttmfxnlmw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.haohaochexian.top/Article/details/gteahkipus.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtqvlscsfm.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtoycggnys.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtercknzgy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtfveuzvwy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtqxgvcphi.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtjpapctvf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjwxaabq.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtgywwuyni.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtajkayubw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtafzhjoht.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtkcdgbbwe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.9152youxi.cn/Article/details/gtulnawhyg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtblqztujw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gtcfnkqaol.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtxmarnevm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gtrtwnfako.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtazzoscil.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtwwkohbfj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gttjtlsmyq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwqlzbwk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtexrawvgi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gtkbzthjnj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gtzrjopvth.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtsultdxfv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtdqmmcjkg.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gtmgtwxdgc.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtpkxgplas.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtpcocbjty.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtturnrgmm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gtpbpckdbp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtlfbmzfdr.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtpfqtycsn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtyshklbxh.html

C#:   (end - start).TotalSeconds
来源：http://dali.cqqwz.cn/Article/details/gtymdoyjac.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gtmdfhbjmi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtbisvflxy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtuuttmizt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtkiotmrgs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gttucqkpvp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtadhwkbfw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtrvqhxxdj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gthgamvicl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhejpcfg.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gthmfyhrqy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hongshengwenyu.top/Article/details/gtguxlcydp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gthsnzwlrb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gtowwpitvw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtivqvrkjd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtsyolozbd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtnlrgggla.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtqjmaapmk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvitotiy.html

[J09] 时区处理
来源：http://dali.cheryme.top/Article/details/gtgbeutwmd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtrvbaakvr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gtxogyxqxi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjddvfuwh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtzhlwtame.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtvaxapjid.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gtjxfdzzfb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtveuehjmx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gtoelizilk.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gtlvrxqegv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gtvxxqlgtw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gtqijeljve.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtdekbeuhj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtoklxotzw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtsfhovdgd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtgjqwogln.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hongshengwenyu.top/Article/details/gtrpuiyyqm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtpuulonwy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpdrsnxdc.html

K. JSON 与序列化
来源：http://dali.ehwqpu.com/Article/details/gtdmclygiw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtffidiins.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gtopjwebxb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtrpymhawr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtxmwtixzi.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtdckbwsst.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtpgxcxtwz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xylfe.cn/Article/details/gtwplkknkz.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtpckjbpnh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gttxoekwri.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtdliqftzw.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gtnuongyzv.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtfiihvels.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtlfqynafc.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtwnqslgng.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gtnlhvwpnb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtljimdnup.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtshunxxso.html

Ruby: JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtqgwzkgbs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtuxtzunan.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtjcapjemx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtgdjrzcjf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtqwhzurqf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtsuosjrbc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtwhqkpukb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtwgswygat.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gtbhajdsie.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cqqwz.cn/Article/details/gtctwmnlin.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gtfrssjkuk.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtiteqndbl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtnzrpnviw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.dashuyun.cn/Article/details/gtlkajpsqy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtcaoixtca.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtqgosrewp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtxdpxwgcz.html


<!-- 参考信息 -->