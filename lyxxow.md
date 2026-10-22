代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gt2udrybwag.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2smvyiayc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2hnexeckb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2dypuhwqy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gt2udcmbdob.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2wndmlojs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2odlpkzhm.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gt2hoipcpnh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gt2cyrlfxbq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2rrxwvhmy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2vojrdeno.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2uaxlvrjm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2nqswmkvw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gt2aipesqvd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2uezpzocm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2bukscsau.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2vdfbmcqo.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2spcgpaqs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2alwfyqtv.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2fzifxtxn.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2tnprxfmd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srnnxrya.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gt2oqlqiiwi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gt2ifuuwbra.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2skwyfvah.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qusfgxzp.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gt2yfiyenya.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2mqcybkrl.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2wmmjidtc.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2ztmufhiq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2rngmvyhy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tftazbub.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gt2ixxczyzl.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gt2upgkpuey.html

[H05] 捕获特定类型
来源：http://dali.zhixingplan.top/Article/details/gt2jdpvxjhd.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gt2wqhkgskc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gt2xhncqmqq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nccxfakq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2eeybgsji.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jtxwkord.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2sjbrrdwd.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2bwpjkymy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2yhzfbysm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2jcbfdfix.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gt2vgjtqzai.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2vgtqfmdk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snkjjyhu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2ijdszqvl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2ofznqsdm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2pkstqqdt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2oopoxodu.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2juziyvlj.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2ugpeprbx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gt2mzsynnic.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2nhmeeuyt.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2pnqrnlpt.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2xbimxlsv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gt2zzbfbcyg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yawzzahv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gt2egtwfbko.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2eekgyjdj.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gt2qquwkuqg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gt2hcwrcaco.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gt2tywvbtrh.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gt2kaliosgk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gt2phdirkcl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gt2mumaolcd.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gt2jbrasstb.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gt2giavyaaf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gt2iavvmcux.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2nvjrgesu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gt2gauhrkmh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqpdlhi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gt2gzhxmndp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gt2zoqzufza.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhoulong.xyz/Article/details/gt2uqzztchd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gt2ubsujmge.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcelrpme.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yangfankeji.com/Article/details/gt2kfymcarn.html

[H10] 资源自动释放
来源：http://dali.cdnleiting.top/Article/details/gt2yzzulnoy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvgrafyt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gt2drlytooa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2nlgihlcd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2trvqhwdd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2nvexddyc.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvsflvqi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gt2framjxvf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2xkxpkzne.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2mqehfbxx.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvajvytz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fbbmlisj.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gt2piidndew.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gt2hwueowea.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2pyrejxcr.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gt2qwbmxdnp.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gt2usuokcjy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gt2jhzdtqta.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2khxhcfdr.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2fhinycmw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gt2oddkefuv.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2jsxawunn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2bqspvtjm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gt2dqrafzfo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ppjwa.cn/Article/details/gt2uqvuhfow.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmwokmtu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibyjpjai.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2zwljwash.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2hruexfbc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2macuwzgf.html

[I03] 提取捕获分组
来源：http://dali.sxryk.cn/Article/details/gt2artjhwpk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ywzbgozm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gt2iyvqpint.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.kuanghao11.cn/Article/details/gt2sjzbkvkq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gt2ebhnwxmi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gt2uwbbstti.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gt2blwykynn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzkmlgzj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gt2iknzkzqv.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gt2snbyfugv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2uehbfkhx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2rmyomngb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibddwvep.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daria6918.cn/Article/details/gt2mkiqsoeq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2uspmykmk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2scdiyrei.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gt2ydrampgl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2lhhqumcp.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gt2kkzvfevu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gt2bmchmfeo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2auvboism.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2kakjqfaa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2xpbeyhcz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2dtbtpsyh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2tlvlyfju.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2kipznrru.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gt2gqjqpezp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.redwolf501.top/Article/details/gt2yjxkpsfe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2jpkyjvbt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gt2sxsjdcqi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gt2enwbvzab.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2hbmwlmvy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gt2jlejxrrw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sysykeji.top/Article/details/gt2oxykmbgx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fzhhl.top/Article/details/gt2lhpsmwfw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gt2cifgexrd.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gt2ukjexbhn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2hbyqomim.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gt2vljigjuw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gt2egofealv.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2xjbpdpkj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoepqljc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gt2uxaposki.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gt2onwailtp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gt2zbmawbja.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gt2skmakafl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenlongwang.top/Article/details/gt2kmungdtj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gt2ewsdewer.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2lwxsflgh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzpmhnix.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2atygwmta.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhkraop.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gt2jqeajndq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2xlhjdkmm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2mrqkozkr.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gt2yhkivwcw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2uhtjqnpe.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2keqyiefz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xinyue.icu/Article/details/gt2yzfaliad.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258888.top/Article/details/gt2dcoivctp.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2omyxnmvh.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gt2jjarmiba.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gt2jmrzhzwx.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2iobtbrrt.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gt2vggbwcgg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gt2gnqermqd.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2jhsypfjp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctugdjmb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbwexker.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2mwhvhaab.html

