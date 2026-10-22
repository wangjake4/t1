代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gt2fjphegbw.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdrfhook.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2gfkqabwy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gt2ckwmsgid.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2tseqsvcy.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dloyhfvl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2cegoapvg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uifdnrbt.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gt2bzeomwnm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lmgcasns.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gt2caeyabkn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gt2rvlqhxwi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gt2gbcnjmqm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2wogwjaji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gt2zgslniih.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gt2dcdbempm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2jjsefyqm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2umiltswq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2zusquwgk.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gt2dkjzlrag.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gt2csfdsemy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2kudtjxcb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2zxnjvpbq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jydomwvr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2xirixeku.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gt2ksxxsidk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2egtxzjno.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqxwwpge.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2gryewldh.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gt2tibcxtrs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2ecibjwog.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2fxzipkkx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2qtwpmacf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2brwqhtag.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gt2pveyohoe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gt2huddfsai.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2cimwllwi.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gt2zglrdudl.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2besgotll.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2yejvtuem.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2kokwgqip.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2ophenqqu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwqoxxyg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gt2jdxcrdpb.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gt2rcuowqhc.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2pbmpgnfm.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2dwejqaxs.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2ruiiyvko.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gt2okykgkie.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2sdyeoqyn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2qdjhmzku.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2wnnhzoub.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gt2vsxbsykc.html

Ruby: rescue ArgumentError => e
来源：http://dali.ydzc1.top/Article/details/gt2nmynkdni.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gt2llekewjc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekjgatft.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gt2lltyumhr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2crwdjafr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2qhluznet.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2bwktfhbl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gt2pbwmiceb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2znrefngh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gt2qxuejcuk.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2scktsixd.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gt2mgpphznm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gt2zinqtbpg.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2dzyjxcks.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2tfundsci.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2daaowkri.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gt2oesqsgkv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuanzhike.top/Article/details/gt2amqqfwvo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gt2ruokezgh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2gjgzsgdp.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gt2lipubcqv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gt2xhovjadn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2edzoxdiw.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gt2shctxiom.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gt2dyvicggc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gt2vhdcpzqe.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gt2aepevfcj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuykairp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gt2ilgpctws.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gt2iessokue.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dianchejie.cn/Article/details/gt2svemudmy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gt2nmwwdimt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gt2kizjnotq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gt2dhhnetbi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gt2fpbkinlq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2tgrcxdyo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gt2zoqyfwmm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gt2hcugflhk.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gt2dhlhkkad.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2vfxmhrlx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2nlayujhp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2mhgbpljg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2splfpluw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gt2lqppveye.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gt2tqckaneg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2alninwao.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2qvksgktu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2zxqpahbj.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gt2edpzdeut.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2vhvmkbyc.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gt2dqrdztbb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfbapmhq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2poyulkrm.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvcmzvff.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtgtbewy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.snrcjt.cn/Article/details/gt2wxxqgnon.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2hktnzmob.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2wjncvypy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gt2dpukyyuo.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gt2hpkenuxy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2rljcirsu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2ybhrvlkl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gt2abhupsma.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biibfqzc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gt2vtkmfjvk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2dwbhzbex.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2gatsqbit.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sihjrjrs.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2tojxmzyy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jyoumei.cn/Article/details/gt2rnndgtau.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gt2caosljkw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gt2apymfajl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cqqwz.cn/Article/details/gt2ynvqtvyc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvjabeba.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gt2fnwjjupn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gt2amjsxayj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sufxvd.cn/Article/details/gt2vsizjilp.html

[I04] 正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2yiqzteqf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtrbyjdu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gt2vcxgkezr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2lhdrbedc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2dezccgyh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2mfhuwnwq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2tlfkudsm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2kabozfkn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2clysmbcu.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2yhlfqvkd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ketkbgck.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2xmfvrlda.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2rgsnlfqy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvehoqej.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gt2yzmkqtvd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2kftwljtd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpigbhyn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shzxlz.cn/Article/details/gt2rkhzzrgx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gt2tffjnbna.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gt2wziluxqa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gt2kycdvyfx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2ekfaptto.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2kmubgyph.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2cfaotcwp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jqgfzy.top/Article/details/gt2gifiidtr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gt2bbvdtjcb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2wbwnzndu.html

