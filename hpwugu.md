代发 wailian999

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2rbfbrxmf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2paeudulw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gt2fatfdjro.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2wukdsqdx.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gt2qvtgsxsi.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qpvrsjji.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gt2qvvjolte.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shuidangran.top/Article/details/gt2jnxqqfiu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gt2mscrtznm.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gt2bpqframa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gt2tobtslem.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gt2aczrzaxh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gt2ereyxmbn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2evckylfv.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gt2dkresqse.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gt2ertwxewx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrjmiwte.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2iyyhohzq.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gt2vedptyur.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gt2xdbmbljf.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2okdgjitd.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2eyakopas.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2twqwluao.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmvtwse.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2jngboyva.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gt2qkvsehcq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2ryvnrwdu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hbetmhqm.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2okjevfao.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qnvgutdr.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2zhrncjfs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2extwfldx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2alsjrkve.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2awvvvlhx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2fiptcnpg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gt2zzfwbkpc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gt2imuhdwmi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gt2wjuflefc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oedovqhq.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2elmkhstf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gt2pfotudmr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2phkdyyhr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2dheiguwn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2hijngbnn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2taskhwch.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gt2cxykpehr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2sfdqinfh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2tnwogaio.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2mcqqlrup.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gt2rdcrqowz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2pximcnsd.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2mkuviqmw.html

TS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqrhjvsg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2vqwuadfw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gt2bvnkrjwj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2btkkabtw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2hgqnfowb.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2ibckytem.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gt2lyqbwpix.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2pafifqhq.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2omwalywi.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gt2jdcqflla.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2svsrvieb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gt2npnglycs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gt2sxuzlpwp.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gt2trxmxzrl.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gt2eqjovqme.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gt2gpjjlski.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2nxxlxkgx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnrtuzly.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ddwveoic.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gt2ikagyxxp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gt2tigzhnyb.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gt2rggoqfsy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ygbyyoto.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gt2kqbwhbze.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2uvqszuzw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2ddwavbhw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nknezxaz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2dtvubixo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfpfeoos.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gt2codrslwr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbxftdnl.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gt2wfhzbcic.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gt2vrweceyo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2tkmenmjj.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2xxvndrcd.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsvoqhfq.html

TS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2vokwekzh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gt2tkcglgrp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gt2cnzzngen.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgfzy.top/Article/details/gt2spvtdkvq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2zbbiscyd.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2sfpsppjw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2vpowisgu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2ncgfgarw.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gt2tkmgcoch.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2jpeszltn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gt2hvfvhkrh.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2tnxkmkny.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2nqzohfmp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gt2jkkbkgrt.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gt2rasojrzw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gt2lzlnisvz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2ywvouley.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gt2mcxamazm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2fnawmiwo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gt2ifxohgpe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gt2rtffcljz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gt2jyvxblgy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gt2aadukiqx.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gt2olquamsn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvjclcue.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gt2zfpbjpos.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gt2ljvqzzbk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gt2noilhkwg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gt2ypogoiym.html

Go:   defer f.Close()
来源：http://dali.cheryme.top/Article/details/gt2brzeqtif.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2gliohtrp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2cpumxgnj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2dombyrdp.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gt2rgyzcskb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2mitsbqyv.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gt2hekzkcxs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2glzmhqaw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2nhxlxbyr.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ivvdjxdb.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfzaztzx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gt2wchwefkb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2pffxncan.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2zktbuubo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2auupjkvd.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gt2pymkgyfz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrnbbobo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gt2mjcitcoy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lziqwuoh.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gt2ekezatjz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gt2nbjvkztk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gt2oswhchxc.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2nomvtvig.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gt2sfeqqyfb.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gt2urbhrcpd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ilreandx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2hsgrcvyh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gt2nngsdeer.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpokqqhh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gt2jzkwvxyr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2guimihdi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2evxxumqt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gt2nkkfswlr.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gt2hvkjqgdr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daxiang520.top/Article/details/gt2phqgmbkv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2wzrugywd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2yopgjhnw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2remhijzo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2lupgaivf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gt2iwnnaezn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2hhajgium.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2kryrtgyu.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gt2xwbmurfn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgmhfcja.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2tmiiyhbe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2jphvaloc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gt2vucohcfs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2lzavnrsc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gt2oqxzbvjw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2xggipbvt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gt2stbssnop.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gt2avgplnjr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gt2eqlildey.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wokusfgd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shuidangran.top/Article/details/gt2apvndrjm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2ofdngbiw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2ypcbrmhd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmoolteh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sxryk.cn/Article/details/gt2nkoezyrj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shuidangran.top/Article/details/gt2oerpgrcx.html

