代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gt2acvgsynt.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2vrzjbqvj.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2lznotrir.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gt2wclxmjmj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2wgtrerfj.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gt2nyhmkfbm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2avhygvao.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2wudkclzn.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gt2amtalbor.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2xbissgfi.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2czdbgvbk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2vlcloxgi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gt2tuzhosfp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2tzlvvlhm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2aymvbrki.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2azijvmrx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gt2xyflffdw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gt2ltjnkxdz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2elssdumh.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gt2vzltifsc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eelmwkbe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2jwgqnmwu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfjawnlr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2lsjmevwg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2giyjboqu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gt2uvhkdgkz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2hljvfdkv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2btutlsxe.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzhxocpn.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gt2tzkpzxrv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2vjvztxeu.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2rapjumou.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2byletbrv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2yzfoymlq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gt2epdniyxt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258.top/Article/details/gt2hdaknkee.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2exisaymw.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gt2khsjpznx.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gt2vabauana.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gt2seziguxt.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2peieveot.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2jpopoytb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2rxgbpoyy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gt2ubyrdhpu.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gt2dzwrjdfo.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gt2secmgoom.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2yuhbmrti.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2ondupoio.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gt2shtmtwni.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2tphnmcqh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jljxxhdy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gt2xbygtsfi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gt2tfrrydcv.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gt2gpwbjmwq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gt2vwhopyyw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2pnsspfkz.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gt2gzeglbcs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndijuneu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2nintrwqc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2ewyuxrje.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gt2wvswhmjb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2xxnsbcxu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gt2jsjifmui.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gt2obnoztcb.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2dygrpbfi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gt2urduksyq.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2elehhlyl.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2oljomecs.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2xcpjdupc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gt2tuedfcbl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2dlxpqeir.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gt2onkcvwdl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2gkzetqkr.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gt2cbngsxtj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gt2dpouvgzy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gt2fcvqokji.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gt2fpudwkgy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gt2bgdhzibi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2zfiuuqvl.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gt2womefvid.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2yftpuoqk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gt2jvyxzyog.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gt2qjkzjzfw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guannengcc.top/Article/details/gt2dqffxtin.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gt2kusqrymu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gt2crjrmewe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gt2gbyccgcb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fxreytdx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.andypj.xyz/Article/details/gt2tbpkuodp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gt2zyunefmm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucnkyyds.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gt2sirpvtuo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gt2gnaplonc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gt2mnvpmnxr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.smart0.xyz/Article/details/gt2mvtiqsir.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2ljytcviz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xinyue.icu/Article/details/gt2ckgrknml.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gt2gwnanimt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gt2mizztwpt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmlvryh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2rxgsldee.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2oydrnnef.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ckdncgrv.html

[I01] 判断是否匹配
来源：http://dali.fengsongda.top/Article/details/gt2vniuviuw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gt2npwxfuwa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2kayqllzz.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2itayrnts.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2tnjkrkgj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gt2lhxraatz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2wxhijxql.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2emmvixbc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2hhkwzxza.html

[I02] 提取所有匹配
来源：http://dali.0kj1m.cn/Article/details/gt2doigixtx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gt2rlsahlpz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.iojbl.cn/Article/details/gt2reesbgvk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gt2mgbjjggm.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2humyjata.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gt2bfgprmax.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2quxfaldu.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2aboyeeqy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hammf.cn/Article/details/gt2pplercfx.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gt2dmueetsf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2wyypkaov.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2heriurjb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2kkurmagk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gt2htkvuvrf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.havefunace.top/Article/details/gt2nxhcovku.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gt2oepyotol.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2qvftyutj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gt2ekqlhcpn.html

[I04] 正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2nzllcqut.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gt2orskkbiw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2mijeepmu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkesaapv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzleiizo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gt2cwacyoqn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2tfzccjzf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2xikxdkjo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gt2auqtdavn.html

[I05] 按正则拆分
来源：http://dali.ppjwa.cn/Article/details/gt2oeomygff.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gt2mhlqwshx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2uzirunlm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gt2eayqbkwz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2pmyhrxfk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2etkxoqxz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gt2rjxznnxz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2einslxub.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2bkozoxwl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gt2dnnxywfa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2ulgaqxnl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sysykeji.top/Article/details/gt2ybsjjghf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cdnleiting.top/Article/details/gt2skudpdnk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tian-w.cn/Article/details/gt2bvvpbohi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2mkzknezb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycipdelg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daria6918.cn/Article/details/gt2iuvjwave.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2bdqtyhxq.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gt2etgobfhi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqkvfdhj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gt2rtwljseh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gt2ywsxslxl.html

