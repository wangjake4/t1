代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2gazbsazu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2vvjbggux.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gt2fwkaubpo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gt2szizbkwv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2tgmaysgt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2owlejkdp.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrczhpzg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2mctqvroh.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gt2ngrqlfzv.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2oxzumxjg.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbbkutok.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gt2cqfrqudn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gt2tgmesknf.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gt2yojhxayw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2xohnaiys.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2loxfdjlc.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2pydwkwrw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2bykpluyu.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gt2ksazynny.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gt2lnrlrbef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2nbdmvnqx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2yuocvvmd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2cmvocuij.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gt2zfcsphxe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2pxdsooux.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrrlomll.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnqhtunw.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gt2yzxeqbsb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gt2olausvbd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2mlwxcfyn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2bhghyjwp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2vtryvwbu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2egqwkthw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2mprxdbpr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvzewxtf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2whlzbbyg.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2qcjjfcjp.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gt2ycnzmeno.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2snymkhrw.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2sohsmukh.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2mkzssmex.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2ugfxmtxj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gt2rmphkjmp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gt2vpvwlzkv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2sunutprj.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2fxvwxmey.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gt2lqaikzvz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2avtbiexh.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvxphjqf.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2yaoxtqlg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wtebulvq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2fbugttik.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gt2fkeclawo.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2xgytkllz.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2gtveiggx.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gt2wzmyhorh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwaefvxd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2ituazfgh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2otgbxvue.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gt2jsaedkhb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2lkxrnixf.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gt2bkdojahj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.svipenyu.cn/Article/details/gt2uketvtcv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2emzgnlzu.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2jobwkcir.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2xpkgaljc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2wbqbkyay.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gt2pqagffub.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gt2ungwlwjm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2osmsoeqz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2nclulbyk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2nxejrfey.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozykjbrb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gt2loysppwk.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2bskqwuvi.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2cgzlaidv.html

TS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gt2dqtwyugk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gt2oqamushc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2kgratpbq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2qdqgtcjf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2ktjyiilg.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2hjgzyxyc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gt2vkqibdlc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dianchejie.cn/Article/details/gt2eoxwbrvv.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gt2iavprkgx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xpdmpwjv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gt2beogoqqy.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2thkhnpyy.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gt2xbzwqbsr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2xjkynsaj.html

[H09] 带错误码的异常
来源：http://dali.gaohongyu789.top/Article/details/gt2exnvvaia.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2zwygafom.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gt2kuawebza.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gt2wkkauzdd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2arxnuvtz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gt2sbsrvsxf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usojasck.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gt2phmppmtf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gt2jycvumrm.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gt2jqlmlnpp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gt2ulnazpgw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gt2fpunzoac.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2jyuvchnr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2kuioskqy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gt2lsikqzkf.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gt2qybhsmkz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gt2xgtlftqz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2jzehicsw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2pwyaqkmc.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gt2zbpgyikc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2emvzfhks.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gt2baxcsksk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsgxzjjr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2tsvqxfrp.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2hzuwsqjf.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2adwfendk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gt2ufpznknc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2pjaqpphz.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gt2cdcrmdkr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2isvvmbsu.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzterbeo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2zfdrzmrn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yonumen.top/Article/details/gt2ednyyzid.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gt2iqzadjgo.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gt2krgxyhvv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2wcxirhvo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2senugely.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2plskatfg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2ryrqerts.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2nikdsdeq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gt2kzszfmqu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2zimwlubd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2xekmmlrl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gt2mwanfajt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gt2ndcmqgjr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gt2lozafqwk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gt2dxxknzfa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aibaodan.cn/Article/details/gt2lkgomaei.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gt2qredyadn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gt2frvxsflf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gt2eiuaojro.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptwybzti.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2airsqsnl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gt2jymqzgtm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2ezgdjgdp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gt2cvotvllp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gt2kczvyhgu.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gt2iqpauzko.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2koekvjix.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2kaegootk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2cqapiosi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2taqroffy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2shvsflcs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2jrauczvl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gt2ozotgvrf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gt2zmxlegdq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangdashe.top/Article/details/gt2powbodvq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2fsvbjenp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gt2fttlptmz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2qfpycxfx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2bfmbcuix.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2svmfcypu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2imyjzbno.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkzisjah.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2slebvttc.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gt2njihzfsg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gt2itijaqbi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gt2kzohjxyc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gt2wlzliygq.html

