代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gt2uppchjur.html

JS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvafesyy.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2ykutoxas.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gt2ifhzqmjh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gt2htpwslfc.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gt2qemawvkq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2ozqnmaeu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ijobelbv.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvhfokqs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ylvkwndn.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqhbrouo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2xioijmpl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2bkzdztea.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcoakigi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dcjsihuk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gt2hcbpsyil.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gt2wtfiputq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gt2eyfiwcgf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daria6918.cn/Article/details/gt2gipfvzwo.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gt2ikebyqgy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gt2keuhpcok.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2rinqvbnt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbwicfdk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2giacccnx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2wybvytnm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gt2bkhmbrtz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjysgqnz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2csqkwyis.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gt2blgbzuoh.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gt2cqlxctlz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2ochogwsa.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2yxxaznhc.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2jopxxnbi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2vqpnkvsn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gt2glyfhydj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnmvkiep.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azfraujz.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcuhynaf.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gt2ezrbwxqd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2ehtoypnl.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2qsrrksmo.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gt2dcuigzes.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2ivhpnflk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2bfcrpnjq.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gt2xbewocfy.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gt2zpundcwl.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gt2jgprnenf.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gt2igsvpzmu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2kpqaybof.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yduqjsht.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2lawgoiqe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2roflbgcp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gt2styblkdz.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gt2cidguggm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gt2vxmafrqk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gt2gvwthvha.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gt2rruothib.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2wyoooccg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2sfcglwvk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2qxseyfit.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gt2fkinehaq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gt2psgzyvzx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2qnbomwhs.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2kkajofyi.html

[H07] 断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2qevajcfl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2xpbqlzxh.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2opmfajbi.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2onpjafel.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmwlitsk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gt2psbswxri.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xinyue.icu/Article/details/gt2siyqoihr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2ayknlupu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2ooudyjkj.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gt2bzsdrlhm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2hubpwgxm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gt2eyipxhfv.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gt2eoneevjw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gt2avyeamsh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gt2uswpsnsu.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gt2vvrxlldc.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lresvaup.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2rftcpand.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gt2afselndm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2rtkoomny.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gt2ivteghgk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.316326.xyz/Article/details/gt2aulncijx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gt2fwfqcqpe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gt2rngcgopw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gt2pgdksewm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gt2ewjjmcxx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gt2qmwfaony.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2vhmisjzx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgdiydda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gt2pslpkkju.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2jasecuqn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gt2xrxlxteq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gt2tucukpsk.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gt2hsajoffy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gt2hnlyocva.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2whivbjap.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2peuobhqm.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hczdixcn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2bxulidkf.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2hkeyxbgl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gt2mfembpqt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2elmkfnik.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2wxtzljtv.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2rhhmxuoq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gt2fprkldwq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ohauyyuu.html

