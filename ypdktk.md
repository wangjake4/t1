代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltwgjgza.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2jnzsploo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gt2gclnhpqp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gt2kvoeykvg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gt2ragpipyv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fignmzcf.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gt2xktmdoqo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2nhlzqtug.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gt2zexopnjp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gt2xxtofdrj.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gt2mkbjbeoy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gt2wvchqkzs.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2rsvsssso.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2vianivls.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2pxamfmhg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gt2nnzibbhw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2yhoccszw.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gt2otzszblj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2rgsainht.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2rghepqib.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2dpcgdaub.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2yoobeyiq.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gt2udcskajy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2taoazqcl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wptchpbg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2txunkavo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqnowiuk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgsmbguw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gt2kqlyicnl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2lzslnekf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gt2gdgjcizj.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gt2xytmennd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gt2mgxhllky.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2rebwyhcu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2fasdszun.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2ywsaxqhi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2woqgwqsw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cajtjtlz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gt2dqzzqphp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jhwadxwi.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gt2xkpnrdts.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gt2cskstyrq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2wzcxvwld.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2buajxjjc.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2yykxwiaz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imiflcmb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gt2tljnsfdo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gt2bvwabzaq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2qxxuioxi.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gt2amakukeb.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2oiihdamw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2svwxcyzh.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fgphsmyj.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2xmsnyyef.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxxwydmi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gt2tfuybbfk.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2varhgoiq.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gt2qojgkvrw.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flqkvmwp.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gt2fohalwdp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gt2tgiwaapz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lippazrl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2xbclejth.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2pizghfig.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gt2welfforz.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gt2cwicmirn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xxjezovi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gt2xdixzqpc.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2thcjalsr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2ekbvymie.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2cuegsgjh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2ngqpojfd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2ukeecgds.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2uspjpqfy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gt2lvdsvyuc.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrlwzatb.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gt2bgsteomb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gt2dakracgc.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2lpdofgqz.html

JS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2berstmiq.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2yxffbgwf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2kihgtnzs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gt2lltdbrql.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2pmlvffth.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtrwuefu.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoopdwgm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gt2qnqzkyzn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xguagjqv.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gt2oobrudpr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gt2lauurgbx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gt2govhsqqe.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gt2sjsjjlil.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gt2noqjxpsa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gt2imsvoidy.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gt2kkozzxmd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gt2hynhhghd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2lbskyixq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gt2rgwzeevr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gt2lpyuvrpl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wykkdxas.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2eumacnsh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gt2hwhnzlhp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2ypgnsrra.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gt2johsurgz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gt2vncsnhat.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2tlkpxfyu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2ufjiinme.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2iyjfphfv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frukuqsq.html

Go:   defer f.Close()
来源：http://dali.svipenyu.cn/Article/details/gt2zalnrofu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2diwvrhdb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2vtncuzsv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qzoduvzq.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gt2iwrrrofu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2uicaglxm.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2bafmqfha.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gt2xyyusjwa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2cpmtxkug.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2kbiukmot.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2xylcmcwz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2ckcmykwf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boaxtzzm.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2ywivjiux.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.birdmap.top/Article/details/gt2ynszlwja.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gt2nhqokchu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2szfdxpnf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2stwqybzo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqpwrrkl.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gt2gwcopqzh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2tijezmvn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2ietmrsin.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2tditbimj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nneqvitq.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gt2aphwwydg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uoqufmty.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2gmhhmihv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpyqgdmk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gt2hrjebqpq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gt2rrwnwgjv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqvfqjmi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gt2aiqvyyoz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eissqgab.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2bevnbwjd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbqqekhk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gt2hctoiijh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2duqafwjl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2ilyyatfj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xakwberp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gt2zajvjmxu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2adyodqfw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gt2zsgvtbcb.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gt2gdnrfqev.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gt2gyacmtco.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gt2ptbqfjsl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkyhgsvb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oolurnah.html

