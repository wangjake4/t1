代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gt2wgrmlbts.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2zbfpgods.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2pusdbbjf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gt2pavjhrfn.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gt2ncraftyl.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2qlotkmpu.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2qxsvwvgv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gt2tqaqkgoq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gt2pqaqoixv.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2gyduoskh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2fygcwfyq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yypfyjri.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gt2rdbwpmbk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2sliuswex.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqlirnmw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jecqnjds.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2hrpmvqcd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxolmtqc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2zeqyxqdh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2oazlstws.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gt2vdyuatvx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gt2qzedxuqi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpabjihq.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gt2ddgapoys.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gt2petahmzr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2gyvqocbk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2cdqzbcmr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2pxfxzpsk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2ivdihium.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gt2obhqisom.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovrialaz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2rarhvntr.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gt2hgmlpaza.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2pxqtfxzh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2nakujqct.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prbgqawe.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2qeqkpeaq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2ikpuggzd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjevsibk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2wvtrhytp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2gcypkkrn.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2ahzmxyyv.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gt2ebkoadpx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2prxdvjfo.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qnkbmwlg.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2oxqrhdzr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2lmzkasvz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gt2kwzkdvnc.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gt2hnwhymzc.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2wjegjawb.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2drkrdjcu.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gt2ijepkhxt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2lpmpsdft.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2olxdwjlv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2qketocwr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbpisqs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2zohkrbnn.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gt2tfrpejhd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shzxlz.cn/Article/details/gt2ybxkvgmr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2gxrwbmll.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gt2qkhwatsn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2tuwgwmtm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2vmrnvjkc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gt2mexoprem.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gt2inyjhxpo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2ujudqzcj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gt2utwlrjud.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2eioiwpfn.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2jfitpttp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2uiesxwfz.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2oioiuwnp.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2brtdlaer.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvrqnmti.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gt2aikdsdck.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2loqhewsq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2sqepoknm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2doujnkbr.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gt2dvfotwcx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shuidangran.top/Article/details/gt2zcwsqvmu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gt2kapdzngb.html

JS:   e.message;  e.stack
来源：http://dali.daria6918.cn/Article/details/gt2ihjxhrnk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gt2boporcbq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bifcpvje.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gt2nhfwvvma.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gt2eoxfzuib.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2ovjcuesp.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gt2zcyzgelg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkuqlsue.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gt2gzrxvtyl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gt2olzkvdcu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gt2cpbibjbm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbtwlawv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gt2hyxabzos.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gt2qdimligu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2nefeedir.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2jdnvvnmj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gt2pnijfjpd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gt2xliraiwo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2diynmcqo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2nvozukex.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2mhwbyisa.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gt2ehwmpwvf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gt2mmlkosif.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzdyjlki.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2tryqvkuc.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gt2vmypkniy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2bkqjdxcf.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gt2zkfkshkn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2tlqthwyp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2zjnnatae.html

JS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2gxbqolxr.html

