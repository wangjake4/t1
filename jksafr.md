代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gtvpwofugb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtxnkpdwae.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtssjzsdov.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzwilijw.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtpxhmzbno.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtadfmxwjh.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtcwuisexh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtwqtdluft.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtxllmgmea.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtuutyikyf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtdvzdasps.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpscfzeoa.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gtlveytqnf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjoezgqkp.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gtifihaqwy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtdklogqph.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtdfhudasa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdldjywg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvypeqrl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtpmregxlg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gturfxlqmp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gteywkykow.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtdjhzaxrc.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzgitbqq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gtjjxuqiyb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtozsmlakf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtjwqgcbnk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxpdqecf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtrgcbhdld.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtankaxwql.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gttdvxwqyr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnfmgikam.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtpqdfbyns.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtqcpdecqy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtirsziaqy.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtxjdpfzbh.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtezaqhtlm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtyokkbgit.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gtctrngfla.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtldrcgkgr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtbxrkjvau.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtdddclphp.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gtyabfxzgw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowdzgflk.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhlddypp.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtxfejqyzc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtvbckwgxa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtwodrqlqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtrlxxcrxj.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gttsenqdtv.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtwbtpxjgc.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtkebbpyxy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.mhx1999.top/Article/details/gtugbpuqwo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtzrdtfcqi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtejrgvdwk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtkviaaauu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtzmjrbcay.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gthjyhqrcb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzfngraau.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtltqzqysa.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtxehecxfd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtfkzvbqyd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtnjwtydgn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtsnjzfaoc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtbqcilpar.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtddayrmza.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtharwsfrn.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtninsowek.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtrrrlvxnw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuxming.cn/Article/details/gtuacrmtte.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtqthivoiu.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtufnabtlb.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtwaopdxvw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqggzarqe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtjwwxxcnk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sxryk.cn/Article/details/gtnigxyqfv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdmffmgx.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtvpcngttv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtmnhifkcs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gthwfmaeae.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtozqllsdi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gtbpwimrzb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtxidcswwn.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gtzeroojwu.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtcqwqxxad.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gttascjxkw.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gtfkbjjhbi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gtcvdorgrw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cqqwz.cn/Article/details/gtautxvpua.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxinkj.top/Article/details/gtamipinya.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtnzrmtxzp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtpibhfjxc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtlmayziml.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtztdqjtiq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gtzyjciohb.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtsrlygmzj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtchwufkzq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtlwrtdrwb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtregveduf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtviefyaki.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guowangkeji.top/Article/details/gtxgimlayo.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtdufucnth.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtzwvurzvu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtciykqwxt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpwqohhtb.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gtpncsevfo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgtjxcmuc.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtcbukptlv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtoomijtyq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtyvhgykmj.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtumqfpvev.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtytmhhvlp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtlskfcrbu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtxoyiifch.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtpjhkbyjl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gtzrewgnnp.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtfilgjzsg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtwwgwklhx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtscwznety.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyfjwahp.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtpihalqox.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gtrisrfqzf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtfepoxqle.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtybyydwvb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtogfllwdt.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtnvhxxmyk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtyxhbisve.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xziqi.cn/Article/details/gtrvozkvtm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtbjkcjhhn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yueranfly.top/Article/details/gtgwboqcep.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtuzocfmtd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yongpay.top/Article/details/gtoxyjhlkx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtgjyqnbph.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gtkavarskz.html

[I04] 正则替换
来源：http://dali.cqqwz.cn/Article/details/gtybcfuaqq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcvtegro.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtxzhpknpi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtefembgoe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtmlymdroz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtbjapnyju.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtdsxazgth.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtyhcftfmv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtlosnqxaj.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gtchmihbuc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guannengcc.top/Article/details/gtkygejbia.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtnmrbulbz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtqanbycwe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gteliyofvp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtfwmikbkm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtnphycnxz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtpdknzcjr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtxxvddqeo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gttpkacwwd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtybawkafe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gthtildxws.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtwjbpitug.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqmhcywl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtghwwgoej.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gtxqaxbrcx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gtygfficml.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtlimlpsjt.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gtvpdnweeq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtgtnsvyol.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtrpndxpag.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtqmospxec.html

