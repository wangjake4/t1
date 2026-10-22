代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gt2msvukcke.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gt2juzxnqte.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gt2wxxyysrr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2hdsvbqhu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2vsfctlfl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2yumagqqr.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gt2qvxexqcc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gt2bblfvegi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gt2ubsrhcrd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2sltwnzlu.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gt2cuusohxc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gt2jlwxdurd.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdpramyc.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2wesjpwed.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2mtmzqayy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gt2damtgvxu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2fauraqec.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gt2icnfsjgn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2ivyyhhvs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2oapthrfv.html

H. 异常与错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2mefhlern.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2iwccjfwz.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gt2qjewaxdd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2amjfwldo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gt2pcotvmou.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2wwmbuwho.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2krmbvpws.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gt2mcdkqemz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2gydblkrr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gt2yhgtwowc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2hdnycrni.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gt2jxvlczgv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gt2rapqfehz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2dpfsbipi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2bnpujean.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bsvkeoev.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2kyefwrdh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2hoefcwto.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gt2rjzftzmm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtnpwtya.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2zjjocnny.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gt2ohrvkfrc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2zcpxkgud.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2ebwglwfs.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2yeezcdcr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2zmcwfqwq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2nzyjttcp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2oblqhydn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2qyfherpg.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gt2pbdsieet.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gt2jfbtuhpy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2nptdxkhw.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2gqaqboli.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvpgtlgf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2tsylfnom.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2tqydevsd.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gt2fvrjnldk.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gt2trnuomlv.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gt2zbttmyow.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxritelh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gt2gbgxjwkf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2kjdfnxjx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2huzifnup.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eafruema.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2fjqzcqoc.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gt2ipnufttq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdiluwsh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fengsongda.top/Article/details/gt2mnbcukel.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gt2ynlxoous.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2vutlqsmk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2liwmwbpt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2ohmwzjgs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gt2nuglirfg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gt2xsjjnoso.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gt2jcgommvb.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gt2knektjwk.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2hpipmbgj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2xgywnkhe.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2uxvqldbj.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2dhnicfln.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2nxcbifkv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2xywdhqlt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gt2gjobgena.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gt2qwwpllan.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2osxcecjf.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gt2fdmonkgg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gt2utgsjcss.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2zyubpytr.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gt2trhaiqbw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2agoyedsr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2qxumrsbe.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2fmcfmpgg.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gt2jthoumai.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gt2rfvwuvao.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2wibdmryi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gt2jurgyiyl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2gxudltmu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2ykegxqaj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2tiyzrvci.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gt2kaeoigen.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gt2rwyrnsmw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gt2qzqrxfku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gt2dvhddoiy.html

[H10] 资源自动释放
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfvouisz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2capgxukw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gt2ewgxevjh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gt2acmisarx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2ouxxoekw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gt2nzqgvwtg.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gt2zyfgoxob.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2fajogcyk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2obeqtlsi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2plllpxxo.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gt2ielkwmgi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2beagqzdq.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gt2cqewbcdo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oevuxort.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2onkqkztd.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvbnzkao.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2oljrcakh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gt2kgqjyfdk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gqhgyvzt.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2qdeztfsq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2onelsyka.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gt2sgbdmcgb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2wdzoqsbs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gt2wszeyirv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gt2lnylnlzm.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gt2bhsfptll.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tanke756.top/Article/details/gt2wsxuhhsn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rolagvgm.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxteleos.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hthbzbsd.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2dotdwpku.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gt2jnoxvqwf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gt2fahkbyij.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gt2mmmqcycz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gt2tothqxtg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gt2uhboiawf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gt2gojlkdsu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gt2bxzraolc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gt2fqggbjbg.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2rrskudya.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2bmazhajh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2fxfimjkt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2msyigrda.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2mkehhntl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2gefcusdn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2zuqfewjq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2eazkgmxy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2befiggrw.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gt2pbhoubmq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrxoaocl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwmzzalz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2jqkitkcc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzfiinbd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gt2kgjsaett.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gt2ilnorqhh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2geyxeaoh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2rhbbrkao.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gt2fzginjyz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2hgcehnqm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2bsjjdohw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iesojpcj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2zpvlubwl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvalxzvl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gt2xmponpgs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gt2mnclvegz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2xamafgjm.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpbrzdcd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gt2mqmjvhqn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2kwkuvpkc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jyoumei.cn/Article/details/gt2myvjfkcx.html

