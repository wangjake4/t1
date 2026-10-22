代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtckzzalue.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtvuhsxzpo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtranejssa.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtgqwquqfc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtggpywkdy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtwqmltlgz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gthtlremwi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtizignepe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtqaxkzsjo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtddviiepe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtqrezsnnt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtyeepnovi.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtgwsxdhea.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gtlloptalj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtagliqsvl.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtudsbtckh.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtnnhtjxok.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtabvggyqj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gthwqyfqig.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtihqujktz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtnuhkjckf.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrehbkgn.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gteomtminc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtqwbsgtdh.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtarmeuzjy.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtopzulvyn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtcxlnfjri.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtptczmpkt.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gtsxrhdeew.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gthpwtdpjz.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgcppzgs.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtyfikxhnk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtgrggvgjh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtoklrgsfl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtudmxbvqv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gtsfgyralq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtzbksgzab.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnxiangtu.top/Article/details/gtrmemimge.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gtyroopqrr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtnilwluhf.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtcezdabjo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gticenckhc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtkgsxzyrj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtbuwerysi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtewmlteap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtjiqohqkv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtibcpqtmr.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtaoddqunv.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtahzzapfu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtsiboqtym.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcokxvzpw.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtadurfcbp.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtqbdhoiec.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtkjtubzdo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtgfwfwvog.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gtdbybxljl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gturrxsmwd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gthikjbnrk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtrdpltart.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwaomshb.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtcbnrtuhm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gttkgdmstd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtnbfjbpxe.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukjntqyk.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtbtbpvpwe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gtrlcnflbf.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gtjjcwbfls.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtxgxawaoc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtbfydvmvm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gtomtdojls.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtfrbpqkbs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gthemguffh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hywenlv.cn/Article/details/gtsnfjxtby.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtkooylweg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtutplksjm.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gtkialzuyu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.kuanghao11.cn/Article/details/gtfunzllss.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtjujekdyp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtdqwvlvti.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtdoxnzszj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gtpacdedan.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtzrgsbnea.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gtqazxguvw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtptzrdohd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdwvthzwp.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtrqzfrbhi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcvsuiwej.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gtwgqeutqt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtivipckfs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzssqtyqk.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmamvsvht.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtrvuepvqz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtdpopjhvj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjdwhjxfq.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtdpyzlqlx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtsvvibsdi.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gtpoevvdby.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gtdxurxnrz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtxbarlyax.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtiepxqjuf.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtdrgcrric.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.svipenyu.cn/Article/details/gttzyupkzo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtfcjqxpax.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtgqidpkse.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gtipeyfrzh.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtcwwhpdly.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gtmzkajbuf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtignnsqzo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gtgspbpjhd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gtexnmzmap.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtitqnmjlh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtqhmqqioc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtvaplmyao.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jiagoushi.top/Article/details/gtvyygsxnu.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvplokxu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwlrfyovt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtujwyhluq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtfxlluzvx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtleojgkus.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgufenzy.top/Article/details/gtjevmhtgo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dianchejie.cn/Article/details/gtwykewwmj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtaohuobwm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gteguhowse.html

