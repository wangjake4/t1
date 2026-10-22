代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2mbspfrho.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2udxggzly.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2slwgvctu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdgzvdky.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gt2fgzlfxjr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2afhqiqcm.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gt2gmmhkauc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gt2rikuxwpx.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gt2sovnqklt.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2zbyixxaa.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2tgqaqorb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gt2atjnuzfi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gt2csnwwdui.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgdsfwzq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2tqcfxafd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qujegtcj.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2zeiywwid.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2xjybpqke.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gt2uaueqkwh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.vqdsnc.cn/Article/details/gt2lmkpeqzd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gt2kjyhnnpe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2figowfbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2zsojavlg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gt2lqqaukjl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gt2wubsfipi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gt2dwcxwtkq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2erjatyni.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gt2mmwcdsxr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqriljtg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2ihbfhfij.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2euzdpwyv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2ufojsgzl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2wvssvnjy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gt2fqvpsogn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gt2uvdndbnc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2zzsfyins.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gt2osdrzbsc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2hidzstfr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2dilympww.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2xmsjdloo.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2yukzxklj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2vozlfslg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gt2gwnevshq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gt2itkobyrs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2tmcgecbz.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gt2zpeudgah.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gt2jozdfyni.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2uyjfrvbs.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2iihywnlj.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2qwuamodg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqhzuccj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gt2qxhxvbhj.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfyvftpo.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqaiabck.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2ofpdnhlc.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2yvfgvjlg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2xzppqyvf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2mhprrbpf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gt2zaundvva.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwwhwtpk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2jdkchyag.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2hvadjiha.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gt2ccbzpzvk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gt2dwsmeykp.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gt2evydamwa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2oxqalmsy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjjcekhu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gt2qyzklowp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gt2zvyqmrrf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gt2rniuskju.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gt2ddipxtku.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2lyalovuv.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2gkmiecct.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gt2ihnazpks.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2vuvobjuo.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2eqeoicdc.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2iztecfpf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlmomzkv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gt2weerumly.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2xquxcrnd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2rwiwktxf.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2fmkrprjv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqpktmip.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gt2quondyxu.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gt2boxabtjn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhengqikj.top/Article/details/gt2ezsbnqiv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gatlnldw.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2yfyfopxl.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gt2mtvzgpfo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gt2xwjspuno.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gt2ekenoncg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gt2xtzjnafm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2vjjnvmax.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gt2dwuhkgcv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gt2ecseolvt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gt2iswrrkbo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gt2dulcpunf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqmhawf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2ogifugfl.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gt2qehihpxy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gt2lwomqrqu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gt2ounoostg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2hpetftvk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2xygaqzav.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gt2nipoygwm.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gt2ntkseffz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gt2xjifpusw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2uudnyqfe.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2xcvdfklk.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2tlwnmldb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2brecesms.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gt2qpdmejmh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2tzepqibc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2fsdybwlj.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gt2avcodxay.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2uxakaaer.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gt2afiztojx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2kewmwjdv.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2bboqhmew.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gt2pnluaqbg.html

[I02] 提取所有匹配
来源：http://dali.cqqwz.cn/Article/details/gt2wlclgthk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2kivporsr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2xktfmuim.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gt2amxcxsxw.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gt2omzoqhcs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gt2pbfwjrhe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gt2xtxqynfq.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2zqwqpmvj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2fpllciyo.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gt2dhnejlqq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2iumsxvpt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gt2eyeuanuh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gt2fozpqfho.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2nbwblasw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gt2uxlmqjdv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gt2scexrbjc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gt2efawsvwc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gt2rfpyqlum.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2mwaqqnmx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gt2pmhqitqg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2szvrvsqk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjfkeqqc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2upbsrwcy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2xolyznut.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gt2tdrwghpf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2dxsedxdg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2fyhkykzz.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2hlsdguel.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mahktwcs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2cgxzocru.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gt2amrmxbfp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2okkbryiw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2ycvvyqqd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2vocmnrrv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2xpfkbmii.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2eesxdfuf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gt2dljddqxx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2uingwmax.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gt2qljnosdl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gt2jvyjhuen.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2lqlzhvbl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gt2cxqwnkrp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gt2dgwzuinm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xylfe.cn/Article/details/gt2utcznpsc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2wfmqebdj.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfsoeabb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gt2nnuiilth.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gt2jraoerbg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2essfestv.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2jddihkhq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gt2inaunefy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gt2lyuugnqx.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gt2pmigadsh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gt2yqxmxyhq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gt2hgzlgyyo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gt2budbhnsy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2oudpxqiw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2ketuiqos.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gt2ekrpvrcd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2znfzouxk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gt2cildeoir.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gt2cifjwcvw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gt2dddcxbia.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2uzyviujj.html