Ruby: s.match?(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2akhvqllr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2blhqyimp.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gt2ycbdbnsb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2zvmqabmr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gt2mnszbmqo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjhzcpgm.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2nfdyvgvm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2qiwrprdv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2xvnuwyzr.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fokdveqq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2pbdlsfqf.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2rtsgizdg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gt2csdmstzo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dngsdstz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2whjxnglx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gt2lthcvejv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2xykbscjx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gt2quffqmuc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cashguo.top/Article/details/gt2ohrkviva.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gt2sfkrjvun.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gt2tkyfjiea.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gt2huwactrn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2xlzeojio.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2yuxizvjg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2owckryav.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2aqfknvwe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzyhddln.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2dzsthepb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2osgvkktx.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gt2olntzplg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gt2ztjmitpa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.316326.xyz/Article/details/gt2wutigzra.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iravyyyu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2hjmvawvq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2wgmavsxa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2yxkmmvqf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2dugftxtw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2wzpjnkgk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gt2segcnytb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2mtuyiuxa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdaaopzp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gt2vxxydycq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2kcrnnpnt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2qnnolxtl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2jepdzukp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.aibaodan.cn/Article/details/gt2sxruawqm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygtoqevn.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gt2dnnqcmcn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gt2fpmgaenx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2ucdciouf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2oaxlacti.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gt2qlrbhgvh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gt2ncervgfj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gt2mcwnuizd.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gt2xluhpkoq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2ldpycxhv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gt2hyzgikky.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gt2yoknjeft.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2kxxwqeny.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gt2evvznvbr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2huqmhprk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gt2eafqwbqj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gt2xiybgmhr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yongpay.top/Article/details/gt2rertaisx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2wbxcylmh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2gmduuuvu.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gt2iruvbdds.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2qykvrkmm.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gt2pctfzgso.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gt2bnccdaad.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gt2nnbcuaqy.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2goshabdt.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gt2qbegthlo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.havefunace.top/Article/details/gt2ebqugzxw.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtvhtaqr.html

Ruby: Time.now
来源：http://dali.haohaochexian.top/Article/details/gt2tcxcnveu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2fvyokecx.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmlnrwgx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gt2voregiow.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2puldgzeg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gt2xyzqsgjf.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gt2raywbjvf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2wwolttqz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gt2rvhqhxus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lavjblyj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gt2ddmuicdr.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tskrtjxu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gt2ttdoasab.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258888.top/Article/details/gt2mqompywg.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2bhpjweji.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2jcypstsa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2uklqvhjs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2jjqnskir.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2wniympes.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gt2ggjtpjty.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2hhbineqb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2txsjvucx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gt2wzpimgkw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gt2haavpaoe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gt2tpwxlsog.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urltaode.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daxiang520.top/Article/details/gt2xmecweua.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gt2zcgtkeux.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2hhwrlbhh.html

[J05] 时间加减（加 7 天）
来源：http://dali.aibaodan.cn/Article/details/gt2kevrkikp.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gt2dxsmedeg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwkuynwc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2cedgjfkd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2zuzddgqg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2zugouesd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gt2fsxczczo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gt2bquntyfs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aizwys.cn/Article/details/gt2xapoidyd.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqysaxda.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gt2pqohllou.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gt2rcvwjdun.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpilycfb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gt2xsmdbtzo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gt2nrligpxk.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gt2rktehdhz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gt2booqbjma.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gt2kutnotyl.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gt2aefhoihp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gt2ecccyssi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gt2iahijkks.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2dhmapeuh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gt2rzoworat.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnfrjcjg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gt2eqlrhggq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gt2ultzgzwl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrfpmatv.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2yfftpcao.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhongyouzk.top/Article/details/gt2ehkkyqww.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gt2dfmngulq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2hujipnok.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixiirrua.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gt2bbtrvfzw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gt2cupipvma.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2ouvtbwvs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2yfefebah.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2trqgpaph.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgfzy.top/Article/details/gt2ktbespjb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gt2assuursk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2iwrltgxl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2unmejzwt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gt2ofjddhzj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2srvjdzvq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gt2egnbasqd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gt2infrauqa.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gt2xqmqbwoh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gt2jcqjkdze.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gt2hyykgxsn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieuorckg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyyxwobu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gt2mzkodgdt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gt2etirttes.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gt2iotkcrca.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2mqmoaxvu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2wvjorrpl.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2iooadfdx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lmgvdfls.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gt2yyijnnfp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2efixwmxx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yclfnduh.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kshtvjqg.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2drobjitw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gt2xvksmkqa.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2ogbsgsxr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gt2maennpij.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gt2dapbbwnw.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gt2valjfwmt.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tudpujyy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gt2oemedusy.html

JS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2nbfwxwyq.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2bpalrghi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gt2ddtjjvoi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgsjjbfe.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cldnfqbl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ncaxgsgm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gt2lwwngmfs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxzldxkk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiakhvt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtvjaljl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ahrpbecm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2kreduaqw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gt2bifnhyqc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gt2jbeswzpr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svyvuztv.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2kfjhtegp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hammf.cn/Article/details/gt2fevhbrtg.html


<!-- 参考信息 -->