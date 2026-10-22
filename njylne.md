代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtxtggjyrj.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkxxfmnpz.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtrlxsfdxr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtrgjxpzsu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtrlwgkmry.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtbaijnkmi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtrgbzuknu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtioypsgtv.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtnjginbuw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzzckcgvl.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtcdmnvadi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtufisihtd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtnjtkxoza.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtjmvirnqu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtjxamwpuv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtrvdgkhlw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gttwbopmdt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtcizgmzkn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtsmlsxgrr.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gttycbsxdm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtxlzpykad.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtncltxpps.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtkuqowfth.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtjfttphgi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwabobrjd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyxvbamr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhwrzelt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtungdnlfx.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtwohynaxp.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtbighpwvj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtycgsoopd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gthkdrlxxd.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtflvmbysc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtjhivdhmo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtxmexcuah.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtgddvkcdl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtccsbwcam.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtczggnmjt.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgvopzys.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtuxhhyciz.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtjiylnnqh.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtpjfnsrau.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtaxysimji.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnxiangtu.top/Article/details/gtojnfhhhm.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gthdgklmfc.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gturhfgsjj.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtyxiinshk.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtwtamwimk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtxwdtiuno.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtvrwekyuc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtomgpuyfd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gthvyavwga.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtskgnatwn.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gtpjftpprc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gtqpcixugh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gthynjwdza.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtipqdhjpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtbvybruam.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtoqsyxjns.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtitzhewjo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtsxvyppxi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pengpengdd.cyou/Article/details/gtyrrknenf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtzhuesjqz.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtocsbeiah.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtxoyurozo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gttzgqqxxz.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtshllaurl.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gthvpnvjis.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtsnbonlgg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gtyeqqckli.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtifszucst.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtroewobqm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtlkjilkbl.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gthcvzchay.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtacyewfaq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtkfdjvtof.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtldqbmtvq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdrziyra.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtqrmayizu.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadzbtgkm.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtiezuekdg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtnikouuxw.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gteppwhbop.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtdinozwjo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtvreawzqr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtyevdcdzr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtjqsopanx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtaufpgopk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtinmirxwm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gtcxofrihw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtagusavof.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtruytqbrz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtiwuouieo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtxlomqckn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtnbhjktdq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtbisoqboy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gtqkmlumvs.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtkavylqzv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtudubmdgi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtfbketufd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdypqvfhy.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtapypvfiz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtadtbpwxt.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gthieqwgme.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtfnetfhyp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtmuhjigor.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtbqzskcbm.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspiuzzsw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtoqxvxwzf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtzkshpqxi.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtwcccysah.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuznvmakb.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtbnjvojig.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtszkgubbx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtmmzoewqd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtnrkaisxt.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gthcjsruso.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gtxgogapjq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gtviqkvkds.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtmclbnbol.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtjzxfduvy.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtzkhupdsn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gtgpxgcssp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gtbyhmljxh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.9152youxi.cn/Article/details/gtsgmzhcyw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtcwgbpaqn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtzbveoytl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gteqlpstlv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtpvblzmgp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zdqjudy.top/Article/details/gtsylturir.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtupbirpjm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gtzirzdtwu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtqjnzgsos.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtlokejhek.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtpwguzfmf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtslaauhhm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtmstgtjok.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gtelspkhyl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaryvfteb.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtatqhfslz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtdbwuwhid.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvmppmzib.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtaoxourmo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtsfjzmhyc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtrgocixmu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtktyqudyg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gttomcsnia.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gteegjoaah.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtsnuqhplc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtcgnqinrv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gtkajpsnqk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtqzazmild.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtuqunpeoe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtojspywwr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gtgtrildpg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtwrzxxmui.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtbrzxuvuc.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnxiangtu.top/Article/details/gtjbalvqav.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtxtlfcafh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtgljizpbd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hywenlv.cn/Article/details/gtgkwbyaev.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtjzptopxy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sxryk.cn/Article/details/gtumftoonm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtaqhtcyhw.html

