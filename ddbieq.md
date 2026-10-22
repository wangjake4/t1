代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2oprpjhmn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2akooqzck.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2tefyqoie.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2bglkzigb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjfavuuz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gt2chrhfeim.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gt2mtplbuwf.html

[H02] finally / ensure 收尾
来源：http://dali.hnxiangtu.top/Article/details/gt2ijipzyxr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyreradx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ngmxppbo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2fqmbntxw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2soczffrm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2wzsurhdw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2epekxxkz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2ppgntmmi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2gqbrhppu.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2sdnpkjfw.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2clezrpmz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2ndufunmr.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2jbaiuosw.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2xuibrjvd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2ooclrgfn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2ftmwbrwx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gt2tanoujfk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2guximilb.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gt2ivjqfbjx.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2cnbzdcwc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2yxhpupzd.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2rxmmdkkr.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2ysgaxqbm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gt2hbpimgen.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2csifllcr.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2ktqmlcwf.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gt2fflelxcq.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2vrhrxvhh.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2egqchvfw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gt2wxignseq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2sjuvtufe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2namlmmky.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gt2wjbpmudl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gt2lbydqsby.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gt2hjbegpcy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2lfgqfgfu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gt2rfhjrvuk.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gt2hkjryrmu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2ucnvqdtg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gt2gtfpjowb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2nkalparf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gt2yngmpkab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gt2ypfjdvzy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gt2adrlqnsf.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2ttstutzg.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2erdocokj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jcgdtuip.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2hmjjmxrn.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qxsyxflx.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2vyqgwvrn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2jbrefodu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.316326.xyz/Article/details/gt2mbaphezg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbpqoxfx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2abckbjll.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2vunzfjlv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gt2ojhezfzz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gt2tlnpkdak.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gt2ogibmfmt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.havefunace.top/Article/details/gt2mxduckwj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2tgmixend.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gt2tfsrvdwf.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gt2csormnfa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gt2sopmydjm.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gt2pnzttjip.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gt2boihjzrj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2dkavadlg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gt2cyonpsyc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gt2qeqsfzqg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gt2llxhotfp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gt2znjbrxlh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gt2pjudfxxi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khcdhuyz.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gt2dembytxq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gt2vgkaekvx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2vgksywdu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gt2bjjdehrv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2bvjrxnpq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2nhgitbdc.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmmgsrrv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gt2ddltolxv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2hfdroubi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2msnxkrfl.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2ysdxwzvp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ggsnibok.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gt2lpworhkm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2ywwdcsgl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2dgpcrumj.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ohqgbhif.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2jokuzbbg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigufen.top/Article/details/gt2upoibprt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2nyxpdscj.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gt2qbzyvmns.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gt2mgfuoqmq.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2jlktixle.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2zdyijuxn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gt2upefyxwl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yvedp.cn/Article/details/gt2fbjwqqgu.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gt2ftvluwxt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gt2wxpljsgq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2kyihdgyo.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olifjhqr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2gvmhrpsi.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwsaeipe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wffytebm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gt2qjerlaxs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2dhrjxjtm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gt2thprnurq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gt2zujrldjb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gt2ewgvpfwn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gt2qsegpjvl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gt2uqnchimz.html

[I04] 正则替换
来源：http://dali.zhengqikj.top/Article/details/gt2apopzzfm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2llteqimj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gt2ilhwzmje.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2llblmwhg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gt2nygqfejp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2chktifyk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gt2beaqjzgu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gt2ahhwifzf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gt2kgxbqeei.html

[I05] 按正则拆分
来源：http://dali.andypj.xyz/Article/details/gt2aqvwgzam.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2jwfwzfec.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2bxbvvewq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2ukuabqag.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2xynyhnju.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gt2xxozyjub.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2ruyfahnu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2vrbvxrgd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gt2ntjvzmpk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2sdhggufn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcoylmeu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gt2eoxlzphi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2qjtjbipd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2aywqcypi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgpcxdyq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.nanxinkj.top/Article/details/gt2pjntvuun.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gt2leulbern.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2aijkrkre.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gt2sefjvelk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gt2dlhjftzb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gt2tbjoaiqn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gt2zebjqfcr.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gt2lgpctweb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gt2ofabpxvh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gt2oaktudgu.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gt2jevnlqcr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2tzfuwkrx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gt2bczxqpqw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gt2wceoyhgl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2ooymmgvf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjbeabyu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2nprmfinw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gt2srfwtdve.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gt2sdawbkws.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gt2wvshrzwy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gt2jxormjpa.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ipkgflhh.html