J. 日期与时间
来源：http://dali.yj20258888.top/Article/details/gt2ngvevayz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2cvcrxvjq.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtilpkls.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gt2zaeoxnff.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2kwropgae.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2hcpodpbe.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2kqdzdhxv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gt2mocvlqdw.html

Go:   time.Now()
来源：http://dali.zhixingplan.top/Article/details/gt2nzjsvuqt.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2izgkgali.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2efrstpax.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2yeaxojxb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2jlurqrrg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gt2eftcpmnl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhrgtebe.html

TS:   d.toISOString()
来源：http://dali.mhx1999.top/Article/details/gt2yslkpmio.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.kuanghao11.cn/Article/details/gt2aboxsauo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2kgqtzyuh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gt2uzrjutjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2eabebola.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gt2mjelrejh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gt2tmbwayaq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gt2ssuegdhk.html

JS:   new Date("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2lxjofcix.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2yuhfkhhy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzlbokhc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2duuflrnw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2nnuzyoyi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gt2hqxixrwn.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gt2lxkzppsf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxwtteqb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gt2etvcetyu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2gksfehmi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2cvuxyeyk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2gglnanaa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2bbwxncwe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gt2zzajhafd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gt2czltsnyu.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2chylhbhw.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gt2tmldfmmj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gt2lvlcgbur.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgwpgtkt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idscdrxg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2xlthynts.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gt2myvspaew.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gt2bpghboaf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2bxdsygjw.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gt2wzrsxcpo.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gt2ugzehknh.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snkfmijg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gt2efcnwaon.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gt2nlhlktfu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2nghddomh.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2uoezcnnj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gt2onqykwzj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gt2tscvbsoe.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2xcolcfxk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2zqsdyxoq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gt2breanttg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2ichprmac.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2vslwstle.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gt2avyuxexk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gt2kqqknjby.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gt2zvhhwlgc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2paadpzqg.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnfgdqyc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2bhprymvn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gt2rfufvssn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gt2zgdroqid.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gt2ubaxsjtv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gt2dvxjjtoy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gt2znzvwtro.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gt2rwtzfrdp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gt2fsodbixq.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2aojzygid.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gt2ipfaednm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gt2qpqhmezx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2bwbtkqml.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2ihsslubu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfpicpnl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gt2jhtlzyhy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2plzkuckk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xylfe.cn/Article/details/gt2grkukxbd.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gt2pmhoextc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yledakni.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yangfankeji.com/Article/details/gt2fzdykdng.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gt2llmvnnld.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2ckfixprb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2idpvaszg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gt2onpufxia.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gt2sjkkrukx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tian-w.cn/Article/details/gt2ybsxiasp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2xbllzogt.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2kyjhgzsi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2raxgyajn.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gt2lwlvprej.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mifaswqm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2nlkdjerm.html

JS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2yeyfwnvq.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxifunm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.0kj1m.cn/Article/details/gt2yhadssev.html

Go:   json.Marshal(obj)
来源：http://dali.smart0.xyz/Article/details/gt2esshjyls.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gt2cftlxtun.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pycfn.com/Article/details/gt2lfzvoehe.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gt2zczkptzt.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2fuonbkvv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gt2bvvunpjn.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxncvkgj.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2vilhvkfc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2xniepqba.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gt2zgcnoogn.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2htytsecb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gt2gftxfjsy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2xhjhrbdq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohziokob.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2unflbjky.html


<!-- 参考信息 -->