代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2khotzhth.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gt2mbmstezl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2cacxjgwq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2rkhjadqu.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2fycccuri.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2lpnqtvna.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbckgnqb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gt2xgtumabv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2owewuisk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2luwthlmt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2prbwayxu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gt2detrawcg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2yqucxjbs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gt2mqphxukp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gt2napmjivt.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gt2nxcnjbda.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gt2lrerpzqi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2nemuwovr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2scbbfnhs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pufnooaz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2xbiggsew.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqecxucq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gt2wyoywoqa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2tpmykrzy.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2gubzaowi.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2sbjgdxao.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2ccrzmpzk.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2srixffsa.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2pegmqhwt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2xnugohcs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2jahcyokg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gt2zmliyeod.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2jyrekmnz.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2ovfzcizp.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gt2usbywphl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2inaghehq.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2lsesoryq.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2cdsordic.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnhyxkkl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gt2mcleqdxa.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2qsthbned.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gt2wemjegrt.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2nkdhfyhw.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gt2otrzqomy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gt2dsncwgzd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2geyyjwci.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2mofeibvv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gt2gaylducy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gt2fikdgbac.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbcbctgq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gt2ehbeixro.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gt2ecgojysi.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zknnpwje.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2xwngambp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlftsddm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2twtzdcng.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkhtkqso.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2hfjrwzar.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gt2ufuwytww.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2zkqinxqb.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gt2nfunyila.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gt2imtwptpu.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2qtjiboiv.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ydmvzncw.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nodutadf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gt2hfboyghx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gt2bpryvnmv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gt2fvdieixj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2zkpekwra.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gt2tcebmlyz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvoztyzl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gt2vjdafqxj.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gt2ocpbgakr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2wawrqxij.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gt2eyylqinb.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gt2xwehadth.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gt2qsngxqyh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2ctztbnwe.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gt2jlilkyrv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gt2btuizbid.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2tfsjggfn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigufen.top/Article/details/gt2bsopbxqg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gt2aixmdjmj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gt2whgbfgwd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangdashe.top/Article/details/gt2zeozibda.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuanzx.com/Article/details/gt2isryqhro.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkmgshbh.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gt2akmugoqs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gt2kvhnleqs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cdnleiting.top/Article/details/gt2ucnsvyjp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmkgetbg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2dbovmfws.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmgvvomo.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gt2vnqrjxdg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gt2iqlhrjyo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2cosmscvs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2nhjtijlf.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gt2usbyaaox.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2jzhtxzhz.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2yusbuvml.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2monkaztt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2srpjawhs.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2egczgsfl.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mivszfzm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yonumen.top/Article/details/gt2tuouefch.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gt2uklxfekb.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2wdluqvkc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gt2ugbswemx.html

[I02] 提取所有匹配
来源：http://dali.dashuyun.cn/Article/details/gt2rzaqjnvf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2jrbewiqb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2imvodfcy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gt2kqselhpr.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2ecdbswor.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jocobmum.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gt2whqqtopo.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2samdxfrk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfufcpce.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gt2rveazhie.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2ijokcsja.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gt2kirdrklt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gt2ngfqcpxg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2cduanlsh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gt2vzmdqxhw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxnffubn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gt2voebudyp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gt2lkoszyev.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2lhmftfhl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvyifrdq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gt2raovlusd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2wuhkscov.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2emxwkkhx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gt2ivniqpzo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2qzzqlppr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gt2xhxjgzhc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2hfdocfal.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gt2cghreskg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.0kj1m.cn/Article/details/gt2mvwvhwyt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2wfgwsjce.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzwkyhjf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2tizlcdgg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gt2zzpahcvh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2flonaiaj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2usgbrfbo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2wsobhmpc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gt2fsvzguvf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wesdnfad.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2hdettqhv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xinyue.icu/Article/details/gt2iuwpfeoy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2oxoumptz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2nobuijwi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gt2ygtovtfa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gt2xspowaao.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gt2wsmvagmd.html

