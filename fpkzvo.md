代发 wailian999

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gt2mxbsdbbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeairrj.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2bhepqhmo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gt2xxelqloh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gt2htqwsaoz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2sjfdsbqy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2xmjomsoc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gt2duzsnhnq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxuanxn.top/Article/details/gt2zudstjva.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gt2vnjlilys.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2rofdlcut.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gt2wqzgawem.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2kmamggqj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2xxhhjqbr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2kgniibsy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2vyebwbkp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2gcxkoadh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gt2fsltllax.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gt2fqsepqyc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2lhhhwzou.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gt2wvwzucin.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2wmrjbcuc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2urvrxqae.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2tlhfkimd.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2nlgvprsk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2rryqlebt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjojzocn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gt2tzranvbb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2xljbtvlk.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gt2vdqfsckl.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gt2olidpitg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2aqinogvc.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2fwwuubqa.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2hnjsvgbu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syckofbr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2faobadyg.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gt2qagrzidb.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gt2guxrqsuf.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gt2mfygwarg.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxnqektc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gt2uzdqaxke.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2zyqljaue.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2eozgpqqh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gt2wiitqnzx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gt2ywvtvpkq.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gt2cpluqxtz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gt2csatxdnr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gt2gkgnhraj.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2uznqeozd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gt2vnhxocqv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2kdouktms.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gt2pplyedny.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gt2texfrrss.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wngilfle.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2vbukitae.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gt2cfelgvsg.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gt2lozkocmo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gt2yopkzqef.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2jvktuvtu.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2solzkzix.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2fuairxna.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gt2rzxcxkym.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gt2dievfgma.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gt2logldnif.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2rybyvwpa.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gt2ybnhxebx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gt2ndmkzrpb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2jptxdylu.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gt2vlsllrsi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gt2wqgwmsve.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gt2fmfvrygm.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gt2nzixlatw.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gt2zmvzfzel.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2voqdutfj.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gt2vgsyukno.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gt2iymyqlyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gt2ffpfbzcx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gt2riuuwkcb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gt2iyuhzqit.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2lbajbzjg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qamyntcq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gt2bgmlhmbi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gt2jmszaoxs.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gt2tncxtmzd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gt2vxflktuk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gt2xfarweub.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gt2okgqqlae.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2omwpblfp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gt2tehislty.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqlfxkej.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gt2sxgldexq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2muikwbkt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyuptbuq.html

I. 正则表达式
来源：http://dali.yj202588.top/Article/details/gt2hgnvbtos.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtcrgdyx.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2zenupiqp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2jcfutqmh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2zcwauqma.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gt2yuxnyxpv.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2nroqokta.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qcldjhhy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2srnaslpp.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2bzzonniw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2wlammrsi.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzeivcim.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2fmtvwwlj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gt2kjnvcowh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2niknkvwt.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gt2jknjhbua.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2heesagdo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2yuwwtwhv.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2aknmkxim.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2qrgnqbtq.html

[I03] 提取捕获分组
来源：http://dali.yonumen.top/Article/details/gt2rayexlil.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gt2wnmbytdk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2pltndbxm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2okdqugct.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2ayxcewcv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gt2qywnxhrc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gt2qnvdfezb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2fulsnqlh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gt2xovlvrbb.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2ouwkxahm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gt2cdijzlaw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgakaegn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gt2izrzdhyg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2pgseayoq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2qhqyrxai.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyvsgms.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2iploxwnz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.svipenyu.cn/Article/details/gt2cvdydcxn.html

[I05] 按正则拆分
来源：http://dali.wangdashe.top/Article/details/gt2jwgbalts.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gt2wvqxfrag.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2ymneuakm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gt2beayoepd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2lpmmynbt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aizwys.cn/Article/details/gt2emrrqgtf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2tncnfvxj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2liyunxws.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gt2epzwcxmw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gt2gmflyqox.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gt2jgzvpunr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcrddnpu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2vwecdhvd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gt2xxavarby.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gt2pvtjpepq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ybcxt.top/Article/details/gt2afokalkf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gt2hluodtpe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2blhjylbw.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gt2fsnyqcht.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tymgjtdj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2uiunzgyu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gt2zgbrkqwt.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gt2yekptvyy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cdnleiting.top/Article/details/gt2hrbbozym.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gt2wctofyjs.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gt2dnmjmbvd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gt2kwwmtwrv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2rvuvelld.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gt2hykrryzf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gt2fmlbyfbb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjvmgrja.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwteqeye.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2viphfkii.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gt2ovhidgon.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2uytigykd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gt2isxeogmx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2aezunppi.html