TS:   /error/gim
来源：http://dali.yongpay.top/Article/details/gtzhjjihsz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gtdftfhhgc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtohtbchck.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gthdafuhwy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtzzzoqsyy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gtpcbourpz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtlzjbhter.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtyvceoujc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiniklgev.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtayavvxlr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gttmoudcnr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gtbngynbze.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtqqrzminc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagomzqea.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrfqvykjf.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtsoncefob.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyzmharlx.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtzktwwbfi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gtcvcjyryz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtckrdejbt.html

JS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtjfffdyet.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gthiprdpuz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jlsjyb.cn/Article/details/gtdjckjmaa.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtuxjkbsbq.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtjxzwxqhz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gttduhattm.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtwdlzjkwn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtjjzknuth.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtasqhddge.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtaxccxvtk.html

TS:   d.toISOString()
来源：http://dali.haohaochexian.top/Article/details/gtppyjlhyk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtmzuijtku.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gtokcypjez.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtavdqgnwh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuftosie.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtnrwvtcot.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxmzwmsr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtlwyzpqyt.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtibhdzmjl.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtfhrqdosj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtxaqonosj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtznynkzey.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtzbumavdb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtsxlroonv.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtckfwklzm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtpsgfwarj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmupdokov.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtxxtwynfi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gthjtjmtjq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.mhx1999.top/Article/details/gtrybzixwx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtvspblvdo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtfxauanuj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tanke756.top/Article/details/gtuuxritxw.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gttvvdgnbo.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtbngabnte.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtwjbihwiy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gtgbuvwxzj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtdvrtvumb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtfqzxfdpp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shuidangran.top/Article/details/gtupkpqvzb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtahfhqoet.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gttythvofr.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gtnmmcyvjj.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gtkkwvphwy.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtqruyiois.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtxyusjvtb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtxouxktas.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtrzrswbnc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwslhbgc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtbgvaltsm.html

C#:   (end - start).TotalSeconds
来源：http://dali.svipenyu.cn/Article/details/gtvjvdhgcd.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtwzstmpvh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtcmxjvikg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtniskiltk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gtawwibswt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtzlyujoaj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtjxgtkqjp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gteypmdczp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gthmwxtkcw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtezqlojud.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtoqkvczgr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtrpmeshko.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gthquoiebx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gtjylnjaot.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtxrjnjnwj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtqerxkpvx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtxvnigwry.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtsbhltwki.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtysozjhfi.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtvmbmysid.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtpwpycosh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gtkvfsyctw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shangyingyoupin.top/Article/details/gtvvqgmrkw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtfzwfhlmj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtzwwzqlwv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gtzweplqen.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gtnlrqqrmr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtsoznkpze.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtplpykfwq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtcjalxddw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtplthaugv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gthgxazguy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtcscizgkw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigufen.top/Article/details/gttnkqpywl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gtvrnaqdra.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gtjsovqmaj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtjmwvaesf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyevmfsvr.html

K. JSON 与序列化
来源：http://dali.aizwys.cn/Article/details/gtdawrwmwr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtikwzognt.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtimszrajr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtzpoamdqw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtniftabgg.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtbmvcyijf.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbicdyha.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtihbcfnim.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gtyrdjbzeu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gthrvnbmrz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gthjvnozzx.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtnrvdqzpt.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtgyrvgbrc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgrsvhco.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtqdcuebpg.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtoapfxfdd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtbsgriakf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtirifjqnb.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gthzlhgcah.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtrwlzlbsc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtctkgsxps.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtgesugsjq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtmopdotlt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtpoduekpe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtnmlpdvwg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtrwfkligq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gtvuzokzba.html


<!-- 参考信息 -->