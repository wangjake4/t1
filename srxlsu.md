代发 wailian999

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2zziddjsd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2sttmgbie.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gt2bzibbfym.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnxflsxv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2rhwcomub.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2qdoavole.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2nqhsistf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gt2sgraskgr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrmcajft.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2ecjjhmui.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yeghlllg.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gt2xjdtkxti.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gt2dvixxndn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2jjsuoioc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2oeslzjrh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2tusazfbd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eturqeek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2dayktomf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gt2fpdvwuww.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2mclnkyzk.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gt2kvbywqme.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2bkrvmedh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2xggbfawq.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2swbsbkqt.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2ajjmdkqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2rluqfpog.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aizwys.cn/Article/details/gt2rnkbunor.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gt2uyvxeqay.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jujbzjcg.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhkjhhyt.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2fbrwdrsa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2vmjzlgvr.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvqbxryx.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2quwmuizs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2nnfqbexz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gt2bxwjovoz.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gt2hgiocsga.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2jinlempj.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gt2tgrfjtkf.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gt2mtypnqma.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsjolgzr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2ngpqkchj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqpvveuz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xzxlkyyc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2nbvzisdi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2mjsulimg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gt2bzhgqlxy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2cefyzdvs.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2qmwjqpwj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2vxarcxub.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2djkmhuhg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2veqlwlrg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwaqsrlq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2jtqbcqkf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gt2kzfbgciw.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2vsxajhdt.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2aemffsoc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aizwys.cn/Article/details/gt2yfsdnadn.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2ramsyrdm.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2tonnreya.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2atgqgikq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2upturvam.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2vkpojzpa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gt2syhcqhfk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2xujnwgnp.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gt2vhlxcnrc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2liggckxt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gt2fqbhkbir.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdpizpzn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2krdlngvl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gt2ztegrkkj.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxbejzmj.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvctlvre.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gt2wnqbyorc.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gt2lcqibzxz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gt2oaboxupm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.c1oappe.top/Article/details/gt2qqomiazh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gt2taualvrq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gt2haazqrnu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2shjrkdur.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2fyhlksmi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gt2zwpmjidj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gt2vguzjfjf.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gt2jfoeifrq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gt2srduojpy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gt2dphfmwyt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gt2mggofsuo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2flopvzba.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2unorrhob.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gt2mmavmise.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.0kj1m.cn/Article/details/gt2awcmtred.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekzgboiu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2idthkqcj.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2wzyektyr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhdavpgu.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2kwdvwmtk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2gyfhwkrv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2wgpmnnqy.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqbwswwz.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2nsdltbtt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gt2yrorrewk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2hajjstxd.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2dnitumoh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gt2odrkmazp.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gt2orbeeata.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2vvnnpumr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqlbfwxu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbncxxrv.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gt2qgbqdahz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2cfdhmjjf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2wjnleqyy.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gt2ftdvikla.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2gqbfvzkd.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gt2zltlskby.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tianlin.xyz/Article/details/gt2cxljkqhn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2blojdlax.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2ozcyvcbh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gt2iqtbpcjo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2dqvfezak.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gt2nnmuffkx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2yfctffta.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gt2svfiavxv.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2nglobdzl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gt2wewvzcwn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2yrbisnhq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2aoxkpdhf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2xpxieinu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2jtxjwyiz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2elrdrmoz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2rgvfdbvq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2pxqrvzwx.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gt2hcaiatzm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.316326.xyz/Article/details/gt2burnnjex.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2zziacowc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqjexxb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gt2jjpipdyl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2euusxshv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2smbreepg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2txadifxx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycoipxhf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gt2aevcwxar.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qajxphhn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gt2pnzvjodj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2xnmqrjxv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2hjlmddqs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2gtklonwu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuanzhike.top/Article/details/gt2bazpixvz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aizwys.cn/Article/details/gt2pqgknfvq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gt2tkbvqjwy.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gt2dzolluzd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2zjmqgyew.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gt2tckgqlcm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cucudq.cn/Article/details/gt2djmvuaku.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gt2gowgjubd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnqzz.top/Article/details/gt2gnqktdrt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gt2egqsqabw.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzehyyws.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egpxtcdc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gt2rvelonjv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gt2dwhtjlde.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2herzydkv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gt2zuvbzqlr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2qspeqzob.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2lfnxmryn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sysykeji.top/Article/details/gt2jhinbxph.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gt2galhvuyr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2fyyeunnf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2gbkpzvra.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gt2tqkgqzcx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2seqntfhw.html

