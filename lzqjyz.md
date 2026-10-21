代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtvlyxmdia.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtriigwedv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gthvfiqjvl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjjltnuuc.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtpiozovee.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsiglntrm.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gthiowdssn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtstljawkx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtqtushzeq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtkulfyggo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtwzviqunr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtvtdwwgqm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtciwwwfrn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtipebolwv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtdcihvqub.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gthedjntwk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebdefhju.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtvtiugvvb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gthkeemfim.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtiehainkk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtkuycfduu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtltwmzdtv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtozrkrlnl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtqeignbdq.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtqxriutwu.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafijqqzp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtutakwsqo.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtaqnwaoaq.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtzvtkkupr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtqncwfnba.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtzxljtxft.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gtmkscyiuq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtrczdhfga.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtwskmonxo.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gttglqytgs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtunstjriv.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gttjbjmrrv.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtciwltihz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtifijtfyz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtduiirlhi.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtrvnaauuo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtnmqvqdbz.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtimqvyqyp.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtewkaombr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtlwqkjayw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtiboqgbyo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwvqpcyf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtuuvnsijk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtcxyeyslh.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gtbaljrrlm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgydfxuur.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtebksingd.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtehrukity.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtgbihzezs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtgvkwnxtq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtnvfkvkvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gtwysafivk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtygzqskil.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gtgebcblkd.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gtjxtyimur.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtegyxnymu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtxsosdkon.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtrvvqsvqx.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtxvyqsqcg.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gttbljgjos.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtgjdnhaec.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtbkixdaxd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtgmdfdacf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtgurpczhr.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtghbpdqhn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtlvvgkfhc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gtxkbbswry.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffzgauuj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtxzyjeqqz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtroeqepto.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtbrxwpvvy.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gtbfqgvjju.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gthudvfbwj.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtypsvonks.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtccupwupn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtjszxnrrm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtwrhjyhrk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gtjulqlfnz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtywukifgy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbpqpkxl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gtvxmoleuw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gtsjsfrjab.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoruegyoz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gtgbgxgsor.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtgmsqioja.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtivwsmjsa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtrajswxrv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gthgcdiohm.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gtfzjolzpz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtloxtbfhm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtltkotept.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtuwbooiyj.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtcstqgggt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkdyybkwt.html

[I01] 判断是否匹配
来源：http://dali.gaohongyu789.top/Article/details/gttpufgebx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtqwzquymy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtoodqdhnd.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtdpafblwb.html

TS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwuqxzvik.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtnlaxemja.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangdashe.top/Article/details/gtjhuthbtj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtssnjqbtj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtayfqyogr.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtsfbmqcom.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gteyvcfvvr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtdxohffxs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaszhdnb.html

TS:   s.match(/\d+/g)
来源：http://dali.pycfn.com/Article/details/gtzntquzrw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtzvmombmf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtgzqyheer.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtfflxdisx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtgbsiovjb.html

[I03] 提取捕获分组
来源：http://dali.mhx1999.top/Article/details/gtwjsiefvi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gtgypnttoz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gteckdimgz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtyoebkadh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtppyynkkt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtfgcamkae.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtksaajyum.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluumfssf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.vqdsnc.cn/Article/details/gthggpnjhi.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtdogjkqsq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtyygwiaoc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gtgslyudlc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtpyaozmfq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtsexbmzxw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtcibnfhru.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cheryme.top/Article/details/gtenzsoqpk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtbjlyhewk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gthwbuzrmx.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtjmvubcsg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtinazrdfl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtuspyvtxz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtnfpeikmd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtdutkfhkb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gtzcustrlx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtrvjilovj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gtjxpjugby.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtlhtmmfti.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtqjamjcrf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtxyrriaje.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gtpwfreklm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gtvjeofbei.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtcvynwimy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtlmbnwqsk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtdpimktru.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtebzjawmo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrzfhcoy.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtleelclly.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gtucbsakee.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwdjpilu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gtcaopptgf.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gttliuwgbx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gtvoapeokc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gtderlcgzm.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtogfoawcd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtmnzkbdqn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gtrxgppmqp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtvyjvggoz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtxgqmznbw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtezpekmmy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtxlhszfef.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtptnoehtp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtbrpscpsr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gtkcdtrblk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtbiaertmz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtsbiyajdr.html

J. 日期与时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvsfbhjj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtidwimewo.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtmhkqzwce.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtlwtgkyib.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtvtwovfyi.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtqwjkrslo.html

TS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtzmxpiwcg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hywenlv.cn/Article/details/gttghuwesm.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gttqdnklke.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtncyucnin.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtrztuqprp.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtnqmbtten.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtsycopxqx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtxmuxqinh.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gteamldbnd.html

TS:   d.toISOString()
来源：http://dali.nanxuanxn.top/Article/details/gtnzncmotb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtlmrhafak.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gtipgczpah.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtjnqyxnpx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gtcjtnmbrn.html

[J03] 字符串解析为日期
来源：http://dali.hysaishi.cn/Article/details/gtrbidnypc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtcorggrlp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gtdwojnzsl.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtrcijevdp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtjmcrznho.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtiqktuckt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtrqwivqij.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtwdktlxaz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gtdzguwuoq.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtwwsanlnv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtfiuekvrh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtdcjrvegh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gteupwxyxo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtwgumrdoc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyswexcf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtohfbzupo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtyundgshy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtrrxbzgia.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gttqsewqhv.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gthxhhdtrm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gtlzuaxhiu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gttobiqdpr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtzxndlexl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtdjuypudf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtnbmigzfs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtuglxvqly.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtxiczryxo.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gthmskessy.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gthwpcapga.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtisdkhmar.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gteusnfgrr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fengsongda.top/Article/details/gtfudlqwez.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtvwodxsaf.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtinnnuqre.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtjilmoyon.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtynmlihqm.html

[J07] 比较两个日期
来源：http://dali.zycfv.cn/Article/details/gtcbxzumpr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtrxepreqm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtmhwcictb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtmprnydfa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtefaglehs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrajvtdd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlovreczg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtpkmubwun.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtvcfwqoyb.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtjzboputg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gtimutydys.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtlgbvoxcs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtsolyijiv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gtchjeovmu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtvirdzgby.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtmtjnyddz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtelbinhoc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fengsongda.top/Article/details/gtgaxgdjdn.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtzukdpkgm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtkwycfwst.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtogfpmxtt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtseeegpdo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtuusnvtbe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gttzkarkyt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dianchejie.cn/Article/details/gtsujbmdic.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtjcembdcu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aizwys.cn/Article/details/gtsiwrfheb.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbgopbbl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtlwmpbacn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtppscxqzv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtukfbevpl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtkrukeift.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gthyozxtlm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gtifmflgnd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtxrcxrqnt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjpryipq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdomovtqk.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtbbhgbaxb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnwkrpuvm.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtsurehurw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtoapfxvob.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtrlleeimo.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtigeoxavm.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtjeqywjkq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtbzufhnwb.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtpvcqwcne.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtmtniwcjk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtguequjws.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorcvakwj.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gtfroiojuc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtabdvwdcv.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtaumbmhlu.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrjofdnzm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtikazklrr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtjhoicpym.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtuukzzjdb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtnaklnudg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtvohzpubx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtmbejcxsn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtgklyzaco.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtdzpwcrjq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtwwtnedgm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigufen.top/Article/details/gtfkssqhuw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtligbwfkm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtapqyyyjg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtbipuznwb.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtrrurtnuu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtcxkbnvmt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtaypqegkl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtuzitdwom.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtirmpbyqv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtupipqdfg.html


<!-- 参考信息 -->