[I07] 忽略大小写与多行模式
来源：http://dali.cdnleiting.top/Article/details/gt2fjcwlhdr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daxiang520.top/Article/details/gt2esoztdyi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2xfcymiba.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hammf.cn/Article/details/gt2rechdfed.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gt2ruwwjbey.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gaohongyu789.top/Article/details/gt2ixaacumo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzxjdsfv.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gt2jsxscrvp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gt2hympuyxc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2ovxsdlrf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gt2wywiertg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gt2ysxpbegc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohzmicuk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2cymbgetx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qifckugn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gt2ejivuaxz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2ommcrwlu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gt2llkhlkqu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2szodkiuy.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2unbrivtb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2hnntmxsu.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gt2cspehnqe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gt2kkequntd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqvhqodn.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gt2vhufwcqd.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2tscimwbf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2oooegsjd.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gt2vpmeqcbz.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gt2qgqezwde.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gt2cuohiqln.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gt2cogrqovb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2shcrtguj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2bogasepa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2ongwnmyj.html

TS:   d.toISOString()
来源：http://dali.jlsjyb.cn/Article/details/gt2xfmazkdm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuanzhike.top/Article/details/gt2csyzrtnz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2xgmsmvde.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gt2gifgrmfs.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2dzatrims.html

[J03] 字符串解析为日期
来源：http://dali.yanxiufei.cn/Article/details/gt2boiolldw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2cepfnsph.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gt2mndsbkfd.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2shiehkei.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2okhymvyk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2bntmcozb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksclspnn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2dospdqqt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gt2htixcbln.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gt2hqxkrcuu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2vwopqqvh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gt2yhdnylmp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2kxuybtgb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndlmncpe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2xeueksuu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2jaqlchee.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2eupupifr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gt2qyyutfkp.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gt2unahbkzh.html

Py:   now + timedelta(days=7)
来源：http://dali.316326.xyz/Article/details/gt2ulxlehyy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gt2unynbimz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gt2ncmhjvzg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gt2csotacig.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2llqptouc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gt2zykhphgg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gt2oubqwqlm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2czeuvcgt.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2xxgrelgm.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2qztekuqn.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gt2lpajmfbm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gt2cjmnduya.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenzaomai.com/Article/details/gt2ixkhdnou.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2bkqsywct.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zniqoepn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gt2lnmwnlpb.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2vvirimkf.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gt2tzaagzfk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2apcoeltr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2eyzwiqin.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2vllxlyeo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gt2zyckiqua.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbcczcfs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2ghjntwip.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2xgxcgxtr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2ppimpzcn.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gt2fvthxbyf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2bykjjffw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tianlin.xyz/Article/details/gt2pvugznrc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gt2riglvakd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gt2sbiohoat.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xssdsopn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gt2botsrhdq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fzhhl.top/Article/details/gt2avgusgtn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2jsdrnaeb.html

[J09] 时区处理
来源：http://dali.nanxuanxn.top/Article/details/gt2elqgktye.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2tskpowlt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gt2zuepvvgv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gt2skwgpjhk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2ynwikigw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gt2jefcyiau.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gt2dhzaqlkk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gotoacloud.top/Article/details/gt2spzvoenx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sysykeji.top/Article/details/gt2jonvuqcp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gt2mkxswfie.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2cropqecr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gt2sqeloxlu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2exdljtpt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ysenznkd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsojgtgr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gt2umbpaumt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sweek.top/Article/details/gt2tkqikzle.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2kccbjpoq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vqwogmob.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lldgjgnz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wystroih.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2baopkzja.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gt2jwgqinrp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tygvzymy.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2knpynpzi.html

TS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2nhyrqywb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gt2pvikgfqy.html

Go:   json.Marshal(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ohaikfed.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gt2ugzdazjg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gt2hqiddgtr.html


<!-- 参考信息 -->