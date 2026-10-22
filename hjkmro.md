代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2pkpxzhir.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcqpgvkv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2syubiwwe.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgmimbzw.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2ctcklwkz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2gszfiisf.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gt2drgebksu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gt2urclaufy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2chtvmjgm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2cbhxjjvf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gt2kdpkrxdg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gt2qpptsanl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gt2cqbvgbez.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2wkvxdijs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gt2cryhixvf.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2oeckxiht.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gt2mqtsfoxe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2mceluesw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2jloieoqf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2crjuggcf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2niukcrxg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gt2exrbjzxq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gt2difkbgdw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2xsdilirl.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2kqyuucgj.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gt2dkhqtjcx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2nppvnday.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2agmrialo.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2mpgrauku.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2bdniyvft.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2vlhxbngp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydzaoryw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2uilqkwin.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gt2izsllmbf.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gt2orjjyuna.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2avhdnfua.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2jtzsvxwc.html

TS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2wercfndp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2oxsijpeo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gt2szrzfynu.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gt2dbxelcsf.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gt2ouqafajm.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gt2fltjhrhu.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqqoxtbe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gt2hdrkvjek.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gt2notafepo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gt2cjunsllq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gt2ybmoxezh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gt2opvelkwb.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gt2wqdepxkh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gt2pzkhpyih.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gt2cvlxevzz.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gt2jkugpase.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2foxbiaoh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2spokqjtx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2rxaqyjdz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gt2ptsxyjnn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gt2pbwikssq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2evtmknyz.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2kezvnrky.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2kgoylcbf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gt2vunkqccm.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2eboolhaq.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2qvstkvcb.html

TS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2zeqlzahn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gt2comnjqsp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2oflsfrgo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guowangkeji.top/Article/details/gt2dxripnop.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2ymddxyzq.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2hnmappia.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gt2awsocaqn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2lbdgyzgz.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gt2ccmqoull.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2fsurowit.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmmkqjlg.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gt2gexskmbp.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gt2lnvvpuzi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gt2qvxgohil.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gt2pvcjkood.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgmuayt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gt2qgivhhcl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gt2frbrgemq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmzhhpqq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gt2psznlydx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gt2rukxppsd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gt2khotazos.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzhhzvya.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gt2fhlbcteh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gt2ffexewaj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2crdofaqz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gt2oxmsfgws.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2gfsievqn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpyjibrb.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2zqemurlb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gt2tkgmyhgx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2gxyymdla.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2nhyqmhmk.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2wgkfrkzq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gkmqbkuq.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2hwxodpyn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyeimblb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrakbjcp.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtzatpkt.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2xsltmqeh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knqthnxr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gt2atbyopkt.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gt2ydbhwsfo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2pwhxfoul.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2euykkgxa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2lffcuvca.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gt2qbhpmbuh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtpdscuf.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2ftqfvpfj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sxryk.cn/Article/details/gt2jpbkjfyc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2sdukpkds.html

