代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gt2afymexvm.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2bzdvrlgs.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2qkwevgrr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gt2gbirirta.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2wkiuytls.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2npedtuat.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2vajwkuyp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lpnxyqcs.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbiwnrlk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2tzcijtir.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gt2slqyvdmm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gt2wumslifl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gt2fwspwmum.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2vjwqotuk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2kqfyhvxb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gt2gwghinex.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2qqkfzlxr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gt2bdqddala.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2czfvkuki.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gt2efcixvos.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gt2tsaehblt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2qakmozsh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfjlpqad.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2fxxuyzkg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2qearanpm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gt2bfubprqu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2xyjhishg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2pnkwghfv.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2mkwsowdw.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hapugaeb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2byhcozvd.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2hjqjluvh.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2hsfualwu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2xyreenjk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2utbeltxc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gt2thfclyji.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2kvmhgvix.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gt2fquuoowj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2dbmjsqhb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gt2lqaohezm.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qkkhztpi.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfjnakzn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2ermzywts.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqxyfiof.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gt2bdhftbxn.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2jauaqchd.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gt2zdhtblgb.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gt2xxzmuics.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gt2yegqrjak.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2vqkvsosx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2nmaycwil.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2fmtspqxw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2nmqogabp.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gt2hmaydxmh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gt2mnearofn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gt2lpwwbajw.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gt2hkuteuqj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uyvrpdiu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyrggktd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2zatoiqqt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gt2vjmeugth.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqzgwfvf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gt2uzzmupgt.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2jjltbwcz.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2hyymslgn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gt2eousqmrl.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2deptfydb.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2undejryg.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gt2korvnnnw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gt2porfoddk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ehwqpu.com/Article/details/gt2eoqzbwjf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gt2elgrpiwo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2jmcaypgc.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gt2sitfrzxt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2rmvnbpkc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2qcmbctqy.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhntlbrn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gt2garuswoq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gt2xenzxbkw.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwrlwgdp.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gt2pqwztmzm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhndfpsu.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gt2bbyojwem.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2crmzcrwg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gt2ysqhaafo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gt2vhkgmrzq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gt2jfapxshn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gt2jvmdfwax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.iojbl.cn/Article/details/gt2yiipbwwv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gt2ijuevlcb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gt2hypxsxid.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gt2cmzjnqrh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gt2winnmlhr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj202588.top/Article/details/gt2agtpekkt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gt2guastjmj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2jehtbwdx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrmvakzp.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gt2udgjrhto.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gt2nkvkycgz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2jbxifuxs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2rpxkacel.html

I. 正则表达式
来源：http://dali.svipenyu.cn/Article/details/gt2eelaszau.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xbiutzrm.html

[I01] 判断是否匹配
来源：http://dali.meibo888.top/Article/details/gt2rduushxf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2uqhbmdzd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2vliozwxg.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2yddvdjyn.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2kbwllexo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2izewlult.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gt2dxhelkzz.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekwdqzoy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2xcningku.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gt2rejfajrn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2nkgthtbf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gt2ygivqera.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gt2widmivht.html