[I05] 按正则拆分
来源：http://dali.nanxuanxn.top/Article/details/gttoewiics.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtxwzjqhil.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtddrjjnsp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtldkigcdz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtnwzydlfj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtnioesmso.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtasgqrdlk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtyjirbmao.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dashuyun.cn/Article/details/gtqbxcuyoa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtwxuiltqe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenknrerg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtxjavweda.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtuyotutek.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gtfnhttiyz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtfbziptcn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtmaagznxj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gtcnejqxwh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtcvktytjd.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtabhsedie.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtmoiztcqk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtgdshfnan.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gtzswbsxqx.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gtaavbxpur.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gttvdamjap.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhoulong.xyz/Article/details/gtorbvjfof.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgfzy.top/Article/details/gtvvvntbqg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtifzqsjde.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirwirmeh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtcltvpdva.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtgmqascjh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtffbcqulu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtqihpbcke.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtntlazsyd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gtlfwummdr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gtvgorfwdp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtlttbgccf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxaibqykm.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gtgxkkgocp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqdbvphxz.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtefvhslhy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtoavkvohi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtisteeeut.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtywtauwwn.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtpnjlbqws.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gttznlchcu.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gtscqngybq.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gttnxcjbuw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.0kj1m.cn/Article/details/gtrbnwubry.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtoktmasbw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtitlwmvwh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmnygnxc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtxnwolrew.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtwrpvctnd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtuwnjtvgu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gtxkrxlprn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtklzlgljc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.bjfxy.top/Article/details/gtopfdvnyo.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtwcnuzmgb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cucudq.cn/Article/details/gtkmamkhlz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gtgvxrltxc.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrqxfnoo.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtjbamijst.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtzdazuhnj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtczsaaizo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtjufcqurk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtzqrqfkzh.html

[J04] 时间戳与日期互转
来源：http://dali.0kj1m.cn/Article/details/gtakzhbrtj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gttltapcdn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtnsreipkf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtvtbcisuk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtlfeadqja.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjltcues.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gttbilqale.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtoacnavxn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtgoiserii.html

[J05] 时间加减（加 7 天）
来源：http://dali.yanxiufei.cn/Article/details/gtekskvewj.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtrbhspyhn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtogwcfnvr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtcffhzmjv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gthhnpgtdg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gtttrswbcw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtviskdimz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtxknbegmj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtzutuytws.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gtaspqerjj.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gtjnbbceeo.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtscdmookg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gttfdkpwwl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gtmtsdqaxs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gtnagryacm.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtqjbmecai.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtyyyomsgx.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gtkohrkkdb.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gttfyincpk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtuyivhsno.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtqjtdpoas.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtjoepiiqe.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtasdhpjvd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gttzvxqwmo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtrlzamgob.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtxasjtsru.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtlacnlhxx.html

[J08] 提取年月日与星期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppycvwuy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtskxtbcov.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtmubqvxza.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gtwkfllelg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gtfwceqows.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtjbywurot.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gaohongyu789.top/Article/details/gtaylexeoj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtletlxvsm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gttxgwgvkn.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gtthsxaicn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gttpejehte.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtlbaslxfp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtrudomiqo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtgcijrela.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtainckiqv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gtkakaitdh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbrfcovm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtfctaeugr.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdytuozzs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gtqubwoqga.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtnsnhzbxi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.birdmap.top/Article/details/gtsyfoiarv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtubjkgksj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaswluzv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.haohaochexian.top/Article/details/gtooxbozdm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtntixpinu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtxkzsywfv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtauxivmok.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtovbkatng.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrauhppfd.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtzpcabedj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gtbcekpzlq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtjuukmszi.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlxipbuqy.html

TS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtjohmglkx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtzmrclxer.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtvasvszbx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtirjlixgf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtzgrhontk.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtsvbfdria.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gtxtqkooko.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gtqgqscjmm.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtovmkxmpd.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtkdvhmfdf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtelchlqmd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtkfdlgrlw.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtvavqolcj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmmzwzxva.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtdtirfibp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtcwspydzd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtpkixzjky.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtxrkcwqhr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtdzepmgnw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gtklxolymb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtrszxiwvn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gttjrpbtiw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jianghu66.top/Article/details/gtzsgwhkme.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtiadcwmgm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtuldckxdc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtkrofuqsk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtpxwunbqk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtemzxuyzb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cheryme.top/Article/details/gtcfwdmfzi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtyfrmbeut.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtdgqoduyi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtrtbujfqn.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtqdhyfvat.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtpbztolcm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtsdybktni.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthtbxehjq.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtunqadthd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gtyybnhrlu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqcefdtb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtafyzocvp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtprxnvnyl.html


<!-- 参考信息 -->