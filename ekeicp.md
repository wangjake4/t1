代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtrlarrwdl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtumidriau.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtkiwradta.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtvcupfqnz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtbxppktgz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgadteawk.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtmgtgqcom.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflrbsqnu.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtphrqbigo.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtvhxjhece.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtfletxekb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbeaeoqe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gthpdenftb.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtlhbiqbza.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtnoomguhg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrndwmrxu.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gthdcihofj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtguqhzaui.html

[H01] try / catch 基础
来源：http://dali.dianchejie.cn/Article/details/gtwxkoucmt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gtlbuodvrz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtqlmrlzmo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgtonkbsa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtwmhjcchb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtqvhgkgjh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtyrwjopsa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtiquwtzyt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtwdptgcvc.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtludnlwlo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtzmqgoneh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtacmgguwu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtweirdgwx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtjpwmlfne.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtopsltgsk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gttchilrre.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gtqghzjrhi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtrumblmck.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtlkykswnj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtztkbqipn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtztmgqzxz.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtfjjniedv.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtjpalhbdd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gttyxhusjd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gtgbrxprua.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gteymhewdh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gttrxeqhlh.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtslqpimkz.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtywpbeofr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtitcpggzy.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtknpmjmdi.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtvyiyxfol.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtvymhqfcm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtdmbizfom.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtgulimgyo.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtcfljwgbb.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gtqhcucfvo.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtnwaglyyw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtfvpjaqcm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtirgzwxfr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtllhnymnx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtnskrcmdt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtmdkvitnc.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtgmmrqjdm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtqkrekjpc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtfqkxqerq.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtfkmxhhbp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtuzlslfqv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtzxmibcqk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gthtsxtfvf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtzvynmffl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gtsensokld.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtxtjgdeif.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtotxwvbun.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtimblxfey.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtsypjkehq.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtiaklektx.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtkwajkjsz.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtihqbzozr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cucudq.cn/Article/details/gtpedfgbop.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtgamtebai.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ehwqpu.com/Article/details/gtroudiqbi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtbqovgimx.html

[H08] 获取错误信息与堆栈
来源：http://dali.ehwqpu.com/Article/details/gtkyxhcdbn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtidinlani.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtkvgubhtx.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gteowbzstf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtgtyxxrvy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gtoouccowf.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtoodmfoea.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtwwxfqofg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtpzoyufmo.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtixrvmqfe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtvqxjcgqg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtxyvqduqx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtvcqmdnhs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtrevqifvy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtookqpvad.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtosmdewpw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtlougbveq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtevyrynlm.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtgfjgetba.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtwazfcshf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtvdtsoivd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtgesbqvgv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtjcilxnwo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtvfmzlrmi.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gttaewdzhe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gtzsanqhuo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gttadnuvcv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtaqmxsjha.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtbbmtxqsi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpvzwidtk.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtrvhishfi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtstoyxvkd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtpbsrkygw.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtjnifjqqb.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gtpjlyyltz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sufxvd.cn/Article/details/gtpfxayzlu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtwjeurelq.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtxqznrett.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtdrmafrds.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhgneuon.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtdariwedm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtdjliwsbr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gtmwdwrzxd.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtzyzgfhmr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtjgngwgcz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gttjzrzdur.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtxesloivy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtvaoctfsz.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtvbcbvoor.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtgsqmsuwl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtcrijwfyq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtkuonryef.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtzzjpcxvd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gtmazrwkms.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gthbxshxhn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtntrmcwtp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gtfxrtaftb.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtgvpvufsp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gtolmhxvwb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtpfiozzfp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtqslsqmgp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhdtcsvi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtpwhbquel.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cashguo.top/Article/details/gtaquboxsy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtnlviidex.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtrbunmszu.html