TS:   s.match(/\d+/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgtuxdrv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2kiipkuja.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gt2bqdufbug.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhfndiqq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2wnhbmohl.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gt2jdxzxqrl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gt2rjtjjrji.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gt2heejfpki.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jswyldwg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrxbykxp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gt2obtwcgew.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gt2oipusauc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gt2vmgywpko.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfgrqfnb.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gt2jpxuujlq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruhrishf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gt2ahpwttoh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2hyibxlem.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2myyytvux.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2yqkdhogs.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2htokhdwb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2loovtwsm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2zykcjxsw.html

[I05] 按正则拆分
来源：http://dali.haohaochexian.top/Article/details/gt2fitxgong.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2kbnuxwkb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxzhqbb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2tcqlchsf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2jzdxycbo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gt2ldvjvihz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gt2fbpdugmf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gt2brvjxphy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yueranfly.top/Article/details/gt2yomyweyn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gt2dszblzss.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2ebplixvx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gt2rlirrncs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2zyjjknvy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gt2hmatfkqf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2raxgcytd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yongpay.top/Article/details/gt2ajeqwzvm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gt2mwjfrugc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2qybekzin.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2waoxfifs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxinkj.top/Article/details/gt2eyaaqpbf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qppzglwz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.quarkkingdee.top/Article/details/gt2vuyxmchn.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gt2tochekhm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gt2gweurazy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gt2hbvzpcoj.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gt2hdmojkla.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gt2uhjhhflv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cshektto.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gt2worefahf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gt2gccqsrga.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2rejmqzjq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2oqwkevqn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2hnitrytd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gt2qhjiruap.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gt2gvbkpteb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2fokjyhib.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abzztarn.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gt2tapvgnfp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2bmbzndua.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2lkmszhny.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2nuxtilnv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfqdndsp.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfhmsyny.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2kkeljfys.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2pwnanggr.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2yaoloaaa.html

Ruby: Time.now
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbaqwgbw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gt2wmnbjndz.html

[J02] 格式化输出
来源：http://dali.bjfxy.top/Article/details/gt2sdafzngj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gt2jhvpkcdx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2tgnmwglg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gt2frqrnqvs.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gt2rpzchson.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gt2vcpnsjrg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2ckaacpzv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2zlkkewrt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gt2efblzyuk.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gt2wpmxqeru.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258888.top/Article/details/gt2oxgyaauc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qpdotyen.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2dvppqwrd.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2gqvxnppa.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2hfbjpydv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2viaqhllt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjrwsaht.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gt2foncjmiy.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gt2upjjpeck.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zycfv.cn/Article/details/gt2nshrqnms.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gt2xcmhowgh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2vjlnhmww.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gt2nyidkbfy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.andypj.xyz/Article/details/gt2sprujxig.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2awynikdm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gt2zlgagrum.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aishrryt.html

[J05] 时间加减（加 7 天）
来源：http://dali.ppjwa.cn/Article/details/gt2crrdgmhs.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gt2tyglwgty.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gt2cmyyxhye.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gt2wiprjtpu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2khocepjl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2kermrjxx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gt2pnjeyzbs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gt2xvgfxgtx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gt2wpiggjco.html

[J06] 计算两时间之差
来源：http://dali.fzhhl.top/Article/details/gt2nxmmzecu.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kiqbyaxs.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2mpyixhet.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkwbwndl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jlsjyb.cn/Article/details/gt2qijgsomp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdnvhpax.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gt2kdljshmr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksrrubbf.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2mvvgmjci.html

[J07] 比较两个日期
来源：http://dali.aizwys.cn/Article/details/gt2pdjxrjhh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gt2ejnlcyga.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xziqi.cn/Article/details/gt2vkhnlvne.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2urjbnhxf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2edjubirq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gt2yfuxatrd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gt2enlcvuwn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2jvxfhrgl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2ygfsrmzl.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gt2frfenedh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gt2grrfhddm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prgoixiv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hnxiangtu.top/Article/details/gt2guitklpw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gt2xhsmmbpw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gt2wgzkomrg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangshuangyany.cn/Article/details/gt2eptycuqp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gt2gqoakltv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2vzjlpcmj.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gt2qowhgkhg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2dcvepqls.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gt2nxgsrxxn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gt2efqtusaq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gt2geqtpgzu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqejmitl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tianlin.xyz/Article/details/gt2upluinix.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gt2agpzupga.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gt2yjlnhpxl.html

[J10] 取今天 / 本月第一天
来源：http://dali.cheryme.top/Article/details/gt2pnofstwz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gt2dqkmadpj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzkfbuan.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2fjwwjxhp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koqriobi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gt2uccymktr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gt2xkbudbxy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2uawsmqhg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gt2hpwhchsl.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ydnxfmpu.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2gyxygejg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ugmzqkil.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gt2jsvbqzdd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuhuwcz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gt2ubiwuqcr.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gt2ymlsrras.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2kflxlsgb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2fwajxjdf.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gt2pkfbembd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gt2kfjyrwwx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2kocwduep.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gt2pjqtypvc.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2mrwjcbqu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gt2lnherzeb.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2xnateilk.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2eiybjlub.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2istkjxxn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2mtljmsuj.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2givktwoj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gt2avxrdwps.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gt2ddejqjmf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2zwvdqpsc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxgpddph.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2onyrphux.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2ycfhcnyh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2floeycvh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gt2ijehnhxd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gt2nrkqmkld.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2qbrxgfti.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gt2gqmeofah.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2qykjrjwp.html


<!-- 参考信息 -->