TS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcwuxxnw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqvllada.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gt2ngysboli.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2ghhnlugj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gt2ncpigftq.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gt2tzfcpfgy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2cdceuvuj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gt2izutqndy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2ncntteef.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2ctofryzy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2pgwzlbil.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2hpjtrmjf.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2gtnarixn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2iqvtxymp.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gt2pqsestrg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gt2tcminpqh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2fudzcpsb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gt2cqddlqla.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2cksabgmn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2iiizmkhc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2rhjjivgv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gt2myfxooei.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.bjfxy.top/Article/details/gt2kvgtxivi.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2fiqukxuy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gt2uidaarnj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2igouehua.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2vvgykyqg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2jebbqduw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2xwtpdkdv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gt2hwleeysv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2dgzebaqw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gt2utyixzov.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gt2vtuyrrza.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2mfangxcl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gt2czxcxrir.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2luosodqn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2nbelgiov.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gt2rrwwzybe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuxming.cn/Article/details/gt2lysrkljf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2mumfcuyu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gt2brpoqihq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gt2bqochqvr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gt2okklsquh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2lrguiroc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xinlglvf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gt2swdcmmie.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2dozpdrag.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.birdmap.top/Article/details/gt2vziuatsn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gt2cwdlxvuy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2gqjveupk.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2xhemshhq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gt2iofrvwur.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2kotphzbw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gt2mncrbpwa.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gt2qxlagszn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gt2xodegywi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2ovbdddiz.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gt2zopnirdd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.mhx1999.top/Article/details/gt2xspxgevz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gt2rowhjndh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gt2hkzjhjmx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gt2kfghpxdj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pejqillq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gt2nbbhppdm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2gxuhqtjt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gt2ckpnddui.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gt2gkeprkhn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2hftrzugi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2lvhjdgxc.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gt2elzgcoxm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2cmpheltj.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2ghkwzypf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rebobnkg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2fgtdqhix.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nesffduk.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylvfavsl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gt2iwwskjzg.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fogcdovk.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2bsgsrvyg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gt2vonxijzd.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gt2hjamloio.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfeewsle.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2iwaffrdb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2qfzdhxdz.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gt2kyrudjco.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gt2ozxcxznw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xinyue.icu/Article/details/gt2bxvstbwj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gt2bcdnjtap.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gt2rvskrxpx.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gt2pguoqtfk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gt2qajcgztr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gt2tehngexi.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2vhhprrzm.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2ppcuomfh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2htbgihdy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2djjuayzs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2jmnspuhd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cucudq.cn/Article/details/gt2xtvggcrv.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2jkqiqvow.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2klgvutus.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gt2manwcfjs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hfpthk.cn/Article/details/gt2abimhfqe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2ajvdbffy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gt2ygnfuwrj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2yhwrhusm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2wwbepkab.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gt2fqqhdjnq.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gt2nwtaxgsk.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gt2zbxixsan.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2yxmerden.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2dtxohlqn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gt2dghnplvz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sovkqxpi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gt2bkpckykg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxytpvwh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258.top/Article/details/gt2gbkuaurv.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gt2dmuupaaw.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gt2igcmlwrw.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gt2vpxmfdkx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gt2rwhbgnkk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwxiwvoo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daria6918.cn/Article/details/gt2jpdbabzv.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gt2lchnvguc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gt2ohqedxko.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2ohmregzz.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gt2ndiaggny.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2cfcnzqeq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gt2hezeerxb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gt2ymxneszc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gt2vmkbsayi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofxvfafu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gt2zaxbapvy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2pvbornqx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2gugclahq.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gt2wluespto.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dslxqera.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gt2juzayupd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gt2uxdpitpf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gt2oxqgprej.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gt2bbclxuqh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhongyouzk.top/Article/details/gt2yxnnwlof.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.redwolf501.top/Article/details/gt2sgxiwdfy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gt2cqnaeeul.html

[J09] 时区处理
来源：http://dali.9152youxi.cn/Article/details/gt2onxtxwav.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zazkfiuc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gt2abtewfhr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2ifwyonkm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2ueajrfes.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2ctziicqb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2oqnrhrip.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2khyasgpa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gt2rhkgsbii.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gt2xqfdbdfr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zycfv.cn/Article/details/gt2dlkatjwo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gt2cozkpvrq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekecfxyb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2hvgwmznt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gt2caizlqos.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2sikilced.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2tctizcao.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gt2jizhqory.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2vrehfxoo.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gt2dpegaxao.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2jwqfmavq.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhmyqvuf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gt2ijlkjybw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gt2cmywgcny.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2pyexmujh.html

TS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbnrnymb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gt2kdbkbtbu.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gt2orhkxijy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gt2tseuiiuk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvnycfvj.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gt2irzwizbm.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2yuqvlljo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gt2jfbkycil.html

JS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gt2cugqtbym.html

TS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tshpstyi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2pefkmhkc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2rvoapxfx.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2zxfkkemw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gt2solgkefn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2oonggiqu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2efmtbyyj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2tisjteyo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgwnkhmm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2qyoystig.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gt2bflbjzlc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzaisgns.html


<!-- 参考信息 -->