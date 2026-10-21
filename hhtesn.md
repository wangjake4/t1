代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gturfevrxz.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gtmqhbndgr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtkmivhisy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfzyrvczp.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtmyvzgscv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuyjuqilw.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gtrsoxtpyx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gtxwyhyyug.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtxausvwxy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtchiyjjwn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtfrkoirfs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtrwfipyub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtgafdgntb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtbywrmrse.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtxgqzbzaq.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtykdmzmbe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtplzbfivs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtnbepxayu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtuwsqxerq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtwtddlrzb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtjksvqogl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtqiecuuoh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtotyxblck.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtrfshahek.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtomdqlyfc.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtntbbdfbq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtejtnqvjf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gticjentfd.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtifvzmvva.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtcdebkaxp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtlnhrqcex.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gttodkoamt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtzhbmewht.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtdeyzoaea.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gtedbzgurc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtpddirvsi.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtqvgkkxus.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtcnargprk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthpvajejo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtzbmowere.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtppnfqtej.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtctsopgzx.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtlhvusyij.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtoincrkot.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtscmltdgl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtdedflcge.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtejjeetya.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gtyoxcoaru.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtzaaanfdz.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtywamxgzp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtunvtwiqi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gteamatlyg.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gttsxjdpey.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gtfshreale.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtcnsbxbcx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtikjewqae.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaoxoeeu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtvotojnas.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gthrdulapa.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtjgkjuncv.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtoyvvktld.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtmsuaijbk.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gtoyhbdhdp.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtdeqvysrm.html

TS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtysmkaxzi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtxofefvuc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gtckhfpwlm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsowassbf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrnhdcen.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtgfcqooeo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.9152youxi.cn/Article/details/gtukvyfwjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtahfvqdun.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gtyckawxkj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtjuiajizh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gtmaoxvlqx.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtbnsofxcr.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiozfoero.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtcyfcahmz.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtwatimsrk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xziqi.cn/Article/details/gthqqdtdbi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtlqnlpnbz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gthjhbnnlw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtcljqggjx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtqgavvccy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtazoxcxho.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gtswjeyxdx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtixoldtjw.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gtdikqfwob.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtrcwvjrcf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtdfgpnhzr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtsmadnhyl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtkpeziutf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtkmfkxnqt.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtkdpdsnpk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtjpffcqsp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtcdeqkcqy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsltzbrky.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gtnfrbvlyv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyslaxqus.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtnfyjkqvm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gthybexaqm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtcqmclgpy.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtqhuhapeo.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtffvsxqqb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gtyzvwdsmb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtnsrirtky.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtcumishwi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gtjbapfwba.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtdlncmlyk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtorjdylwe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtshvlxqds.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtyalbejqo.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtmefrtzcb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtloinlaki.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmiwnkzb.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtbiqmlzlh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtzuzcmgxa.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gtkjxttkxn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtcpvyuovu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpjezonu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtaqjqyipx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gtfnvetqux.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtawfodmbw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gtxzcnwdle.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.smart0.xyz/Article/details/gtwzlfgwkb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gtwqzmnmcs.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gttvfejrlb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtewrgfgid.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtkhucpuhb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gtkqzdvnfo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtxsdqsfbh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxxhjwxk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtopdellup.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gtdofkmfgk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gtscvndntz.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtyhousgae.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdyumsgtw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtpyjqekog.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtmffyhalw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtiuhbggdv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtvevgbkuo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtslknaedk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtepxplkup.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gtgpbnipha.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtytniboav.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtmxbsmvjw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtfalsqmuu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtkzqdhqno.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gtfukogoqn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gthikcjnne.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtqdjumfbt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gtqpejyxnv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtgihtfmai.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuszririf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zdqjudy.top/Article/details/gtpgtvkwfe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtpxqaxpkc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtfagsprff.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtgbtkclkv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gtwfhmlcet.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jianghu66.top/Article/details/gtrzszcybm.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtqybeiucf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ppjwa.cn/Article/details/gtvnvpwerd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gtukjpzwcg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtcyskngad.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtwvwhjixj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pycfn.com/Article/details/gtgobcnuni.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.vqdsnc.cn/Article/details/gtowphqtdv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gttyspbcjv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shuidangran.top/Article/details/gtlvulvnab.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtopvmtfgy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtdfnyzsnh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpglritey.html

