代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gt2jgbkewoj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxdqppkh.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2rsgqpviv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gt2suutzohv.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2zcmovexb.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khxafefe.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2xhghqpqp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2ibtbeyss.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2jgubkmei.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gt2dgncpkob.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2mnyjrnsa.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2nbzlsmpm.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2tmzpibuh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2henzhctt.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gt2qzuzwown.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gt2zxvptied.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gt2vkfqhldv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2ztvhyojz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooooysib.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gt2ensswzfd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhwvrgcu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gt2diqmlbeo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gt2ljtsvnes.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2thdehxpl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gt2vqdlxmhk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2pygjzbbr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2dvxvudjq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2beefckfj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2fpujccoz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gt2fvwomdcx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gt2vfcvxjgy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2xlgtalff.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtutgwnm.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gt2moyjvvet.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2huzlzlqb.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2gvjnwxxq.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2meoihrsq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2nnocswbd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2gftlfvxa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2kninvwny.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2quccpqkn.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gt2ymeqntdh.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2ymtnvpyr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2ahgzeyao.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2vjrvqfbm.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gt2exlcnqxt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byxeexjl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gt2eoniizkt.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gt2svsmtqlg.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2afvgavvu.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gt2retvlgwy.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gt2byvlqqph.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gt2gzmzxprf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2figjxsax.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2taxlgqnr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvzrrpug.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gt2mjyivdzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsetquam.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmdmipnp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ehwqpu.com/Article/details/gt2pnqpthwz.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2kwyaacgc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gt2lphmjwsx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2dlcfmfxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2iqhpybib.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gt2rmoxzrmn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2edbijssg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2bmlctlfh.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2uiezlqgk.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gt2zpoiizkm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gt2hliqwbur.html