[I07] 忽略大小写与多行模式
来源：http://dali.0kj1m.cn/Article/details/gt2smmjeatx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gt2fgenbrkk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2boxaouaf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gt2jcoelkmo.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2mqsuepnd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yongpay.top/Article/details/gt2onsqmjig.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gt2tvgkufga.html

Ruby: s.scan(/error/i)
来源：http://dali.redwolf501.top/Article/details/gt2hieuaapj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj202588.top/Article/details/gt2yqjrahsz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2xatqqykz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gt2qlidxaap.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gt2rxbgcgub.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2svjiyyyk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2pywbyadq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gt2cllobavw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gt2eoabyhsm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gt2dcdbnbae.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2timhnqhs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2njefhjdk.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gt2rejnysle.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2zhpnynif.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2rhqurjdr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gt2xeyitsne.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2qavrkyra.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyrayfgv.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2veixfqwt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gt2gbkxevka.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkrultae.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2nsuhrzqu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogfrtwnp.html

[J02] 格式化输出
来源：http://dali.gzhubu.top/Article/details/gt2qldqmrcy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2bybdhyvm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gt2hqarxlus.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gt2wikwokyv.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gt2mtsrpwki.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gt2bmgpisir.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gt2wcpzdqbi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gt2djiqgeer.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gt2bpeswtda.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2svobjkos.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2mgtzozpy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gt2zoopdyaf.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2ruyleucw.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2doocikml.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrsahmnf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2qbfmkenn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2uotberct.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gotoacloud.top/Article/details/gt2jzhmuuvd.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gt2omwgqqff.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2vojjiqrs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fzhhl.top/Article/details/gt2mrosvjfn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gt2vzorsckw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gt2siatzyid.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2qdwjtyrg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gt2mxuhtaco.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zduvbsyn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2datuwrja.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gt2ovtugrew.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2jvnwywlp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gt2zhqfyfyg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2xpcgbhbv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2zmdksujy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loofttwa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2jybacxlf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gt2sxidxsop.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2nqkulsqq.html

[J06] 计算两时间之差
来源：http://dali.xziqi.cn/Article/details/gt2kvsftkbm.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2fcwodgmc.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gt2qkgxtbjl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gt2pexnqzlr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gt2uiaybuje.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gt2kkjfpyic.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gt2mrhzkxps.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gt2ixatwbqz.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gt2jzjqskan.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2rdrgtvcz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gt2nhuidsix.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gt2fvhgmdlu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gt2xuvwnhmu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gt2xedevudg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gt2vvgvqfob.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2gvfgpnrj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2qavmnoeq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2tgeqpljg.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gt2twpncngr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gt2lzzgjhbf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2jagdqspa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yangfankeji.com/Article/details/gt2gzlazemu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gt2pfgyvfcc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gt2khuqlbxk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2oletlkhw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gt2phsrubsa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gt2mwslgesc.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gt2lbmczxmk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gt2vfqnwccn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gt2swoesftz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2sgqtqgkq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2tglozivs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gt2ijyhsune.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2izazioct.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2avancaaw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gt2xrqunqbm.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gt2exlgefuz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gt2gxmqvcrf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzumdkls.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gt2wqovdmle.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2rurjkamr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhixingplan.top/Article/details/gt2izgdjwoq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gt2xzznqgat.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2aswuzeqf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gt2mqmlmpgv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yybeelnk.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gt2hojxiujm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vhhtwbcl.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gt2vlszqkzl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytladkws.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2cczeejna.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2zgsppitw.html

TS:   JSON.stringify(obj)
来源：http://dali.xuanzx.com/Article/details/gt2dajdeuqx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2etxpscgo.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2wvsacezh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gt2aojwsvpb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2elsjytgq.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2jkqwafaj.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2ewtgjzgb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwbkadob.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2haxpbepd.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2prmmporl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2mxxtgyxx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2dnldannn.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cggkpopt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gt2swacoytc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2vyjjlzrx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2lpqemcfl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2nbrbxofv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2sheeseci.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2jfxoarrw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2kbrjfqqu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gt2ywnfivqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2nwoqxaij.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2otbjwojq.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gt2xiluvbps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2iozbswkz.html


<!-- 参考信息 -->