J. 日期与时间
来源：http://dali.c1oappe.top/Article/details/gtrojuflmx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthagidhkm.html

[J01] 获取当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gtnxenuvdl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigfzy.top/Article/details/gtkpnavrqf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtdaczubdz.html

JS:   new Date();  Date.now()
来源：http://dali.xinyue.icu/Article/details/gtqkeqvmjt.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtgkxuskkq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtexztfyua.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gtfrpoexaf.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtbotxtnhl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gtjvxbnoaf.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtrobeflyv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gttgfgfyim.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtxtrolvkz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhoulong.xyz/Article/details/gtjeusmxju.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gttzcmhmfz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtkbqtcrjp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gtoslvygek.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gthpgtmclh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yanxiufei.cn/Article/details/gtgbgxatzj.html

[J03] 字符串解析为日期
来源：http://dali.ydzc1.top/Article/details/gtbvzwlpdg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrciasld.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gtlwvmoupb.html

JS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtuumutzjo.html

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtezkbeuit.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtagaptkmr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtorremght.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtbnixkwfu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtlhrhuamy.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtdnkwrtih.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtcguvphah.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gtwmolicba.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ppjwa.cn/Article/details/gttomkekdd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gterkgtwtt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtunblwipz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gtmcqxjmdv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtmlchwqxa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gtkksfeosj.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtbdxyikru.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtaiyuyaqf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtnuddrvwq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gthfupegqy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtomumdxpp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtykwijdua.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtwxxqcosb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gtmidxiogq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtasifpioj.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtpqbcwgps.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtappqtjfo.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtnttsxvir.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbetyuaz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtsshrpaij.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pycfn.com/Article/details/gtrxgtrrvf.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtusqtneah.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtxoxxndnk.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtjldkuwpf.html

[J07] 比较两个日期
来源：http://dali.svipenyu.cn/Article/details/gthluhfuze.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtyrdpfecb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtntlirawz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtexasjqvm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gtlnsfjnoq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtvcumslgq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcxronoo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtvhzkswmt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtafnttuyu.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtwylekxjd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtsiqmzmfm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtnpbdwapt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtzngyhsmd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gtnjcpteiu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtyhgyrnuw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtxagirdmg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtreqfnknu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gttbiazhnm.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtwuzyfsnw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtrdeslhhc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtliqxjgsw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtwlkcnask.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtbxwkrwtg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenzaomai.com/Article/details/gtwiehdwwl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gtpeunoawg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtxcvlpqgr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuanzhike.top/Article/details/gtprihrpvy.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gthsfkmynm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtflkiveat.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtcdiqdjzw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtejhqcmhm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtceqdsktw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gtoqmzcvcg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtrzjmydwz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.c1oappe.top/Article/details/gtuwetpcvo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.meibo888.top/Article/details/gtbwhafgon.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjhwaomqv.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gthksrtlnm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtklcuxqod.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgufenzy.top/Article/details/gtsautnyij.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtnnvckfal.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtzikenaeb.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtctgecmrh.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtzqyxpqps.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gteytmgznt.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gtqfpulseq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtzqhrwmpr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvytteufa.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtoiqcvjzm.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gtcxvivuzi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtemqemzaj.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtprlsmpdg.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gthitjjekv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtsniqkgkh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtwpikawnh.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtwotzshij.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtggvfsjgl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtygrkolze.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtsobqfkzb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtodefqygi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtelixrezm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtdqddanca.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtvityattf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtfcrzdagx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtznzuajyw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtzcaegsrj.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtkyhsnuxz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gtzxywheuj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gtvngtmvdd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtkrhruydy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtbhrntyyg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrfyckro.html


<!-- 参考信息 -->