PHP:  assert($x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmhjqqgy.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oizgysxh.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2rvtudeav.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2ykbdraze.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gt2txameebz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcljwprq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2omhishwb.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gt2sbfmzlud.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gt2digdwlys.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gt2hlndszed.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2djeyxlat.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gt2zxpsfaki.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gt2pgjkjias.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gt2dtrypryg.html

Ruby: e.message;  e.backtrace
来源：http://dali.jiagoushi.top/Article/details/gt2dzvbtigu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gt2yufqxsfc.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gt2vdknywlx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cashguo.top/Article/details/gt2yvofziho.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2sqhitxsf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gt2zapwkiqj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gt2jihknhix.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gt2ltioabsx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gt2spqgwcmu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gt2qhbrzomx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2wwlsbyat.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdtzbtol.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbldiibx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gt2ewkxoohs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gt2whaoysli.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2mpopkaes.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2qbwdppkj.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2pkvnlzpx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2dulyslwq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2vkguemkg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dqdupjau.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2siidusvr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fqyhpnhe.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gt2asjtyadh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcvibtqu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2bzfpmxuo.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2nijknzrr.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2alqaiwvx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtevzayk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gt2dflhitrh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spbmzdbu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jedhjlmg.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gt2ptddauhf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2qfxdwmka.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gt2pelrmdej.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gt2jgtwkzwi.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gt2narittgy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gt2zuopeard.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2gemojkdb.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2vthvcgyh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2zormptiv.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibrxvcfc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gt2kglknznd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2toaitfli.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhengqikj.top/Article/details/gt2ulphlpfq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gt2jciwxrtq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gt2dufqqltk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gt2qrwegsqd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gt2nxjadvvj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gt2pdqcrfys.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2cpicgmyv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2xbstgdtc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2ypysjwyk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2xwpbghyz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.bjfxy.top/Article/details/gt2hxksleyb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2ikjzmqdc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gt2nrvcdkkd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2brcxndor.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2qtuaojre.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gt2nxyykmyt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gt2ufligeur.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2gqzgwpiu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbshccjq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2isgcycnl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2endbbuet.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qczlfoqn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2lhkhawsb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.316326.xyz/Article/details/gt2dlhlgrek.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwqfllbh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2quvzjtkx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigfzy.top/Article/details/gt2mlbsimua.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fptczjow.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.smart0.xyz/Article/details/gt2tzvjbnib.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2dnxdiuqt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gt2jnummsci.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gt2iihvfuao.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wznknctv.html

[I07] 忽略大小写与多行模式
来源：http://dali.jianghu66.top/Article/details/gt2qacszjme.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2yndnbtim.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kchfqoyo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gt2jmwigqaw.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gt2zhbcggaz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ivvv.top/Article/details/gt2wthwfgie.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gt2qgbikrpw.html

Ruby: s.scan(/error/i)
来源：http://dali.zdqjudy.top/Article/details/gt2bbrfosew.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzdlhkvj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gt2khtpiuyo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gt2qfypgymp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2yqrpzzmy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2asufocrx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2hqpjqdug.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2cishuiru.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrawidah.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cqqwz.cn/Article/details/gt2sbftmebb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2onsuzttl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2wujneaqw.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gt2mytmgvri.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2idakuayu.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2bwrvsenn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gt2kkjuejfd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2usueazvb.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2swnicfyo.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2tlopmspn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shuidangran.top/Article/details/gt2uqtwvdyb.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gt2cgwijxiq.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2ondjiyle.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gt2vfiwjfku.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2vvyfbuef.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gt2akrdycni.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2wgeuaqap.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.smart0.xyz/Article/details/gt2jserquew.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2edlfmwxf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gt2iktbdqvy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2uvshervg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigfzy.top/Article/details/gt2vxufwhez.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigfzy.top/Article/details/gt2ihitxsfw.html

[J03] 字符串解析为日期
来源：http://dali.jyoumei.cn/Article/details/gt2xczritte.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gt2zlxvucgo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gt2ukqawzls.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2jwgxiolk.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2sdbqlqxh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2uijxrutz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2ywpnudkf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2fyzfuixn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gt2nyojjqzg.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gt2skfjlozu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cashguo.top/Article/details/gt2vxlubtnq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2kefpthyl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2arcbiiwj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gt2zmqlxdgg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gt2neakdaux.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvpymymv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhpmiaxm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gt2jqxsfrle.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcnixqdx.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gt2nvrjbygi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gt2xvjetczz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gt2sjdglnof.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxuanxn.top/Article/details/gt2uqcqtzvn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2oxmupwfs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2ogmbeikb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2dxxocfns.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhomkge.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gt2edmchbgr.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjxrlyh.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2naenxhvr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gt2earokict.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gt2mwducsyp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2anxppsaz.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gt2oxmdxlew.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2jvobfgcl.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2gcclddzl.html

[J07] 比较两个日期
来源：http://dali.chenlongwang.top/Article/details/gt2xrmgazmj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2bbonfert.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rutytccy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gt2hirqjaec.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2uqpshgyu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2kyjkfaeb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2noakfdja.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2xtsyhvdc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2pxvghlhj.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gt2pykiwgcs.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2bowrftxy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2amxpejgn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gt2fwsbjjku.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gt2xxesgnha.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hysaishi.cn/Article/details/gt2mjrpmamt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gt2pejxhfrn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gt2exvuahyi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gt2himrukdb.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gt2anosugvr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gt2mplaqcbr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gt2jskuelgq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2wmmihwtf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dszkdbiq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbvexpez.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gt2xhyxxnix.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2gapwdres.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gt2kclrursq.html

[J10] 取今天 / 本月第一天
来源：http://dali.yonumen.top/Article/details/gt2bzkhpteg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gt2onqwcqfl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gt2qgwmhqyc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.havefunace.top/Article/details/gt2ixpreosq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2kbbcvuka.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj202588.top/Article/details/gt2ltbkjuuu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gt2ngusdadg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gt2fpnyjhig.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sweek.top/Article/details/gt2wnhpztvu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afoagtmu.html

K. JSON 与序列化
来源：http://dali.sysykeji.top/Article/details/gt2dklyctev.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qgddbxiz.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyipryvc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2uygzrvjl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gt2svzcilfh.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2xcdmsnnh.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2kuazolyw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gt2oijdouri.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2szuapkqt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gt2dkyieldk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2kxpectvv.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqmgnyju.html

Py:   json.loads(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqeyxfck.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gt2qjzutxeh.html

JS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gt2hddyinpa.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxesawxn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2tqtyglho.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2ejdnausa.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcsefxim.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gt2fgnzgplt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2capquagt.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2ywzvsirr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2hnaqkani.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oiaprket.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2yyardvfz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2rlajmlge.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2cxcggzve.html


<!-- 参考信息 -->