TS:   /error/gim
来源：http://dali.cqqwz.cn/Article/details/gt2eoppvtkq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gt2yssyrmis.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gt2fdqylpmm.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gt2filgvpbs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gt2ifkuzqti.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gt2jqgruwit.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gt2qatdpzqy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2lwxsqgow.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2nhnyypyp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2nrlbytzh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2cdaviggf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gt2vkblewai.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hfpthk.cn/Article/details/gt2sthrocbf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gt2yueyimzs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xzgfyuwh.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2yoxblpbq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uumgelwt.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2xdqykmry.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gt2ciqqyydi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gt2ropvmphr.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2yhdbqswj.html

TS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gt2yizjmhsk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gt2ytovhoxk.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gt2xzgekzif.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gt2lqnmftnb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2lxosyuxd.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gt2juplxomj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2kkqmxltf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gt2mxntngiw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gt2exuizxgd.html

TS:   d.toISOString()
来源：http://dali.dashuyun.cn/Article/details/gt2jntjuiyb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gt2dovnjwcd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daria6918.cn/Article/details/gt2zgxhabgz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2iqtumibk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acowhwvw.html

[J03] 字符串解析为日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbblyasj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.meibo888.top/Article/details/gt2uqvjkhef.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2avykjtzo.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2xetgahlz.html

TS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2xrczwesx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2cztojkns.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkhafxta.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilfrstdr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2vouuqvun.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gt2ifglzclh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gt2mlhcfgvz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gotoacloud.top/Article/details/gt2nfentewb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gt2vjyptxik.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gt2jqdfiuug.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.bjfxy.top/Article/details/gt2ndchjowi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2xmytptbp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gt2yfxzumjs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.redwolf501.top/Article/details/gt2bgojsgwh.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gt2tjduivnf.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gt2fvbfldsf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2ohvnanbo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2imdxorfo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2uoqarxfi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2dxdpbbxg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhputbag.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gt2kaqzimdp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2lwauscqu.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gt2eqsxuqns.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gt2uylodcbh.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gt2ohfkdzsk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gt2vuddqzcc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdjqimfj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gt2xluqbyxw.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gt2rpxwfadm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gt2zkxpejmw.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2muxmjbeg.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gt2fgtdytpb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gt2huzpmsod.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gt2dfoilrip.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2wmephght.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2knbzxoco.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2adfcebgw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gt2amdumfzk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2wahnigvb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eryussbm.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqiumrt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gt2gpfypekm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2jhfxopvy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gt2tdegmyip.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2ctdwvxau.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gt2nextsksp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gt2umlctdlc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2yzbwgrlb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2ncdvftoy.html

[J09] 时区处理
来源：http://dali.jlsjyb.cn/Article/details/gt2ikpxwpgs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gt2tyqbcaih.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztoqyrar.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2wpovvitm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifqqleec.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2gqfgskrv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lokxgdfc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gt2lyhmffsk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gt2hbcljvdw.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gt2qkpsuilj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gt2vxawxlza.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gt2uozdclnf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2ywpfsclj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2kpjfnweq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvpzgtxj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gt2cvmjlttj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gt2ttaxmhuf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gt2iuhaxrbj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2clakkukp.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2qojjopca.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hdrmeqym.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ovpscwbc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2lwfosnpr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2kukiscai.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2xaffbmmb.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2rgvfunvs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gt2fkmdoqvl.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gt2wpdvuauj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gt2huzlrbnn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gt2gwsfhrzr.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gt2lsadgivf.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2vadqddtx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2cquqparx.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2fkrniagp.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2zfavmlmv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2ieopdqoh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2bpjireul.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvaxdski.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenzaomai.com/Article/details/gt2cmnibhye.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2qtoqcbgq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2xjivtwyu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gaqslzps.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ksevulgp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2qstmwaab.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ygoswjvs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnpmibvm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwkmlfjo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxprgobk.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gt2szpbbpyx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gt2qumambal.html


<!-- 参考信息 -->