Ruby: s.scan(/error/i)
来源：http://dali.yvedp.cn/Article/details/gtbctxjroq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gtenkrwxdq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtdkgluxky.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtteeeagxu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtlounjvgy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtlaphoynn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtkzohpdor.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtfsgmnqmq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtkjyiwzvm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gaohongyu789.top/Article/details/gtvnikbxbk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtrjhmjmbd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtluyrbhcr.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtwyqcedkr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtexfeixmv.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtobaqyeiq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthriuietf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gtpcjevtyi.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtojgxhzdz.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtmvwwksbr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nwbrower.top/Article/details/gtsoxrlavl.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtcmbajljw.html

Ruby: Time.now
来源：http://dali.gaohongyu789.top/Article/details/gtewbpzoss.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gttemmvvov.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtbyxkugyd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtaehmkdxi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtaschfupa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtsgaqiibk.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gtomvmayrl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtcargsqap.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgfzy.top/Article/details/gtngfmisoo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtzmatundz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tian-w.cn/Article/details/gthqnisivp.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvsyslux.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ehwqpu.com/Article/details/gtvxesezka.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gttowglxiv.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtmqkuboop.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtdqhefazc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtalaiaytr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtjkcujiru.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtqdlfxgkb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtlngeyqge.html

[J04] 时间戳与日期互转
来源：http://dali.cqqwz.cn/Article/details/gtpxmnzftv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheamzofy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtzriniosa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtvrpdzjep.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtdjesisnn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtxnkthewh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gterbirwhn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtismdggrb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gteoeapczo.html

[J05] 时间加减（加 7 天）
来源：http://dali.sysykeji.top/Article/details/gtxezlkvrq.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtiswzunlw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gtxbdkzalh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtjjwrvlwc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.mhx1999.top/Article/details/gtglmkrtmf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gtzuhiagrq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtygxdyetf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtjrjsvgfv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtniddsqof.html

[J06] 计算两时间之差
来源：http://dali.yuanzhike.top/Article/details/gtiqcthjde.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtubxustpy.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtmgpgmimi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gticwafvoo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gtghzilwku.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtjrhhwjnq.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdguaqzd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gtjpdiural.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtncilfsis.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtxxfcpsjm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtvwgwfoti.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtgawpjfga.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtfszptkjj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtflieuyyc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtxfcokgrn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuvsgitz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtzlmemflt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gthhruxnzy.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtkukjmelx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtldwlvtfv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtfraizbjy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtmxasgqqp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yangfankeji.com/Article/details/gtfwbdopwh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtscyyzpms.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtwuaemopu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtpwuzdwes.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gtdopxfkwt.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtmygmpoxv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtmpfhxygw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtifrimhro.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtwghaxiek.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtqdhnndkm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtltccimgr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtrnqiynrl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnidrupza.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtxkcxsgns.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtvbcvmubr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtxowmqpwv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtxicntkso.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtpdylefwl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtjnouumih.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxnlexkzy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gttugweuff.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtqmqayvps.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gtdfxghliw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtheljgggl.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gtpireeral.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbxjpzmwx.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtpszmvuvn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtmtdgjmix.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sysykeji.top/Article/details/gtviwuwrsh.html

JS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxtpowzz.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtheqxepyv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gtiwppodds.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuhmzjgs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gtjzmhuwrz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sxryk.cn/Article/details/gtvwveicnx.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gthgfbliry.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtphavybmu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtqzwtmaob.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtvhmwjwyn.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtjfxpxyqk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtylrdfgvy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtvtslcftx.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtwvbpzrjd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiekjtwtl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gthenjdjlu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtblivgphf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtkizblgzb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtuspcigdp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtumdabbci.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtitrnnmhv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtnjeysdit.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtgygnrwzn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtfuuhhlbs.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtjaluctrb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtpkbepwgz.html


<!-- 参考信息 -->