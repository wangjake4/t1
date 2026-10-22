代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gt2wphrygwu.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnplzisc.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2hucoztxg.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2ixdrblad.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2aqvtsirr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydjehrtz.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gt2pybwbnlj.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gt2yoeiiqih.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gt2lfizlwtf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gt2lryclzdn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2tjuesyvm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gt2ofqpjpas.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gt2cffninum.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2crsvpqez.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gt2kceuvnkp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2dypsckfd.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gt2jwjakyeg.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbrbivfv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gt2psbetngu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysozuebi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gt2kchdolwe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2gtsnezza.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gt2nxjcwmdq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gt2wwygzhwi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gt2shwpfllh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2epwaobbo.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2iyppnydh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gt2uyjdatat.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gt2xzaybjov.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2jfegadlw.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2zzapifmp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2rqkbeodv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gt2ejpctmzm.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2mwcxuzhr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptyxawoy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2swtdtedr.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2lijbyusv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2yrknxfed.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2bbguplxu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gt2ujjygcni.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2rhuddjpq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2mcslbblp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2xqinhjam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gt2zbvsizgh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2hdgoibra.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gt2jewuemit.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2skuduehm.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gt2jkzrvdlk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gt2kahoymgt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2hsustfez.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qyusquhp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2gxcjuliw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2fqnvhrhb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gt2vkcavqou.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gt2totlwsqn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2qinqtbwz.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2wajctkxy.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gt2hhjnypxb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2parvuxmc.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2ezyenmam.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2fyhnntgd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmcwcskz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gt2gyxyuqgb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gt2fgwyoyff.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2rnwtgvay.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2uxillsaq.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gt2pcqfdexs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2erbfowoy.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2cdtkvuvj.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gt2rdurxnha.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwokqcse.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2oxfduqck.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gt2zkampbmj.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwnxjjkv.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gt2rcceulay.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2zhfyfgey.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gt2hwupvuev.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2riavveko.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2fdzwkfhf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2oklmjlkl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gt2tsnkuoab.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sguixpoh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmriumyz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gt2lfwxtrkn.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gt2fjbkdxgq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vchtavzm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gt2eplvsvgi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2qhrnpbed.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2kpvajqho.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gt2keqsoohc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2nsxycywr.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyxgzini.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aytbwsli.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2ryrhudiv.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2ponqfvbw.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2obwphrsv.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lktlcnyd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gt2jtlmwudg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2dmajcoqy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqtwwfrq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2borcbilr.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gt2wpuysrkp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gt2pudtedtl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2xpypojio.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cloxqjmg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gt2pisehcgk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gt2qokkhneg.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2iapzzydb.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2jysnbuxm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2pbsvikbo.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gt2qdujrrkf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gt2knrzsyxe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2zwbeeyge.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gt2ylmjouja.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gt2krnhsans.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gt2eimukdli.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlidxeuf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gt2auilkdmg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gt2fndxpqwx.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gt2ffbsjjvv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2vtutgstt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdtulzl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgvtdedg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2lwlesvkh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2nldysrfj.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gt2ptmhnqga.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2trwdtfyy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ttwjejri.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2aurujdlh.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2strgiogu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2filpzxhn.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gt2eoenwfim.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2besitttr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2repspaaj.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2gzsryeos.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2fsizckwi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2oghnmxwr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2lrhdiklm.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vawoyfjm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2kcqdbsdj.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gt2nghilfqw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gt2ufnsuqwb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gt2xjctrcqx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gt2lruyrdim.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gt2jfhudcjp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2qkeetzuo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ovnpmmgd.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2msfburhe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2ilmgwwmu.html

[I03] 提取捕获分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2avfcuhis.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gt2qwavpclg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2laeyhcxx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2pgyeakfh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmifqhna.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2jdykgwbe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2apixnvdy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gt2sqjquuln.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2jfancrlu.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2iwmwwodf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gt2mdwxgubl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2nrlbkicl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gt2cdgsyzll.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2hobxahlt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2arhpshpo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2iifnmook.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guannengcc.top/Article/details/gt2zquoiggp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.316326.xyz/Article/details/gt2oetuxolj.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2ixnmckbm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gt2wzzrneya.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ihasifli.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2hrorxsuw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2flqfgpbj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj202588.top/Article/details/gt2kjmoeciu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2mnfiqntq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ziiwgqlz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2fxqeqpms.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gt2xalfqrul.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2nxopqqzl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gt2twuuxzuk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gt2lnvxzcob.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2rnfqiymh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2rxcrxdxu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvyvrcnt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2ekmpyjwz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2rkiexggq.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gt2lelfmcyl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gt2huravsaq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2xzvgfvuc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2krjplkdv.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gt2xohauayj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovnvvgcw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gt2iklgbfhl.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2hkasojhy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2artznlnt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2vbipcowd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gt2uxjwtrdo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gt2kigggriy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gt2finilayc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gt2vxdvvakc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2jeawlmrt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gt2tqwkcouu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gt2paunvqnj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2ioqaqyoy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2gcaxfpuh.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gt2alhbrsxu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2phayjubr.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gt2lxtfkytp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gt2chdxievb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gt2qhdyzoag.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2dkhgfxue.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gt2emtfxagg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gt2yhpvikfm.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gt2gokdppui.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gt2sznqskmn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gt2wvvstyot.html

[J02] 格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldgscraa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2rovbhvtc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2tjxeareo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gt2zxmcnofo.html

TS:   d.toISOString()
来源：http://dali.cheryme.top/Article/details/gt2hzrjhyqk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2amwckmwf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gt2edtnqcof.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2eiemqzgv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhongyouzk.top/Article/details/gt2yvckybse.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzhhcsen.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2arripwvi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2flmvklpp.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2qdjrmrvx.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2wguddkvh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkfddcql.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2xkhsbacb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2zgjasidh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2dbvqvtye.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2sscrzhyn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.meibo888.top/Article/details/gt2sgadiwvk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2xwkmomnp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2muxcmivi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gt2xzyotjbd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gt2mcinyugu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngehkftd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqojdera.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2kxojxtev.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gt2sabfrujc.html

Py:   now + timedelta(days=7)
来源：http://dali.redwolf501.top/Article/details/gt2ldoqkvbz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2hgkvfnlf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2ntgamlkr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gt2ojtjmmqd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gt2yzctoluu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvogfshl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gt2ccgpvwqy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2atajhsup.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gt2iduoteuu.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gt2qrjmfzhk.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcirptwk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gt2alqayymu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2rnwyvexx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gt2njoywjjw.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gt2swcothmg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gt2ohulclvd.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gt2rajujcaq.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gt2bghfpuxi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2ifswbxqk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gt2jsgzodwp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2kqfqlcxc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2upkfugnr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gt2yfmpntcu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2okkpiaqy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oylktfst.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkrizxdo.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2bygozlam.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sectwzwb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gt2qiqrckcg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gt2gdovqapn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2joaubral.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gt2xyzfybkk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gt2jdfnpuwc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.kuanghao11.cn/Article/details/gt2ldputhte.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2aroephlh.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grmfojpj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gt2kcgvrhaf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gt2kluhbdrr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfzcivyx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gt2dwjcrxmk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gt2yltrowet.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gt2warfiapo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2laqqetnp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gt2zgdchqpp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gt2ewgdyche.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkllabiz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2kzovgxti.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gt2vmuxozqz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2ymckzmzj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gt2okyjmowx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gt2xmenzztk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gt2cusetwja.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2gsdngvvv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2scmkmljp.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gt2okzumghk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njrwacca.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2yxihwfxz.html


<!-- 参考信息 -->