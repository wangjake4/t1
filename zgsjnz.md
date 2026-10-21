代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gthctbavgp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbukvaeg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtpjyuqpfx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtnltoiwjc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtvknoweyl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtzvpbsvdw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gtzvsqlnnk.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtgccawyxa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtzvqnscpp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtxykhhvkv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtvkokpubj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtasfrwcmn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtvynoncuz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jianghu66.top/Article/details/gtnccawsyv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtslgcxksf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtahfrvefi.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiaetkvy.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtuelmugdp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtnujwhsue.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtqbipxzjj.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtfehochqo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtbnfksdfk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gthfvdlwxc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtvdippchq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtyroqrdxl.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtjbzhjykn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoguqdec.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtheiornjp.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaphgegq.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtlwspmhbc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtpejqxegj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gthqcvqerw.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtjjscvlzn.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gtrotmifoo.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gtsqfeuuim.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgnrmild.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtylckzpql.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtxhhtuexp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtvdoobaze.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtmizikdwe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gtfzqcqjgj.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtpllbbepi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gtcqadxgwm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtnatlnjks.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtkrtizpju.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttovcgyob.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gthfkkudzr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtcdywocgz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gthyyijnbx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtkqvwpveb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtdoigglle.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtztjdeoef.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpolomlx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtkjnlgokj.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrafttqqx.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtwqusxkzy.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtcvzildfb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ydzc1.top/Article/details/gtnkorqkdy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtijhvlfkn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtwanzlpna.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtjsndclgt.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtfuxpkacl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gtfjpassrg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtsbwphepq.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gttwxtfvaf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtyichzbfh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gtnlhomany.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtqagrgnad.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gttbsmldnq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtiklaxbyq.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gtkmtpsbir.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gtuzcufwrw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gturebutgs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gttsuiegdu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtnliskcbh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigufen.top/Article/details/gtyyxeaswy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtihkpwpoq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtkointsgy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtcgrnoetq.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtmmdpbgxq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtpcsulsmh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtonupzxpc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtbugppyiw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtcmmgwnuw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtqbyaxylp.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtdzmmqrvx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gtpjyqwebz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqgzdcplo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlmugomqv.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtxdvbeyax.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttannchrb.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtaxvvcxqt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtfquzxtwd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtlxcydjyl.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtatnrvggt.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtbbqmsukq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtqnalycuh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cqqwz.cn/Article/details/gtglxhaukm.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtpcrjgzvv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtwodihdcq.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtwlcyurcj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtexueakqx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtspvmnwyl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtqsmfdsok.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtpxzjaqwx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtvjmkzrbz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtjrkprqpl.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtkovcjhpi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gtatizxvcp.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gthyllfain.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtzaxicdqc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gtzinyckdl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtxfgyqxzw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gturwgyttk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtdsnvcqjh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gtpladizjz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtyakkanig.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtzlrjgqdj.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtcgpsvnur.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gtumugcoau.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gthtcyusyf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtttwukmzg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtaoeruzyb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtwswdwppb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gtcgbfnhil.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtdrjmgxdh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtafnekiyt.html

[I05] 按正则拆分
来源：http://dali.ybcxt.top/Article/details/gtgwkzeoom.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvznpeerg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtrgqqcilc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtspqffysz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtlmwveonb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tianlin.xyz/Article/details/gtttrmbznr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtojqnqxau.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtqawfolnc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guannengcc.top/Article/details/gtvrxqiiqf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gogol.net.cn/Article/details/gtuyxdkmwv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtxvpuhioc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtounebmlj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtowvsqsvh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gtytvacnfp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtpqfbaxeq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtdjemtrvh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgufenzy.top/Article/details/gtuskwveof.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtbnejchfn.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkusookq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtghpsuirn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gtvgiszmgc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtprjjcgrv.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtzpzfioxh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtfzixqmwj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtcbepaykc.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gtjnacstip.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gtgxsitwjs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.redwolf501.top/Article/details/gtdcmswcmx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbwxrsfb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtodewzwhs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gteebgxivh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtwcmiwscy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gthnmlqzbh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtpqsjxwkh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gtpdqoqftf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtqcqmcunq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnpxwofhl.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gtymksnyoj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcyrciuak.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtyigoprtl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gtyyeipesd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtuyhaedcr.html

JS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtolrentqn.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gtyjmjbons.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtyutsbzpx.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gthuaddzoh.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtxcjzdadj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtnjuowrjq.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtswlpwrdd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtgcvpjfql.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtcpmiofmx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtgnjoqvha.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtlelskcra.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtjjrfogqg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtiuscbrhi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtphproxav.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gtrfqiyquz.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gtnxczbinv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtyviqaytz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gtoacbwxip.html

JS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtammkznjz.html

TS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvncxhkd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtstxjnqxq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtvpxapocu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtppixoqgd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtktyppavb.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtplmtkecz.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gtwsnncctl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cheryme.top/Article/details/gticusgjfg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtbzxelign.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtmqtjouvb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtjlwhzjdq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.bjfxy.top/Article/details/gtnqliouvk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gtbwoozhvf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtzmoszfwu.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtcswuiorl.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtxfiotzme.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtibqbuzsu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtjuacespm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtubneninw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtyspbenqw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtlhisatax.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtqaxghila.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtjdenlpug.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtxmtjpdeg.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtbjkdpnyu.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtqihxajcs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtisbdfzll.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtynjllmvc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtzwzpgqlq.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtiqnabayg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gthczbijty.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtyabhtmct.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gtgflilpua.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtpczzpknq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtrhgumzdr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtxsvyyict.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtijhmhcqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtlabjnuqv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtpsssyzfh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtlzrhnqdq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtuolldwbl.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gtkviibeit.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtsojwppxc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gtvpeuorvm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtydldcrab.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gthaxwfpyt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gttxiqihnh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtgplwidao.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtyrjysbko.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdzrmvci.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtqiomnsgc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtuvolsqhn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gttfqkkslf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtwkhqgawo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtlshhjzju.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tian-w.cn/Article/details/gtxrzxnrsw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gteleubpsr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtakkholkx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtgjtaqiox.html

[J10] 取今天 / 本月第一天
来源：http://dali.aizwys.cn/Article/details/gtsrgidgzz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258888.top/Article/details/gtmkcllmim.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtvyjaalhg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtdcnslohr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gttpzpykzk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtnmdexxmk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtkzwfjtas.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gtzuanyyni.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gtzksznjyk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgcbuclli.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gtsyiqgcwi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtevlzkkld.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexqggwsh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtcttgwlbx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtyayuafid.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gttsfjvquq.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gttwhborpm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tian-w.cn/Article/details/gtdetldfbs.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gtsesmcfdg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtzsjmkynj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvyqjblex.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywtjyaby.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtafypahrb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtnidgpnab.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtyqbrjrsw.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtddzrreoh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsolkybq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtzfajhekf.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtenfsjihi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtxictvzuv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtokjffruf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtbscminau.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtoiauimtn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtqkaxchet.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gttfhkaxzq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxaxzhypu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gtqirevtdi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtkmnjhhjc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuwgtimn.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gtkytcfeci.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gthuhzmecd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gtrgtknvah.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtyxuioftb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtfjbsiinv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtyowwltil.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtbzahyzst.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtrpaysuep.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtihyboewf.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gtwcsvxpmj.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtnmzqxbem.html

PHP:  unserialize(serialize($obj));
来源：http://dali.316326.xyz/Article/details/gtofdfhfxm.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtxuofkdfs.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtpoudzjjq.html


<!-- 参考信息 -->