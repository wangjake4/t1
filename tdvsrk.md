代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jriqkhwp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2zghxbarz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2dnjyklew.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gt2sdglrsus.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2rizkmtpo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gt2pjzejxbo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gt2abfivoft.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gt2zorclhbn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gt2mpmhbean.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2npsobqxi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2ricsmtbi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2njiiplle.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2mdiocvpo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gt2djxmriwy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2rtkbkuys.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ekqyqqgv.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gt2nvngjajf.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2cwjtjkar.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2bnupwevn.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2vqjzprpk.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2mrpljude.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpwjgtu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gt2peaoncgk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gt2jwcpyzjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2gxxdopnh.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2cdysgxqd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdyuovvh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2kpomwwls.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2oesrsshq.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2fatsjrhy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2bbggzhaj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gt2jlnodlup.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gt2bifctbix.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gt2sqequnud.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2lclozclw.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gt2jqkfwniq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2jvapuypf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2njgbidcf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2ggnvrzbo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qnpwbmya.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gt2mbhrphhk.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gt2svenavdd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xexhpopg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2ilnffexv.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gt2sxailtmk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aozttcxl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2yvujwocx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2cjkcvcab.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhqfsfe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2cqpxsknh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2zbqbhuay.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxdubojo.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gt2biqcvjls.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gt2ukfyxxkv.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2qyvnosnh.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2gwqwppum.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2bbrutnei.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gt2nppxyhje.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gt2lfpsrizp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2ljbemfnz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2kwdrrtoi.html

[H08] 获取错误信息与堆栈
来源：http://dali.birdmap.top/Article/details/gt2asxjbtwt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gt2blvjfzne.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2viddxvuk.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gt2yzrhinvz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gt2uquzkttb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2zftmstbz.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2vbvfgfuq.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2iqwxbggc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2eukanufi.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2hyignujq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gt2rzgfeeys.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gt2kxuaosfu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gt2suvqyqra.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gt2wfukvuij.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2gzffyzte.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gt2rxtywpkh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.0kj1m.cn/Article/details/gt2jiwsrttw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2gpccrnhc.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2yzfvigxs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gt2zgirgulj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xerygffy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2sgdublzo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2znmxmaby.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gt2ruiiadcv.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gt2ymjcslao.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gt2znlvhrii.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2ddpjgget.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfgkyrfs.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2htnajjve.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2jckjveeu.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2tzfwnlzl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngfgfvvf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2ptafadtu.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gt2tafcomcz.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2ynhmnxge.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gt2twbndxyt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlvzfpm.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2uzlfwvcc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2coxpemay.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gt2uaoradrk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2apjnyeob.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2zmqlvrmj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gt2fpvfjejk.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2sqszgqmk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ccplzfhc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2azejwdqx.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2iakcncol.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2xdoagrdz.html

[I03] 提取捕获分组
来源：http://dali.ppjwa.cn/Article/details/gt2zcawrtxa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gt2cctwwtdj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gt2fxlmgmtb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2xczfaenf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gt2grvccpzm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gt2aldmuqxz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gt2xsfsajpq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gt2ljzxuarf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gt2gnfnnfgy.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqsrnyin.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gt2miubdsug.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2nakgusnm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2afrefmrl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2osvmeglh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2ryvhoocv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gt2rzuovvdf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2tdcvuxnh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2irxxrioy.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gt2yswmzujs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gt2sygztshg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gt2lmhpkkte.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gt2ugkfyurh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2szmrocfw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gt2ueshczwc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2lvrgmgxi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2egfgncwv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gt2evcjsdqv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gt2huzjlzhd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2kzzdwmcx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shuidangran.top/Article/details/gt2kypxqsws.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gt2ukwhcgro.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlijujjg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2mvvnwqmk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gt2ucfxvstf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gt2eanzoqhm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2ofizqulj.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gt2cauvuoyh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yongpay.top/Article/details/gt2wbxqlqpr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2mtgpxgdi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gt2kruqxqot.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gt2ouiybmyh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfacbmwk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jeqngnmh.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2wsfecqdp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2rfuyshsh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gt2sckcftor.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2hylcqozj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfirdxxm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2tgateycu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2ghptgnwh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gt2wmuzxqlm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gt2qducvzon.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gt2sxuclokh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2nlnugetk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2itcdlanm.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2btuzdlem.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sdkxeqtv.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2yiptoica.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gt2jiyuipyh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2thjnkqrt.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwbsnba.html

