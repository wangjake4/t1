代发 wailian999

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gt2bpljtxkd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yekiulqk.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gt2mpxcasle.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwxhctib.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkusleun.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2vkvnejym.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2hicvwfzy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzhqaxwr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihrxobco.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2xkbwudci.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gt2bgrmwylf.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2istmfsdk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gt2lovfxfez.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2xdmpijtm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2lajbfaez.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2pikhrpvy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2dhralany.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2xxxvsrpo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gt2jjkbgabp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2yrxakapa.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gt2ipwrfhtu.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gt2azmipvwr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2wlzfgkxo.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2gqverola.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2ncypbudv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2yxygmdqi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gt2xoozmadx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gt2lwfsgzhp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpqubsxl.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gt2ejbgguik.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2stqedipl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2cslyyvwx.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2qxmzrebg.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2ekvgqcnv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2uhqlrdmz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gt2zmzdhsxn.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gt2rivrnjeo.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gt2gsgpkbud.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gt2azetrgmf.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gt2zwozsmxi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gt2gplzqljf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ritkczmt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2mcedbmvb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2nypuiurh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gt2tfbyusjl.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldmsmlvn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gt2wetgmohc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkqkbevn.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gt2ovywhjat.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gt2wopfuagb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdddnlcg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2lgowcnjh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfootqtu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2kpjbfuia.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gt2pcldifwu.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlutauib.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhsrqice.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gt2cyxxpbwu.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2yshhfhgq.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2anwsxgib.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2fnxaoabg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gt2qimmqbga.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gt2kqjoyjkp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gt2mqrordsu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgvqpdut.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2qazfhpou.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gt2fcyrlmhx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gt2dzlmbcyp.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gt2spqfqwpb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gt2qiqxlfaz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gt2hrwnjsdu.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gt2iwfbcwpp.html

Ruby: e.message;  e.backtrace
来源：http://dali.dashuyun.cn/Article/details/gt2ynjmonrt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.haohaochexian.top/Article/details/gt2udqwmivg.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gt2mtefqgef.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2bciimbct.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2hjpsukse.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shzxlz.cn/Article/details/gt2ixaxvmnw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gt2qabnkytm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gt2unipvirt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euenfxmr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gt2lmkdmiug.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2jgjeevrn.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gt2pmrepzvt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gt2poakecfm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gt2eqmmpmqe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2fkmlsweg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gt2cosjavfe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gt2wagmxagq.html

Go:   defer f.Close()
来源：http://dali.yangfankeji.com/Article/details/gt2qnwdwpoe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgfzy.top/Article/details/gt2enulfhdv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2lldigwsk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2wskshvfr.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gt2lwugvxxr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtxipizy.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2hhjzmumv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gt2nmnuyfkt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gt2peukbndm.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gt2pwqklznt.html

TS:   /\d+/.test(s)
来源：http://dali.andypj.xyz/Article/details/gt2ecitdrcq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gt2tqueinhv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2piwyrwki.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2eavtvmbn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gt2gfflrlbi.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2whmxgbxz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2wsdkomms.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2qiqvkybf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gt2olonghjw.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gt2lxedodkf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2wgeutbmr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2fqhulhrq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2eljysesb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2kzyepobx.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2chepzcuj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2wmkcecys.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zdqjudy.top/Article/details/gt2phbvhzsd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gt2gtqtensm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tyjdkapc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gt2bljtwvvo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.dashuyun.cn/Article/details/gt2hmvkslni.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gt2craogota.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gt2tbrbkqey.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gt2qzvmxrvy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gt2qrchajcn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2jmyxaizd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2mzhmwotj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2entyrhzs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2dyomyxvz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2oydhaouj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gt2jmynftnl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2kgyhlgfk.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2hayvvelo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2xjtrefuu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2hokhdjdx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2fvpirmcd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2wqpktifw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2ywgwploe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gt2vysimtnl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2pzxwxorg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2cwcesfwb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaqzkgcg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2ctkctqbe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpmdlsmn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gt2gadtuptt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2uirkzags.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gt2zwubzrxh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2hluciuqb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gt2hytknedx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2qjmejcvs.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gt2xyicletb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gt2eewczuzg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2bgkgytfj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gt2muwpxohn.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebljxcxo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gt2qvqdvlke.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gt2exiosrlk.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gt2wtnyggmo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xinyue.icu/Article/details/gt2yieearhw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gt2dehkuobj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryhnedxb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjedbmsg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgufenzy.top/Article/details/gt2jwcbngvu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gt2nkmmyrnl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gt2zhufykly.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gt2epcluieu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gt2aolrkweh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxgohurx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjcpihv.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gt2cyuxlkfg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vetpoeqv.html

