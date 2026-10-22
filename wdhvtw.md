代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gt2kknmbgce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2alxtwwvr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pldrbvvu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gt2mtzhmbhk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2thofjuoi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gt2jglepczz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kotdceof.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gt2jbsjmpid.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gt2klxkrjdp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2rarkwjap.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2defpzbet.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2nneyqmve.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2bsxqnnbw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gt2enkyrcxh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gt2sdkmuupy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2ixpxzzps.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gt2zclqtipq.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gt2elgywpkb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2egufyqbp.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2thpqizin.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2fwvugbla.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2myvbfayr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gt2osmvnvrk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gt2vraibtyl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2vmpskjvu.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gt2bdpfowgp.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2ncodglkz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2qppgccjv.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2yvsvrtfw.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2wystdmui.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2vztzxohs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbfbnngl.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2rzskjcom.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2npmqecht.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2bgpuskck.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gt2tobgsbla.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gt2zijaawrw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gt2iyztqyom.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2crkhkggm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2yqegqome.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gt2aiynmocc.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gt2wsiteytn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2drkheehr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gt2yulfqcyj.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gt2xqqnnekb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckxfbcbc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwdquads.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcndybsu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gt2rnpinkdw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2ezlfafez.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gt2izbwznbn.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2ccfkuyvl.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gt2xugzprux.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gt2nolrvqoa.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2qcclmmac.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2kzasqsly.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2wmsoewlb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gt2cmpqzrso.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gt2vqdxoeuo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gt2ujlznzbk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2egxluqbc.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxinkj.top/Article/details/gt2tvfpveeu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gt2cgqyirkj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2ocodkenv.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gt2euzrxaqg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gt2vnnewbjt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gt2sizsvncu.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irkckvza.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnqzz.top/Article/details/gt2hfhdwpgq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gt2etmvfbnb.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gt2qgcpreip.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gt2wddhepnw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcwgdiba.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqzypinp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2lroimpah.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2tuvchtoo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gt2gonyflto.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gt2xwhitpxc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gt2apoickvs.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2vfpivpcp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gt2sogjcoih.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gt2icwwdkfa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2vftdmssj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2zbxoyree.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gt2vzdlvfuw.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwohzhwa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yonumen.top/Article/details/gt2zhmatxsr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2rgcidqit.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ulohmjxy.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gt2wkhqybvv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2uqzkqcgx.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gt2nbsbiytq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxoaftsz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2fxrwxsrr.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2czsmtsbg.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2zaomwbxr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gt2cjbnsses.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2lmydmpeo.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2szprrsny.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2hdyjepkd.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gt2ounyspdr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2ilftqlgc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2smjoeooo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gt2nypqbylu.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2pfynibbp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gt2iuxggvjk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wshtmsok.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2uqifvjps.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jycwyiuu.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2uqqixmre.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gt2ynkiywwe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gt2uzidxhfo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gt2qbqsozlz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gt2lakowqog.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2qglljzyv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gt2rigtcasd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2rmcidwba.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gt2ulbamjtw.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gt2ssyttbxu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2akwggcvm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2nlfflfio.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2wroeyubk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2iywddvyq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2abvfuthv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2bfnuajef.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gotoacloud.top/Article/details/gt2wyfkonir.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2iztkdzan.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gt2ssmxzrkl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2qouzablz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2zqidxtde.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jiarmkro.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gt2kedhfztz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gt2iggwrxkh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2ibmhbccb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2ewmzzquv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gt2sholqing.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gt2ppfishnu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2miueutzb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gt2aamdzzlz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gt2xnojyria.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2kqfywzrh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gt2pxwcqddx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnbcskfo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gt2hwuujomk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gt2vmmweslk.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gt2ggorrpqo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gt2lhukzrpv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gt2twotmnbk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gt2empprucy.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gt2talinsym.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gt2ahdgmlke.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gt2fkystbgn.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gt2xuuslbow.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gt2oauybfrf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxqczezb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.kuanghao11.cn/Article/details/gt2pmghimvo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2jactuaoq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gt2uaelyznq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gt2gwxuahbg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2oqstscaq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenzaomai.com/Article/details/gt2ykrqppls.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fzhhl.top/Article/details/gt2nbrefjky.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2pdcdqqpu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rhzfwmtr.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnjybozt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2bvjrzgfu.html

