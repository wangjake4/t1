代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.c1oappe.top/Article/details/gt2ncddsnhq.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gt2cqdsrfcx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gt2owbtbozr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlqbetuc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gt2auagusys.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2jxdfofor.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gt2qisaaymq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gt2ghwevjai.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gt2yrrncurh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2hjiwthuh.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gt2opatcclr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2poobvnko.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2iyahzjwk.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2uddsyhwh.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2pajjuydv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gt2bwifnkxx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gt2uoptuqvi.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2rorccpmj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gt2daycwdmw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2tvofutqw.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2viofufgy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2uazebnip.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2feqqomtf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2zaizltcr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gt2dfvnvdjt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2wiwudjhd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2pupqdoot.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2cptnbxvl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gt2lemqaxwf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2pyhvczqa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gt2lrqhhsjb.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2omefqotr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2vwdugoxq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2iucbthkw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2reddluir.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2iytrzfxp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2hxdijvxc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gt2tjuvxuli.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gt2abwttdof.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2vbozbqjk.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gt2gzpwqhpj.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2dcpoyows.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2rkkzjnkf.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2kediajbc.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2nkcsxhnk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2vsdsaxmj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gt2rvmxwkkp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czluiian.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2okqrgtir.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gt2utefbmdi.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gt2wsdtsqiv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gt2nheqhmlp.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkddmklz.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2cspceyos.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2nrkizpni.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zafxduxf.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gt2ngwmkero.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gt2xtoootgo.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2tzjbwmus.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gt2oizkgovg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gt2tfhoddmk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gt2zrraifwv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2thlvtzre.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2jwjbccyk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gt2csedsmuf.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2akjgyuud.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gt2pfwjybac.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gt2txijyrjd.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gt2obeqfgkk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2pwtmvmjr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2zfcaparf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2mkdkwbab.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gt2fxhtxqbb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htmlnday.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gt2hbgbvvlu.html

C#:   obj?.A?.B ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2kfkyyhwr.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2selveozp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gt2exuwpiah.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2kbhbhnid.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2cyxnfkne.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2aypoqrfb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqvsiqdj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gt2ipknledo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gt2luumwamw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2rkknouls.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gt2ddgayaqx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gt2sklmmxam.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gt2kormylii.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gt2zkrfrybh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gt2dyvbdfub.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gt2quwkxyhn.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gt2ktkfkxam.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gt2zvxmpfef.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gt2ojoryhsn.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gt2zgguwaeh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2oimvxgqp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hywenlv.cn/Article/details/gt2iuzkbthp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2zhkpwprh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gt2jcnurtsv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2jnsuvtsc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gt2hsgrunbr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gt2hojxrfpf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.smart0.xyz/Article/details/gt2oqxektpq.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2tuervoak.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gt2tmbagdcz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gt2ecjeuqhr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2xcfxdpce.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gt2erblphjy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gt2gjbpmdak.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gt2ozohemdo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gt2dsycnsvd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2fpftzykx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2bsboebgp.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2buztaclk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2rgjtesxg.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gt2lmposaan.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2mxhwgopw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2rpnnimyz.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2jwhczwxz.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2sydrbniz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gt2hstvotjk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2kfqqygqf.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gt2vqtdzfee.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcdlzwsh.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2txxoauiq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gt2nmcthfpk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gt2rxqcptox.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gt2pwpaugau.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2axwsnqnn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gt2wniomfgj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gt2maylrnsf.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gt2mqfezhqt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2rnyaenar.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2uqcojyie.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2wrqanydd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2cxayxdpp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gt2llsprwem.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gt2xirjefut.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gt2adxacifh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gt2gcdedemm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gt2spsjdesg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gt2lrhtzzbj.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2iggfeyzb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2gggcvmkq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2cbvrvxas.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2xrhfeylt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2wlpjjdzn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2bsozlwji.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2hnefbnew.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gt2wwsgosmx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2zaglstpd.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gt2kdcmabig.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gt2oodsaeqj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2nkrmuuhu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2xzirhvxc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gt2unoevomz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gt2lsbckhsq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gt2bmouafik.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2ylvcmmwj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2xbkjconp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.0kj1m.cn/Article/details/gt2umpvgcwt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2yqaueuhj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gt2meupepxn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcslysht.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gt2cxhpldal.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2aescodte.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gt2xzanxjqg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzgcfpic.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2bkdtyfol.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2amuyyeih.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gt2tfllyrvu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gt2zvxivekm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2kwdvbpjk.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gt2txgdbszk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klupvgci.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gt2itmoetow.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gt2ffhettyy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwqwwync.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2rybjsagm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gt2yvfzqovm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2xtazfyzs.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbbizdoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gt2dhebvghv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2oiexkypt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gt2ynnxxkzl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gt2usvifrkn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gt2wrwlzpqp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2lmdsnqlu.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2apjmuiti.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ohjjjugh.html