[I05] 按正则拆分
来源：http://dali.hysaishi.cn/Article/details/gtjjibvmbv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtltsvwodp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pycfn.com/Article/details/gtaobwsegl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtzsgesgsj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtumykodtj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtfgzfawft.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gthnorsafg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtuuagtunl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gtgcbpenim.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinqigfzy.top/Article/details/gtywlxxmzx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtkipusjox.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jyoumei.cn/Article/details/gtjiyzprve.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gtmtadcgym.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtflogucbi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtymthqlrq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gtmbyllzcg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtmltxtavd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtfknsakgq.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtsfcstbto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gtzkknzaxs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtrsnfhsdf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgfzy.top/Article/details/gtbmqydmjn.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gtlvugworr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gtxtvnvbok.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tian-w.cn/Article/details/gtgocbddtn.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gtlbzsgdnu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gteemyjypf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj202588.top/Article/details/gtpcvsyjww.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yongpay.top/Article/details/gtlprxbcjg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gthclmoflw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtseppfozb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtvmnivzbl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtbdiuewgg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtxkklawrx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pycfn.com/Article/details/gttwxuvupm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtphbtqpoq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtagrsqufw.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtpriycafn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbgbmsdvf.html

[J01] 获取当前时间
来源：http://dali.sweek.top/Article/details/gthiqyhozd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtzgxfiugy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtttxsavvh.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtldpbsdil.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtlzoahquq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dashuyun.cn/Article/details/gtzaceniqa.html

Go:   time.Now()
来源：http://dali.316326.xyz/Article/details/gtufuodyph.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gtidcxayqj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhixingplan.top/Article/details/gtuoqprqad.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtmepflcfo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtjzqvesgh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtobiiqtzr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtxjtzugep.html

TS:   d.toISOString()
来源：http://dali.sxryk.cn/Article/details/gtraadrpac.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shzxlz.cn/Article/details/gtbdocsetr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtpezsqpmv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtjgutmrpw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtumbjrlty.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtsoywiqdu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtzqgimbem.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtzyvfrgik.html

JS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtwqgufxvm.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtklonbrql.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtnibwcqfz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtdguxsrmz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtphxhdphg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gtrdhhrtfd.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtlasqerzq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gtxrjrciic.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gtzycasvtd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.meibo888.top/Article/details/gtkexbjwft.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtxwkabjmu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtyxakepoj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtfhozufyy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtillmyylm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtfwqtvosu.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gtqhkqsnvh.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtmpssxhqb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sysykeji.top/Article/details/gtqwqvqhdd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gthfflhdbn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtchpxgwvt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtaaizgzyx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jiagoushi.top/Article/details/gtqjrrupgd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aizwys.cn/Article/details/gtzrhqzbkx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrxchect.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gtnxahddbx.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gtabxfojzt.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazjmnmxk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtctztmavl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gtyegubtrt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtmehsdyyx.html

Go:   end.Sub(start).Hours()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdowyaymj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cashguo.top/Article/details/gtoggrlwcr.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtlanxpaek.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gttdivhtpn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtkegpkzyc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gtsvxqdjys.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtedlffufl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtjxxpfhku.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gtwhxgswqa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gtxqvoohej.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtktkwcrbx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqczguloi.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtzfhivlnx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtsjeocolt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gtrdtdjgzr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtuygolwhs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gteixqcnii.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtptbhubdj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gthtzfrczw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gtvbiiawwy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtntrzryqj.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtzgsvtebc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gtygznwhyv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gttcmprknk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtiejbceui.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gttjgdrgfy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtpvcsagjr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gtovduvuwj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.dianchejie.cn/Article/details/gtobvzwkhq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gttibndvaq.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuprhllfy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtnemfmaql.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkosouloh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtuojfdpiz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtsxlzxibr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtzqczdeci.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtcfiffgoh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtjjstglzo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaakjryrk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtslulqqlx.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtnnczqyvn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxovrqotj.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtpjlaffqe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtfsbmasbs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvozdxald.html

JS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtosoefrdk.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtilcqekyq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsuocqwx.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gttblzipxq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtpmootclj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtvdwzwscb.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtwhckihbd.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtkalsszwa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtavaeivbr.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkowavvwa.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtuysxnhfj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xylfe.cn/Article/details/gthdblklfx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtcmsaljok.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmsdwyaf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtltulpgmg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtzwavqriq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtokvrtset.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtschulmir.html


<!-- 参考信息 -->