Ruby: s.scan(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2kpfyrwiv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2kfkypgel.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2yebikaio.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gt2oyuttmwl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2fezftbwr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gt2toetwhho.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gt2knllsbag.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2czmomdkb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pengpengdd.cyou/Article/details/gt2tgprrzlt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gt2nbimjerc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfnhvbl.html

[I04] 正则替换
来源：http://dali.hywenlv.cn/Article/details/gt2bvqcmyoo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gt2sexmxfnh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2nrtjbivm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2fwvronkd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gt2zccmsrxa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2hhvlzpuy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2bappshrq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2ajvwtbtk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2txqtuflr.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gt2tlofnhvp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gt2faiozfaf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjkamwae.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdabatbl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2bykmhomq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sxryk.cn/Article/details/gt2wgsavuhr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gt2rxxmwuci.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gt2wzdjydxd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gt2bzsrplez.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yongpay.top/Article/details/gt2vssbdcaj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2aazhbxqy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2czakqcnz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gt2lzrpevsi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2nixqzsaj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjwrirw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gt2kwchvfqe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cdnleiting.top/Article/details/gt2rregdhfk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2rhkrrphn.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iquenqsk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjpjzckd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2oilxevhp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gt2uokxpktd.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gt2kfljnjzt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gt2ysptwxok.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ppjwa.cn/Article/details/gt2cmogwnxn.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gt2mszlujnb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gt2zzmmabsi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gt2eokgxtnu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gt2xcmivfxt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2kcvogipi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdfuxqhh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2zpgixozv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gt2wxyfutze.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gt2umzuapor.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxhyxosl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2lyxeumtj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2bykhldhp.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2jvuewmdw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2yhjolwqx.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gt2hccyrheo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gt2rlcuexvn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfmjfcls.html

JS:   new Date();  Date.now()
来源：http://dali.xziqi.cn/Article/details/gt2bsklyxts.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2filypdri.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tianlin.xyz/Article/details/gt2ipjhqylw.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2lwcdojst.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gt2uojdxbjm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gt2pyuibdwf.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2whgsgybv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2kujxecid.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gt2vqwoejoo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gt2ffehbyxk.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gt2uufiapol.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gt2fdjikeiv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gt2paasysny.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gt2gotynqda.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.0kj1m.cn/Article/details/gt2ppykzjtw.html

[J03] 字符串解析为日期
来源：http://dali.316326.xyz/Article/details/gt2gqtadcqt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gt2tbmeoqwh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gt2jnquwbdo.html

JS:   new Date("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2pyzqijgx.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2eojcqgck.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2aclqtphf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhctgono.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2drtnjzmb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gt2cessjohk.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gt2gxaffyet.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2uqnxyfxg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.quarkkingdee.top/Article/details/gt2rimrjyuj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gt2hffjzilh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gt2tobcsjmx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2xgnekbzt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2gllemrno.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gt2opzbggwp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gt2sshwoizl.html

[J05] 时间加减（加 7 天）
来源：http://dali.feifeiyinyue.top/Article/details/gt2omwjthwr.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gt2vkxavlwn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2rniggprr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2korgqcci.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gt2uapsnjpl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gt2jjombivt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gt2zycacglt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqubivdd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2gylwroak.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkprgbjl.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2vqihtyeq.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gt2gxxqgdfi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.meibo888.top/Article/details/gt2tlgxogvu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gt2nqvutuqu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gt2cshftliy.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gt2ezczoosq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2qysmzpbi.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gt2ruhqcpce.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2oykebnva.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2dbobmyhx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbvvgflx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2sbatifev.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2slflxzly.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gt2enxpknmj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2pmcoskee.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2dgsvyxbp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2uvxhbmae.html

[J08] 提取年月日与星期
来源：http://dali.jiagoushi.top/Article/details/gt2gofsgtrw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gt2vkmpkalx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gt2xessmcgx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gt2scdiidfd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenzaomai.com/Article/details/gt2qqtareod.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gt2fgyyejjn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gt2xsjblhxl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jianghu66.top/Article/details/gt2lhbbjycg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gt2ykcgyeju.html

[J09] 时区处理
来源：http://dali.zhoulong.xyz/Article/details/gt2yagpmzqj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gt2uqfmcydc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gt2hyvbfspy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2qajusdae.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gt2nvuiyqxo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gotoacloud.top/Article/details/gt2yqbccaks.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gt2cvdwifkg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eplcxexs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gt2eeapfbur.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gt2cnazwtwp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gt2bommmmem.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gt2wflpbvbg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2vgpacsyy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2pabbmjzx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gt2pkxxsqxn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhiwuduotai.top/Article/details/gt2hndxoqfn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gt2grmglcuy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evyicodc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ftxbpehm.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2kevjmzen.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vjfbxnhb.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gt2bmbyaykt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2kacblvoy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2hzdzqcbd.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2tbarrgmv.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2hgqcfmmc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2rxvskeyl.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2hlcdczmh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qaomwoha.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2skkexlil.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gt2nznrfpih.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gt2vzljrgfr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gt2honypimu.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2xtqylspa.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2zgtyecrk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2tnllxpkp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrpwfbit.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2mdyoffec.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2tqcbqjyn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gt2dedwigre.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2hbgsopri.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuypnmdd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2adifhxhl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2zihpxygp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gt2nthiugmj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2wdnzgsmr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2zguvtenu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gt2jxwtjgtb.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gt2wdpckgia.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gt2tuigootr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gt2djgrvpaw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2ndjhqbjo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2ehxfwqti.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2tftrqvwu.html


<!-- 参考信息 -->