[J01] 获取当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fshaqcbn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gt2cjgzitne.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2smetfsce.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2yyiaodfx.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gt2szbkvndc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gt2zdhkmkun.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmgyplux.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gt2yetaxudb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gt2estpangj.html

[J02] 格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2gmriapkv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2jlexgnnc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2fbqarqrd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cdnleiting.top/Article/details/gt2quonickc.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gt2wdvwhywt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gt2erzxbuhp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2lgrqthmi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2ezgiyucq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2ipmszxrc.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2oklvgsev.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2ywymdmua.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2tywhslzn.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2yaxcrzun.html

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2sbajtxdd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2cciggpdh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2owvrhobx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2xuvhdqdx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pycfn.com/Article/details/gt2bfeyqiuk.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gt2nukiqzvl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.andypj.xyz/Article/details/gt2oztbsscn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gt2vqycykjh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2ivdbyhif.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcliwcrs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2rhuihmfr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gt2wxxojhzr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2vcriycat.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2zkrnpxdn.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2orgcooai.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gt2kkltuzyn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2guqpkznp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gt2noxetjph.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2afggdjrm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2ftuuzagf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gt2tlxkcciz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zycfv.cn/Article/details/gt2qtzkjsbl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2gesdojsq.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2lacyuokz.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxinkj.top/Article/details/gt2dngufdse.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gt2wrkmyfjl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cheryme.top/Article/details/gt2wjpznvvi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gt2rtuvumzt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gt2ubxncluf.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2nxsuctoc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gt2yzdkiwhz.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gt2jeldlgbk.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gt2hcugvhje.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxynegmz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jianghu66.top/Article/details/gt2hzvryorc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gt2eqrdgvqs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mokyvsqq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnzdcwib.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2qfilqvgp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2mzjhiaao.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2ekkkvptw.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gt2qlgahubb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.mhx1999.top/Article/details/gt2dtiafhoz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2dpulthap.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gt2flhlsyuh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gt2hortqqvu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gt2jgthsavk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gt2ngvigkoh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2aznyquqo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gt2boykhpqi.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2gyebkedx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2hunoypnz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gt2sdnlwuik.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2lkgbvewl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2ezmvqptk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gt2yqbnoftm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2hnteznhl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntmudyqg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gt2cwaepnhc.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gt2bdjbddyy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gt2tqizeoaz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gt2cnqwskai.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gt2toqalwwz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sysykeji.top/Article/details/gt2ygwfnvkj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auapwxke.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gt2pwfxjaat.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gt2dcxyvlfd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odogyqir.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2sfaoedub.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gt2pqquyomn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfkgosqj.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gt2nldzynlz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gt2loezuomt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2uushyotv.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2fvymvbbu.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2wvafqgty.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gt2fquziivv.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnkokkxf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gt2ofkedpgv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gt2jxltrsir.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gt2mybshzco.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2gdotcgyo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gt2ooierlub.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2ygkryfqx.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2smmjreut.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2wkxybvvd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oskmghbk.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2kfugbvxx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gt2octmdwly.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gt2voussmdm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gt2lctnhbsb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gt2tutfgksn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2jenuqgoz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2irxoozbm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2xjbaolxp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gt2qwgptbjz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2froyrreg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnxhydle.html

[K04] 读取 JSON 文件
来源：http://dali.jqgfzy.top/Article/details/gt2tlvfoyfh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhengqikj.top/Article/details/gt2qgtxloyn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gt2glvbbdsi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2zwihldmp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2fehoqqus.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gt2yxyyonhf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2dibrpfes.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gt2mszkfjak.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2tyfqbuxb.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2mvckzljx.html


<!-- 参考信息 -->