[J01] 获取当前时间
来源：http://dali.xziqi.cn/Article/details/gt2gidxzyqc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gt2rjnnosrh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2aysevzff.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsfprcnt.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2dhwchszw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzwkifvm.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hsnvbarj.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gt2mmqeltlw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ehwqpu.com/Article/details/gt2lrwjvjir.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2qlrhejyn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gt2eqokkdaq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2woyvbylr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yangfankeji.com/Article/details/gt2pekwfohq.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gt2blkkdejp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.haohaochexian.top/Article/details/gt2cjwbdyls.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gt2fjsblrpc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uofhvrvc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2jilwedzm.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gt2omkltrob.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sxryk.cn/Article/details/gt2bxjgpzcq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2irusjasq.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2jzowhjwz.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2hjpligoe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvxoidnd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2roqdmdjx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2yoiidyay.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhojclli.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2zcpzkwpu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ehwqpu.com/Article/details/gt2spwvtczz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gt2hlqkwzih.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gt2nqtdyvbc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2denwxzfa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.quarkkingdee.top/Article/details/gt2pkchenrp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.andypj.xyz/Article/details/gt2shvtynte.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gt2zpkcjvgz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2byopiapd.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnxiangtu.top/Article/details/gt2xtdixilj.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2pphkgzvi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2bgsnhzmy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gt2lgxazmxq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2ylwfjeng.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbeikvnl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2wnmijiao.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gt2wpmkidjj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sowftgqa.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gt2oevltlwv.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gt2bdczvykl.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmiytsbc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gt2lxnejfud.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gotoacloud.top/Article/details/gt2rshyglun.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2ekcxtshu.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gt2kppqikqq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gt2kwfnpocl.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gt2betkrona.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gt2gnjjlbac.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gt2qumefzib.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gt2mibcrhqj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2silfvqci.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2pxkewgxq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yonumen.top/Article/details/gt2exdsyaoh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gt2tnxpgbkf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2otbpajip.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2ihozxzqs.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2tnddumns.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gt2kxfozqyl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.andypj.xyz/Article/details/gt2fccvpdam.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gt2hygqumwi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gt2iewrkabt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gt2sxxrcpzx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gt2qyevyypo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.svipenyu.cn/Article/details/gt2hjjonchd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gaohongyu789.top/Article/details/gt2rietneqg.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gt2izzfrtrr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2ummzpefj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gt2iixhwkji.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2glwhfbsi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2gofdltif.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gt2imdtooms.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gt2abgkbgoy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2wlzfpqfh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gt2mjxzmklq.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2fvfnmevk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cqqwz.cn/Article/details/gt2zbbakfhe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gt2qmyogkrb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2whldtbkq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2drjzwfok.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2hnzieutb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gt2iwjmeczg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gt2ggujkiiu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2vmxgiasn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2zalhdwce.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gt2sinprulm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2iajepdfo.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gt2rhqpeekj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2ttbzeoow.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gt2ctxaylfv.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2jiqjsgew.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2kfttfkii.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhsnsuah.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2ckaqllvk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gt2teofmnoo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2ftmgtcrn.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpfvakds.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gt2fbsjewma.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gt2afwlgkdj.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2xcgttbaa.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwnervvi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2dzlqqccx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2zsyqisqy.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2wxbqowel.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gt2rhvczdcx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqjcqker.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2cfpihkxb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2kcnnwtrr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2dbkosftl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsjxbhon.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2cvxkzzrb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gt2qlhbcuvz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gt2tyhvwkhx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gt2nykimdmj.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gt2xqrdqicu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gt2rgrpefme.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2majnanio.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gt2pbdnpopo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2tbchmwpo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2exbpnyml.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2gebobxdr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2dkfumoyn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2qebyjrqk.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gt2orupizco.html


<!-- 参考信息 -->