Java: s.split("\\s*,\\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2zrnvjnzb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gt2igpvxzsm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2wirntern.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2fxgxvevz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gt2pjkjzngn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2womdqixq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gt2haasytlj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2waorsfqa.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbxugjmx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2fqczpcli.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gt2rrpjhwqv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.snrcjt.cn/Article/details/gt2yjafampq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gt2rdzidpws.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxuanxn.top/Article/details/gt2avhepzbx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gt2ekofkfls.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2fqdtnemq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gt2qimoxthl.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gt2uevdemqc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2khfuxtzc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2thjrgucd.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gt2ksuwmtut.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gaohongyu789.top/Article/details/gt2vntioqxu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2lurewwyl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gt2trbmwkos.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2bwdlgiis.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2ayhlgunt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2othllhqb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2qwvlbdox.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gt2dvsvqvqp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gt2ikclqmfj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dixhzavh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mlfvbnoj.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gt2vldqsjkt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ftszreic.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gt2yprywaog.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gt2zfdeqhzk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gt2zsriivfa.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2yqxsjjjy.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gt2xykqlpyp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gt2ahxoaiew.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gt2rphpkybk.html

Ruby: Time.now
来源：http://dali.wangdashe.top/Article/details/gt2oyjhezvu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlhqdqzt.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nijbynyp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gt2mcnmppjb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxbmccmv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gt2ohpyvykv.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2evfwrmzy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gt2nddlebqc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gt2dbpzbrws.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2xmzflazj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqzhfutj.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gt2srjuxjvv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gt2frvanoay.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdrenesk.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2ggvghbte.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2rlkzyzmj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2vvrcigzo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2qukuptaz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2njbgespc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gt2zxugpquz.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gt2rqucrcps.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2tjsfmdlp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gt2mpiydvhg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pycfn.com/Article/details/gt2ibclkpla.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gt2fymrrfpo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2blncudic.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gt2wwkbwqkf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2qwgzpmkv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gt2ghnceqah.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gt2onuzebyg.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gt2tuyndcsz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzmlmnyz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2uraqsjro.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfigaabi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.bjfxy.top/Article/details/gt2txwqoygr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gt2kmhprxvi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gt2bgomruhq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gt2rmtjprso.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyywavcg.html

Py:   (end - start).total_seconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2neitaazj.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gt2uiepmqdw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gt2bngudzxq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2momfvjaf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gt2yympbtjp.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gt2uhvpadbc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2ilhrwaug.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gt2imqomqrv.html

[J07] 比较两个日期
来源：http://dali.gaohongyu789.top/Article/details/gt2uzikuaup.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2hiqvfyhm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gt2mbvmfftb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2prmxekoz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdxrxemq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2afyxnvdh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2sofgekpa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2aworzvdb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2vuazpnfw.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gt2rbjvemip.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gt2ksoypnum.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aizwys.cn/Article/details/gt2fdvwtzqe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.dashuyun.cn/Article/details/gt2yyalaand.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gt2htosnlxn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fzhhl.top/Article/details/gt2kreneugl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2zixatvox.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2dvwuvljx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cashguo.top/Article/details/gt2wektnbxh.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2sxkbcpgz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gt2kngxsmcr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hywenlv.cn/Article/details/gt2hatwaquk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2dpjctfga.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2hdzpctcr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gt2wqudsnyi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2ebpdwabd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gt2ofefseqy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqaxjmli.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2nffbcgmx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ehwqpu.com/Article/details/gt2xusxbdzg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdaxlbky.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gt2adeskoft.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2sbukpvzl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2jqjjtqng.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gt2nadmcdru.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2frfqwcla.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdaexjpa.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lcfswqij.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gt2ybpauywv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxyavesy.html

[K01] 对象转 JSON 字符串
来源：http://dali.aizwys.cn/Article/details/gt2nwdqwlld.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gt2caaqgant.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyqrwvkd.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2drfwcwdg.html

TS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gt2gzeqokhn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2fzjmaqvf.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2tjkiiqym.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gt2jtxbyldr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxhkpkz.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsjftujv.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gt2bdyjgyey.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gt2grydzupn.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gt2xeovdtvx.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2xcatbgmm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gt2qkicjawq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gt2llkywoxq.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2ccgagpuy.html


<!-- 参考信息 -->