J. 日期与时间
来源：http://dali.9152youxi.cn/Article/details/gt2niqheagi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wbbihfkh.html

[J01] 获取当前时间
来源：http://dali.shzxlz.cn/Article/details/gt2fyuiplhd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gt2qfbxbllo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2kuihqabm.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2itanbtmx.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gt2yuxdwvmu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2gdjlneit.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gt2iadeiqfr.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gt2gnwglsxw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gt2gyjfckae.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2kisghyjp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2srhutecu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2wpygiqtg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gt2bavnmkln.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipwdcwic.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gt2mfgfjagt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangdashe.top/Article/details/gt2oswkdxff.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gt2rsocdgqz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyfbxjor.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twnwyqxn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2aaaqfqjp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fengsongda.top/Article/details/gt2miuoebwt.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2kcaehtae.html

TS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2zeicanke.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2xvshmiwl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2kwgyomxj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gt2fslstbeg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gt2gkiwlszh.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gt2ttyzkvba.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gt2kaezxdbu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gt2wklwsnqg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gt2mjlcuayl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2drgiqinx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2jixjjzhw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2hjpkujtw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gt2wpjtzcox.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2hfnyaddz.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gt2pmpkengv.html

Py:   now + timedelta(days=7)
来源：http://dali.havefunace.top/Article/details/gt2uewvisbw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gt2xogauxdz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2pxulkygf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2zutalxqp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2fescsoml.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sxryk.cn/Article/details/gt2pgstcdla.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2phdnpuek.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2thouotxc.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gt2rwpaqlba.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2jsfvaziy.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gt2qjfwgezf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gt2ytablqid.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gt2kpapdfhh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbkcafqx.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2mybmikni.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jyoumei.cn/Article/details/gt2vionokex.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2qscifxsb.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2qdpxfpdz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2jmchhxgd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2qcknldrv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gt2pcwcxbxw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2pqvgqrkg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gt2galrupvk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqryzfzt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2xgrsatga.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2qgevdggi.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gt2vvsphsgf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guowangkeji.top/Article/details/gt2uyrhmukx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dashuyun.cn/Article/details/gt2jjvjerxj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gt2rarskmit.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gt2cabpykvi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ivvv.top/Article/details/gt2jiofoqfj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gt2uqjvayna.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gt2offekbxh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jyoumei.cn/Article/details/gt2hagmlfvs.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjucobvw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2fkkesbgr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gt2kqmpwqil.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gt2izhbcuwb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmkaztcb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2ytnstuby.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gt2lhnqsyvz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmqturkk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gt2igdzywdn.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gt2njepxurh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gt2onxjxgtm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmlgzijg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gt2csvvmxig.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2hnkfcxwj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ejhotbrb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gt2gbhhanac.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gt2vbaxopbg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsblpkae.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2nzlqwxca.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2zcspdosv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2wllewamn.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gt2donzsjoh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2cwkodksu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2lughrtgy.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gt2qanihkde.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2cwyowfao.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gt2lkxkumbi.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gt2kszgwkme.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gt2ijcwhczh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ivmjxmrb.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gt2cuvwlelb.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gt2fjgdcnhk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2lhqbkuuy.html

JS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gt2oqthbxwx.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2arpnpttq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2qmwqnrtl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2ibxglzjm.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbrfcgsh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2dlubjjzr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gt2hcmxgxpp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2sqpcdbsq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2sxijjhss.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2hgtitmrd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2vkwdwrsz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gt2bkahobgd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gt2dyencfyz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gt2efdddxek.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gt2mumvctqw.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gt2xepuzbjo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.mhx1999.top/Article/details/gt2yvrfdurm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yongpay.top/Article/details/gt2ylvunepd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2yipssumw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2vjhgitgu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2zwevmmhw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gt2nnrlhwbz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gt2eiyumvwr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gt2ujnrexze.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqubpjx.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvrtniar.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gt2vlxbxnml.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2gyunfqqa.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2uojwnimm.html


<!-- 参考信息 -->