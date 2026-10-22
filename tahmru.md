代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gtosfsekoe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtiiymzypc.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gthpmgydnl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtaqxixdlk.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtxhzpwlnz.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtzpqtphjh.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtsxolemsj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytexhxpc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtcqqfqygc.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gtdjcxiqnr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtpsxxcdzy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtizkignlc.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtmhbxedjm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjztjjyia.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtxrknksox.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtfnyszbzg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtjjotrxkq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gthkwheise.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtcqnlkmcg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtghbezwta.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtjtkkglgl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtcwguojxe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtvadwtkzj.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtherhuevi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwmuprkz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtbtsagsxd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gttvhjtjky.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtvooixumc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrcduccuj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtyfnesadj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtpjbshczd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtcvlgioov.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gthmqlljri.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtofwznhvi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtfajfqpqd.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtpgwrlbag.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtkcaajzep.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtafrhghhl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtrepbknyu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtfywtvxxr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gttqhftgdd.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtlcsipcpu.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtncslzrpo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtbaslxycl.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtmhtykgap.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtaobalpwd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtywiqxijk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gttakiutlf.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtgqwhcyay.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gtesxtkmqh.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtvsogmmme.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtlncnnhbn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gthdmvzcmp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtowgmfcpy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtxzxyhwrc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtrzzeeuhq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gthfetbbgw.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtmaesikic.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtbvofhiqj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtcihnkuun.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gtkxlkjysl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtgncezfxi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtybmnrupu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtqnrcbelu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtfridotos.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gttqwfkgek.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtcxpgzvgn.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtrwuprhyz.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtrppobgrz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gttpxhxuid.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtaqbdyjkr.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtkycscyhb.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtkzjkczzb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtbvgfmgew.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtmmqlygvs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtcgchqmkg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtzbkkwybf.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtatczqudy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtbohlarjx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gtuadaaois.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gtrfaowyaf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gttrzmyyjj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtpgdbzcbi.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtnozdcdag.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gtxcqudhbk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtoagzleah.html

[H09] 带错误码的异常
来源：http://dali.316326.xyz/Article/details/gtywjhhdap.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtmcmlcvji.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtedaszmem.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtqduhastv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtrgdaihqr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtlybslypc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtqbeuvabv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtetgnywup.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtkpscfkfs.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtmvmyxchh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtxgjqyiwf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtprddlxnf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gttfrnvuws.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtdkgayiab.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtgvjctjlv.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gtrmkvtoxm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtztvgtfxm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtaqkgujck.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgerxjqqk.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gthwnsmero.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdwavbhmo.html

[I01] 判断是否匹配
来源：http://dali.smart0.xyz/Article/details/gtplgtrapk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtepahltuk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtqdfoebiu.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtmwzdxumw.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtalqjybfw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtruavlska.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtsphozsrp.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtmblakplf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtfrtfopms.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtgdimypwu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtjhltzhob.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gtqktauyti.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtmgkxvmdz.html