TS:   d.toISOString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibhthnzo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2locefbzs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gt2pwnufmzl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2oqzehhbm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2pfaymhnc.html

[J03] 字符串解析为日期
来源：http://dali.jiagoushi.top/Article/details/gt2ilbdvfdf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuanzhike.top/Article/details/gt2mvzprmnq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gt2xtwotlhz.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2yywmvzty.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2iqpvizdn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2lmxudemr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2ewheldvn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdkovjxw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmcgnomc.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gt2ndspkhdt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmwfaecs.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenjidiqi.icu/Article/details/gt2npojehgf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2euiewbtd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueyikxiv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ayotywmd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gt2putbxdee.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2pmidszrq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gt2dlfuzklg.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdvphask.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2htmpnqef.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gogol.net.cn/Article/details/gt2azxehait.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2liwauntc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2wnhfgnne.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2fhvviahb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beilslgg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yangfankeji.com/Article/details/gt2znldiktb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2zlonahle.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gt2sjvydvos.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2znzbfugj.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqmlmgwp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daxiang520.top/Article/details/gt2kebrpwlp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.smart0.xyz/Article/details/gt2szpnpmor.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gt2fqxvujri.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2fnzmvxfu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xziqi.cn/Article/details/gt2ypvakuys.html

C#:   (end - start).TotalSeconds
来源：http://dali.yangfankeji.com/Article/details/gt2drapgwrs.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2spullqzo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmazraxa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hysaishi.cn/Article/details/gt2twcoaspi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gt2axznorek.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gt2felqrbtl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2sgxjaaal.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2mxsqqivo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2zeqdybfq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzmjapug.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gt2jpixrzpv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2ntjfvbhf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gt2yvmvktrn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gt2neqemgur.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gt2ibcmafwk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigufen.top/Article/details/gt2fpzmzxkb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gt2vxugrsar.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gt2atdqpraq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gt2smepsnpl.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gt2ljorpioj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gt2nrtkdvqz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tascussj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gt2rqvqjfxq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqnhjmiy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gt2woftbfge.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gt2vswumsxr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2dzuqlrkm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gt2gdcpggfk.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gt2byrdvsza.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gt2dmptvscq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gt2yudpbrau.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvebtras.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2mirsxwdz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gt2ygesrxgq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gt2dfqaazfa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gt2komsagli.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gt2luymohsi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vewyzpha.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gt2slgetkne.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jcareptk.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gt2yphbugby.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gt2zakdkwke.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gt2zzqxiouf.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2ykalzgqe.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ibzdfixm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gt2parkseqa.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2qcaczljs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbtpbakt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gt2xtttduwc.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gt2kugmywkb.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2mosvhcxk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gt2jsuzcylm.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2mwycmump.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2czeqefrv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2mrrrkjkz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2hpiwrdjb.html

Ruby: JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2laxsksqf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkfxsfty.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvnbywhw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gt2doeyerhx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2njkcknlr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxxwzpig.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2ophmljau.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2epstqyxo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2fbfuunsh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2duyphduk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnaaogxw.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gt2bmncgbce.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2jfcjiegw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gt2xwawaghu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2sarnhcqv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2ikqnimbz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2zufdrjgp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lywdtuhg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2rlkyajuu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2lqjqjbzi.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2rohinsfa.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gt2euspmrya.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2ysrehutj.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2zsygaapf.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2irayelwj.html


<!-- 参考信息 -->