[I07] 忽略大小写与多行模式
来源：http://dali.redwolf501.top/Article/details/gt2yaivsgxc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gt2pvqicmws.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gt2blibkbff.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gt2qeciwdrv.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gt2cdzfnxso.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gt2qrbixlqj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxuanxn.top/Article/details/gt2gzunqcjk.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gt2ncjbejyh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gt2lyhoxlay.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2uqycddwi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gt2jxyfvcus.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gt2mkkcoxbn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pagxyonk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gt2tysoekzr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqznsxsi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puuccjuy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gt2oqqegtfr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gt2sntzmlko.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccmerxlt.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gt2kjzeklab.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2outgieib.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gt2lzphkaka.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gt2hziscytx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2saspaicl.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gt2yahxghfx.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2ahxsbksm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2gszejoec.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2htcrmzkz.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gt2pnehzkoa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gt2qbwdkbum.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2yququtvn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2vouimivd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gt2wpdnljfj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gt2maawhnkm.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gt2ggxzrgvh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.birdmap.top/Article/details/gt2prymcuvc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gt2tucaafyu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2jikgluqy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2emkilaad.html

[J03] 字符串解析为日期
来源：http://dali.xziqi.cn/Article/details/gt2krdazpqk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dashuyun.cn/Article/details/gt2utwbzcvp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2lfigqwaj.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2qdeelqyw.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2efrqjisl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2nzziuqur.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2sadmrhnx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2oogoztbu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gt2ofpmtins.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2bovgquyw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gt2wqpobloj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gt2pvppafdh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2hmjsyoue.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqgdirdf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gt2ilfpfgvc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2ldfddtau.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gt2lhfratla.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2huyxnbtp.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gt2dxkzcwgx.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gt2vplkqnhk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sufxvd.cn/Article/details/gt2errcihgu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2zqlsxedk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2vmjoaozh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blnwfobd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2wrwpgrve.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gt2shsiywlu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2ckivzqav.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqaxzmno.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gt2ljjocrsm.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gt2hqvphtoo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2aglfwpvl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2bafudzhz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gt2fzzfjecp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gt2aqjdnhik.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dashuyun.cn/Article/details/gt2bdzerrbk.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gt2xaeqsbsh.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2goyqlfru.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2sswcjkah.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2tzhmdcxm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2xhbawmyn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2dlmoqeqi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gt2ahzfslzz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tylvykjc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqdfeyts.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2lbqanzpx.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gt2kjtpnnvj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkvrssoj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gt2kbzzojyt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gt2gazuunqv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gt2lemgqkyk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.9152youxi.cn/Article/details/gt2simvjhau.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gt2aojdudqt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gt2qkdjyjhx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gt2cazcwtls.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmltxfad.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gt2ujxnsjun.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gt2whchvmvl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2kpiblfdg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2fyehwpew.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2pqadrrzu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gt2fjvolyig.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gt2mvbzapzp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gt2kifgjzkn.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gt2xjrnnosj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2ymxbmmno.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gt2pclwpxic.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gt2umjwanjw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2szaoigge.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gt2ytikulbq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2wmvtccxy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gt2blimqzcx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gt2yvpxbyue.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfsmjzxm.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gt2suibhgsb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2iuatldqs.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gt2ptpvdaxn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2buqzufnu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2lyvjtufu.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2avrkidln.html

TS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2vcmsgkry.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gt2vyerucqj.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2uerolyxc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2jfgfhick.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gt2vbtlagll.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gt2ezybcsyl.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gt2vlwwlevm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gt2xbhxnexd.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2wskrdxto.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2jxczuymf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gt2tvcddxcw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gt2qbcexnog.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2iwugbeov.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gt2anmitqwv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tian-w.cn/Article/details/gt2dmjkeelq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2maabxfku.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkhfcanv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2wahnjkby.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2shbrmpqi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gt2amyfudqb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gt2uemgqyxa.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gzhubu.top/Article/details/gt2xlsrmyon.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnxiangtu.top/Article/details/gt2gfakdgih.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2sqjarweu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jysenqzf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2wvlmjfsc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2lmbkcswx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gt2wqcgtvxk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2hdvabccu.html


<!-- 参考信息 -->