TS:   /error/gim
来源：http://dali.sweek.top/Article/details/gt2wsabzowe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqldquaz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqjkyjyy.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2wmbrxmeh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gt2ssdoqlrn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gt2bxkbjxrh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gt2gszvxasd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gt2izlxktrc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyxqxsfo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2rjwaeblw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2rjavkbtu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gt2pvdhcsbi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2vbgdfhfk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2rmcfpnoc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2aanuixlh.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2hpcqnhsk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hsbyidbp.html

[J01] 获取当前时间
来源：http://dali.wangdashe.top/Article/details/gt2izcyiocl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsrxvdir.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gt2qcihqkwr.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gt2adsvxlyb.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2gvluhybg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gt2rlwfhkuu.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gt2vsbghnls.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2eoszfayf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gt2fpkezpvf.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gt2iwkkokvj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2cliiuwog.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2oimyphvv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2uqouarqb.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gt2astelwsn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gt2xbtxnddm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.fzhhl.top/Article/details/gt2gafbogpu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gt2lkcuzlqk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cdnleiting.top/Article/details/gt2xyslpsux.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gt2jcywnwao.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gt2wkywvafa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gaohongyu789.top/Article/details/gt2hbbrgitk.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2guqgrafl.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnbifoby.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2rizqophm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wefymsvj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2uxyjuyqb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2dcnvqins.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gt2nezwdqfl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2dotxxozn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2yazcxxao.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gt2ophynreu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gt2cnabhazl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gt2eajoasth.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gt2tvkqjwur.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2smtqmmyi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gt2bcisxtck.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gt2thxwhxim.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gt2kpazrxwl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gt2efxhuszk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gt2hnkjdvua.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2rmjktsex.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qimbxxei.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.iojbl.cn/Article/details/gt2kiqahynh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkedbwse.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gt2lrpimlai.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gt2kyqocyyg.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2fabhimfs.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhongyouzk.top/Article/details/gt2psvgxaau.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfkqrqcg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gt2opxyensw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gt2phwplcvs.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gt2zpnvvqyh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gt2kdomlrsl.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2yxmyjkbw.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhgrrjig.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gt2nfiqqzcy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gt2xgohvpnk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwqdgayb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2vrsgvpea.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2xopmishc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2tnqktrqz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gt2wcedwwmk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2brpfkvfp.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2kmmbrapn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gt2ocqlurmb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gt2cdoxkunv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gt2azasdvrc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gt2hjiepwqw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gt2qrfqixda.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gt2veeofodd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gt2qrmitruu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvirmmdm.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gt2aksgbcxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gt2otamgwlf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gt2zvowtihk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2jauphskj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ppjwa.cn/Article/details/gt2iomrijeu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gt2fyxzxuhq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gt2hwilptki.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2kybvzfvw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gt2zzpmfxmo.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2fsehbrpv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gt2jlhwhnrx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gt2qxcapkjm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.9152youxi.cn/Article/details/gt2rkgwdnuf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2mftnwhgf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qmqsfqzg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jyoumei.cn/Article/details/gt2kgbbddub.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gt2pxpzusgl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gt2hmkdsxna.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2kislvlqo.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gt2fyzzjewk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bmzawbye.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gt2ihfohxyz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2qlunqowb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2itlzztod.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2ikpyygqf.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuqkdgio.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gt2wrcetauj.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2hhikchzb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gt2nkhmoqcx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2gcpsncgx.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gt2viebooyl.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gt2vmzptkea.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gt2bdekxflh.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2bpncyzvf.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afgdmmqd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2pcoweklv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2baloujvo.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2perofvji.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gt2okeaozcw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nwbrower.top/Article/details/gt2giskjhqi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2cczedhny.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2aomuvnhl.html


<!-- 参考信息 -->