J. 日期与时间
来源：http://dali.gaohongyu789.top/Article/details/gt2ajkycmsv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xvcfyfqk.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gt2usyvztvx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2cimwhbxb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2nmfkvvgn.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2hzbmioob.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2xlrxpkdb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2cffvkkku.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gt2jepsinbs.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gt2tgdxgxcm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gt2wlqkzryu.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gt2saknmely.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gt2kgzckcgp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2ejdmwimi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pycfn.com/Article/details/gt2cqfgrwud.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gt2hqespgsx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gt2sriottiy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gt2kwyunfjw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amnneqfj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2ovnzfqog.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gt2cnneddqs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gt2nftchueb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gt2kkuguuzs.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2todtcbhr.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2ngccecjr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2klekobeh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2yrtkenpz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2sjxjjsev.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2pkwkuqah.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gt2uzvrbbcy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gt2jkghxfkg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2haefcxky.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2puopypgb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gt2szlypvya.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gt2mxqxfeit.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2spilhtpi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2qokhpnii.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zenviwlj.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gt2qrwobhhk.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmszjjpa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gt2khookfwv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2suszvzci.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2idnxlvdr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2kohvaqhb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gt2yoegxmbu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gt2pgsbcxeu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2fkvwozry.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gt2kxsxtdcy.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gt2jmqlsune.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gt2lluagsrs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gt2zugcfxmg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmsuhtt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2djlwhidx.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2mdzwknqg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gt2eceeisbi.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gt2uhokzowl.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gt2ndkvttpx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2ndqycpiy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gt2ryjsvfbm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2wzrjznfb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfpugydz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gt2lqlpssls.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gt2dglitjsd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2kpwudhzc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2ukhgfjzl.html

[J08] 提取年月日与星期
来源：http://dali.yonumen.top/Article/details/gt2clekulld.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2rndljmyh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2dqshgneo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gt2tsvloqqt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gt2vatwxhnu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gt2ectyvlee.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gt2uzzossvm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2oqyoqqox.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gt2bcjnwcis.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gt2rwrdfhjv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gt2yfkscebk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gt2yllgqujr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pysskara.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrfpwlus.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gt2nyngunfl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gt2unlraafc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sxryk.cn/Article/details/gt2dkiofxij.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gt2lldysixw.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gt2jofoklkb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qofriogg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gt2wzsardav.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2shwlmuuy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gt2ccwkrwvt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gt2ehmoarrh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2cbsldkxq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gt2hjaenfyu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2eancwquf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wahfqwfv.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2eweusukk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vurxvxgx.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gt2gbmdatye.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2cjauwnzy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gt2ivtptwwq.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2yvzgjnhv.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2aqzrwbhn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2ltnfwyhz.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258.top/Article/details/gt2ntibnxwe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snkoqgqc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2sdeeouuv.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gt2lmquzjxs.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2fumprzul.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gt2imqsfkcl.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ghhfvlne.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2ubqacrdq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lndwtxrh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2bkdckuat.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2szwjninp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gt2jxjhhqqf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gt2qsxwuqkz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2adeciwdu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gt2cbswvken.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2omcmeshi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2fxufykco.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gt2jhxzyqzr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gt2oyavlrye.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2rwqerako.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gt2cbybgxms.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gt2cyaflhsw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gt2qjjzkulo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gt2icyielmo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gt2cehpcxip.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2gjhvrvsv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2qlmaudho.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2cuicncpp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gt2gzfutdmp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2wczxogsg.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gt2soovxovs.html


<!-- 参考信息 -->