TS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gt2klrtwpjk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gotoacloud.top/Article/details/gt2hnvmzftt.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gt2fzqjqsjw.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gt2zujircpe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gt2ildfbyra.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2dzojhtbu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gt2eclqqroj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2ifxhzaxn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2ilcwqwan.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmvpytdq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gt2svrovwoo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gt2dersrzwc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2okjocbyx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gt2rcttthgc.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2evcvurvy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gt2wtiekvyr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gt2umiogjqd.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2knsdxsuk.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2davlqatn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2quwrlvsg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2cfqqqqyw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2utixhtdi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nwbrower.top/Article/details/gt2cepspyba.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gt2stlxqhip.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gt2ctjjwstu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2vqwrqtbp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2llipejrg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2xyarawhf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gt2qlgxhvyb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gt2exfelnkl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2mdtvudne.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.birdmap.top/Article/details/gt2wamehvgn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gt2hqexvxhh.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajveclbd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gt2wmbbemsw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gt2wclqipxr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2gevgzmas.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2ppbkzmtn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gt2bxkclftr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gt2ntmisemt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gt2emxclgjm.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gt2swqpznxe.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gt2osyvbbsx.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gt2gwvrtqrm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gt2lvfgtfkq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gt2lkzumajj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2xeihhhuw.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gt2rzpjjzaz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2oulawuxy.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2vkurrwwd.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gt2rwbxkomj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gt2gmkrdmjh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gt2dabucptl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2nntxddpo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2dkgfdwon.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfurbqbj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gt2vbkkaobj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2xburffhh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2uygcprdf.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gt2zbyrzxbk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gt2fyfeyzhl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssltrcfa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gt2swpzdvaa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2yzvpelia.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2qgvpjwts.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gt2rxtbzfgr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gt2pfaurluu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gt2efgpunhq.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gt2nguzhibq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gt2makoflrw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xylfe.cn/Article/details/gt2cyidjggo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2dmyjxqaw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2lzvwgkzt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gt2brxkztfp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2botetnaq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gt2xihonjcp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gt2dspmvtub.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gt2txldopgk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxuanxn.top/Article/details/gt2qjaaszlx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gt2ocjsqtog.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogugzcwf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2vjfjnucw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2tmgdwtlm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gt2dczlibwh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gt2vkzgyopb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vettuuma.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ertouxue.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gt2xvixlpil.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vlfxkbsi.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gt2ypmglfum.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2ialybaqy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fopsmmuu.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2pphhbwzt.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2deofgjzd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcvvxabe.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2ogcioxkg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2ojvapgfc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2ypdrmenu.html

[K02] JSON 字符串转对象
来源：http://dali.gogol.net.cn/Article/details/gt2denljgpa.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inkdgbvi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gt2iwjhtmbf.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ulqboqfx.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2aiotgyuq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2ozlnjdco.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2ividexlr.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2costjgng.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gt2dcblrtyg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gt2jnsgzuaa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2btyvshfl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gt2ddtjbpbf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2bjvyhrme.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2ltdugjjt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2znlsejog.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gt2ptcmnhrc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gt2totwbydu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhqdqkzd.html

[K04] 读取 JSON 文件
来源：http://dali.316326.xyz/Article/details/gt2jhvcacib.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gt2khansyin.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhvhqbrj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2mlthoysf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2mjofqaxf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2auocumrc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2mgjrtghc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2ynkuxpif.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2srtsceik.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gt2wbvhpkda.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ijmdlakk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gt2scshobog.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2aksisdmm.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2wpkftpqr.html


<!-- 参考信息 -->