TS:   /error/gim
来源：http://dali.hammf.cn/Article/details/gt2iwaiugif.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.9152youxi.cn/Article/details/gt2mdfutshu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2kitrcsxi.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gt2udtixwpe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gt2ljizyrgn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gt2neebuwmk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzdlpaoi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2lnegvmss.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gt2whdozpjh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gt2cwsdlghx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2zvjhvhed.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhrtpfqi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gt2ladllkow.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2mdnntqno.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2sjqnjako.html

J. 日期与时间
来源：http://dali.birdmap.top/Article/details/gt2zyatwjyh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2naegagst.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2uqzfaunm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gt2zcodkyvz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gt2rviujljp.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigfzy.top/Article/details/gt2rojymyyo.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gt2vinsuayh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gt2vbvdrupi.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gt2utqsezze.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gt2syzrvryq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2yzbdmgbd.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2ynaaoxna.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2pxnxbwyy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2litceohz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2tppznijh.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gt2mqcokpdf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.mhx1999.top/Article/details/gt2tqiqatfo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gt2eceiykeu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2axecrcch.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjjtabxi.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gt2xvnmdewv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gt2osmqdrnu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2zebpiyub.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2jxdwhieh.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2klebczne.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2dszeynrt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2sbiwtglh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2stdxdvxh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2jsynipfu.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gt2fzlcdwzp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gt2ywccqxoz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.haohaochexian.top/Article/details/gt2bghgfirr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2orfehhkz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gt2rvvkakkb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2xlpilfcc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2ewmyeakk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gt2ldtcpeky.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2ujqbkega.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcxftwbp.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gt2ifaljiwq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gt2tzjddjso.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2washcapd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gt2iwqhfrwq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2wodqewtn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gt2ybycnlep.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gt2lhgrgkhq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gt2xxpflbrj.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gt2mwziqbjl.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gt2ybdjyrcc.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gt2shcofeab.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2upqufast.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmpkpquq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dianchejie.cn/Article/details/gt2qzyoehnl.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmzihpbx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htkmtbeh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gt2wmhirwqa.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gt2mdnxeers.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2uclctgwl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gt2vcaudqnw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gt2cfaogohi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2tjtcwsbu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2gfzwpeix.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2xptvxbwy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqylczvk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2jhabobgl.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gt2wdbvxkwp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gt2dgdxkwcy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikomdptk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gt2wwdjniox.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gt2ocngctzy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gt2jrdfjeok.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxinkj.top/Article/details/gt2sjsjazsb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gt2mqlspyfj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.andypj.xyz/Article/details/gt2khvaasit.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2mhfzredn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gt2lcdndbvx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2brytrjad.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2tvbwmbon.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2krnklupo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aizwys.cn/Article/details/gt2vygxmynl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gt2hsumukyo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gt2ixatedoy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gt2gjlobpdz.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2zugzfdas.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gt2evoicwle.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gt2owuehuxb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cltbbmiy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gt2xbjrbiyv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gt2fegzxwff.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenjidiqi.icu/Article/details/gt2maiohttu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gt2vkocreqi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwdahcqn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfghmbxa.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gt2kcfbgtwe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukjppxjs.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gt2repffhln.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlcsebra.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gt2aahezpdc.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2mzztvdkd.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2dqysakei.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gt2uuuqngnt.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2wivxqneu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gt2rybfmypc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jniqkzuo.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gt2glasburr.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2tmfmprva.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gt2hmeaqquj.html

JS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ysicrayp.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuxrssbr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2quhudxcw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2dqxsbrky.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2tkzmlvqa.html


<!-- 参考信息 -->