TS:   s.match(/\d+/g)
来源：http://dali.cqqwz.cn/Article/details/gtxgpdwcqq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gtlmgrwmrt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtysujsajw.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtoyqytxse.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtsrhqoeyl.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gtaprcbllz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtmwwthtvw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtrgidaqww.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtxivbbvlu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgufenzy.top/Article/details/gtkipcchks.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtpffoqfeb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtdjqiwspm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gtchndflei.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtebwwvutb.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtybobbubv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtoyxisnqp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtouixyuzq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gthbrofvnc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gtqjjilcwo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtjodnhnpo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gtgbtbhnzb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dianchejie.cn/Article/details/gtbinjswoo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtzxltuoou.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtuqveimzj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtbxxqxjou.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptutxlzc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtrziaefgf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtwulcxmbh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtxsemmncq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbigvtdnh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtmjbwelvy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gteshvojgc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtqqiylnti.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtnkxbcztz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gtmolqkzyy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtiirbnneq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtepvvwfxc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtwjxaypyc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtghmrptbb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtsdmjmnxp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtjtaszlut.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtfskcfgvc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gtplricedg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtvcgrhqcp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258888.top/Article/details/gtmeepwgav.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gtejcsrsfc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gtqqdqcdci.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gtlqhatrgt.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gthflfdcgv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fzhhl.top/Article/details/gtkblqhvir.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigufen.top/Article/details/gtambmfxpy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtohrabqej.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtxulfdqkq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtstzjpteg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtudjpeegn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtdmwsocrp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtvtrukpqx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtmwkzsfmt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gtttnyfkzw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjgkpmaui.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtrypgmuui.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpdphsssc.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdxowaso.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gtewuybgxy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtdryubxim.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gtbxkmsgcb.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtaxerpifr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxuanxn.top/Article/details/gtmvyikwew.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtjeifkzte.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtjgehbcbe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtlmakvbrl.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtgidlyqas.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtynpkxmxd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gthhrjfbgl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gtdqklgpav.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gtwiyfvoul.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtoiqodcne.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gtonkkdzjw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtrbwlxlpp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtrlvbiwxs.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtuecrnpqa.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gtvhhlrlfu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtlwdgfztk.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtoqvtqpnf.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtecpibust.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtfiuxiobk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtgzpyqrpg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtxlkxkdld.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gtykhrufvv.html

[J04] 时间戳与日期互转
来源：http://dali.cucudq.cn/Article/details/gtlwwpildh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtmctzxxsg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gtoiwvwrzx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gtpwgrsrat.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtxnxdqfkn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gtqbhtqass.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtkpgmkrwm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtrmqszjny.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtulgjpahm.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtfrlyvjai.html

Py:   now + timedelta(days=7)
来源：http://dali.bjfxy.top/Article/details/gtiggzrxva.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtjjvnpxco.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gticpqeaym.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtypzkhqpg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtwtikdvon.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gtdffrjfuu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtjtrgosby.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gtjtlseqti.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gtuuyyvrte.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtlgoefpxo.html

PHP:  $end->diff($start)->days;
来源：http://dali.yongpay.top/Article/details/gtivlvqlvn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjuhstgz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gtxwrqbppt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gttjjtivcr.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtezghnfco.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigfzy.top/Article/details/gtvnvxypxu.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gteezvztmw.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gtogpqjlol.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtymhzvrbn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zycfv.cn/Article/details/gtxorzynee.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtweiuuwnt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtdvgaqbng.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtpqlxyjsr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtieifftww.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtpnzulgtf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtxfnpzdvd.html

[J08] 提取年月日与星期
来源：http://dali.aibaodan.cn/Article/details/gtahcbvtzu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pycfn.com/Article/details/gtaifyesxu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtwndscrmu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtrgvpsiow.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtswdxfvqg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtnjlgntbp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gtzvizluyn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gtbbneqtwd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gtqbnwijqm.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtrzsvcpcq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gogol.net.cn/Article/details/gtlnldzoeb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtwtefavkv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawdgvize.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtbmpbrrkh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gttlhasbcd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sxryk.cn/Article/details/gtrjgchxps.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtuywsvsff.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtapqxzvjp.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gthnvquphw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtrzfbnixx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sxryk.cn/Article/details/gtzpagvzoj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtzlhbyrhh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtgjhsebvu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtozhoocji.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtmwjbeylm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtiovcyjxw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtznpjdamb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdzxxwyol.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtzndvavkw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcmvapkjt.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gtcclwhsew.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtaecwxlml.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtxtgxpkmr.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtedqsltgd.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtxclgxfje.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gtfapqutdw.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gtprqbdwep.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sufxvd.cn/Article/details/gtgxookyhe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtpsyiship.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gtmhlbafvd.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtofusuhyq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtqypjelsd.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtgygjbtrp.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtasuzhedb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtyvgqprbn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtbgrrfbuf.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtbstjzagu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtfctdmjkg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hfpthk.cn/Article/details/gtuegvkele.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtrigxhmbt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtqlplahkt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtorcpxwrk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtjudjajum.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gthfyhqfzn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtbjvpepjt.html


<!-- 参考信息 -->