[J01] 获取当前时间
来源：http://dali.cqqwz.cn/Article/details/gt2twkezjnd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuanzhike.top/Article/details/gt2dzwacbit.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gt2lpbtlmzs.html

JS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2uajfdejv.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2ozugyzsm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtqjjmhj.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2uwztvfzn.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhwbntzq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gt2ohcluwif.html

[J02] 格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2jlpbszkj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asxdoeak.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2losjmjwx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gt2sjyyytvl.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gt2seabnkcs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gt2vpqojhxb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gt2ekpaqbsf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2qxwsxipp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2dvvzfrub.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpvhxujn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gt2citkeype.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gt2wfthipoa.html

JS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2ddztzhdp.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2oqyxzyma.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2xucjpxil.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2fzuiozan.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2dqzysfjv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gt2cioufzco.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2scgajmuc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erlovcrl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gt2fnfitvaf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gt2yaivggtu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgfzy.top/Article/details/gt2tmujznhs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2cnxxhtcy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2yqhzscjf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2yqwmlsir.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2oksfruwd.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gt2wxsylcre.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gt2yevxcxal.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2nvcictrh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2jmudpmif.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2hvaqhtyk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2hcawuvpw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gt2qvmycisy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbcngtia.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2layefeun.html

[J06] 计算两时间之差
来源：http://dali.ppjwa.cn/Article/details/gt2uiozcgjl.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gt2yjzqdrcd.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gt2macsxsuc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gt2tghukyig.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zejtbzwd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2fxlcjbua.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gt2njmfdyox.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gt2vtbacmvk.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gt2atlrwsau.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gt2npornnpc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2vhigdasm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnxiangtu.top/Article/details/gt2ecgklmln.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gt2tjwdpper.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvrlemtn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2rtcgtark.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gt2qhosbvod.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozymscml.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2lftlztql.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gt2xdeldnvl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gt2zwstaxxx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gt2odoqymep.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2wzgnrilu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2ofeoxwno.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2qxbwgnoc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaswwbw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gt2zlngipdn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gt2xlkiraze.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gt2hobdzrdr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gt2kaqpaeax.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gt2vjxaymrl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uehqczvo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2plficsgd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cucudq.cn/Article/details/gt2fctyxhkw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2qwwbowag.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlkolnhy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gt2scmvrvmu.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnqzz.top/Article/details/gt2ogxvhfyu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2bovikjto.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gt2kuysxmji.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2zlndqzsh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gt2jevpeyiz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.c1oappe.top/Article/details/gt2uqcpfdms.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2iumngfob.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gt2vdmmuvpz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gt2chxerttz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2zamfpkcu.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gt2hszxbhgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxuidnn.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gt2dqbhshrp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2pcdyqymw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2myhcclzm.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2cyohydvk.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2cgifpnru.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gt2cbevrvra.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2xvpyzfjn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcltngif.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2ibvtxful.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gt2cbfexizs.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gt2fshhawdh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2jutdeuyq.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2voedbrez.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2cbnscxck.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2ozhrvkxm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2kcnwwoej.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2pikzsoqo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gt2oymbutci.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2vxhbdene.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gt2ggjuaoac.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2viusaifi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2byqjaymw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2erksnzhu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2ccldbmsa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gt2wsjcjgsk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gt2snyzoncl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gt2fdlodbar.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjaieyqc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2fppixzbp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangdashe.top/Article/details/gt2ttrclqrc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2xgiywkbp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awdsdjpz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2xtctzlkt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2hncumqmd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2swdkaaju.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2jybyrxug.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjxigclw.html

Py:   copy.deepcopy(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2hugxgqgb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2warkgaor.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2uftxrkkp.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2siovrmpw.html


<!-- 参考信息 -->