[J01] 获取当前时间
来源：http://dali.gzhubu.top/Article/details/gt2vfknnvdb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gt2fwqmyovs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2pqczjuxx.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2tszvitce.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2oxlrattb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gt2gnvewsgx.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gt2zfmgtxfk.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gt2rnydkdhg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gt2qfsxbwls.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2ketvvdwi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2xdxzgrms.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzbwjmpo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofbmmfrf.html

TS:   d.toISOString()
来源：http://dali.jianghu66.top/Article/details/gt2erjgrmae.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gt2mzqoajft.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtlnopzb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gt2lexlaack.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gt2lnzxabpi.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gt2kyxegexs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2ysnokzls.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zdqjudy.top/Article/details/gt2stwvivjh.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2jbylqmts.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2acqwpnuz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2oknltysf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2qafcvywv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2ugheksda.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gt2rhkyqpmo.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gt2fbhxppod.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2cluatydc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daria6918.cn/Article/details/gt2mcsrzyhz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2uhnsnsrm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gt2ympaipko.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gt2ndqlhqcw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxgfdqzs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2wysguetx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2opfhvhaw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gt2bckfuefb.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gt2lczixxgl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gt2dngmppbq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gt2tjjbdgnr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2trhokxfc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2qkbaoklu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gt2twcqwwni.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2xbphacrk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gt2jkdcnayd.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gt2kcbshyxt.html

Py:   (end - start).total_seconds()
来源：http://dali.sxryk.cn/Article/details/gt2qzrmdfzd.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2zyombuhe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgnonak.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gt2xgkbunje.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gt2zpjlsbns.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gt2pluqomvv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vevsrkyq.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gt2bfyzhlcc.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdbjsmqa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2ahkdyqlr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gt2bjbjwixc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gt2xosroktf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xguxipwm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aibaodan.cn/Article/details/gt2rtjuyojp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxinkj.top/Article/details/gt2fekmhlxi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2aohwknpy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gt2zbixsjjr.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vficeszt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gt2vodsftfz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gt2xtkcwgcr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gt2ukhuhgqo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcjsqyay.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gt2vrqrpseb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gt2flikulds.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2sqcbmtck.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gt2bqoloyzs.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2wrymruoz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbblagw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gt2vzkvaqau.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oprdawxy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2qncbjalf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gt2jqqemuxs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jiagoushi.top/Article/details/gt2tdziquwh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gt2buylyqkw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2cmzqzxss.html

[J10] 取今天 / 本月第一天
来源：http://dali.gzhubu.top/Article/details/gt2wcexluko.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gt2tabodujx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cucudq.cn/Article/details/gt2dtvkzssw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2erptyeaz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptoopudi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhawuapl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gt2llwudliu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gt2zavutfpi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2rlzhhvcd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2pclxmykt.html

K. JSON 与序列化
来源：http://dali.jyoumei.cn/Article/details/gt2wsmumqps.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukxurjee.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gt2sijlwbvd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2vyepmtrb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gt2nbgfhjiv.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2iletkvcg.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2khjkeljx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gt2rztxhlej.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gt2dqcvzgol.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ybcxt.top/Article/details/gt2dfaccfpu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.smart0.xyz/Article/details/gt2thgiyasi.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gt2hwsqayec.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gt2vhdkvgfu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gt2itkcivzd.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2dbwskrhy.html

TS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2iksbbzfw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2ogrunrma.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pizenore.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruqkeraf.html


<!-- 参考信息 -->