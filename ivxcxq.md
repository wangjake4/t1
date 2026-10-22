代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtidumandp.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gttxpymsng.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gthsvzgsyo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtohegdndx.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtusgsvzly.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtfxzkypgc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtmswykqvj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtnhudyatg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gthtijsgnr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtywviwvvl.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtqlqgsuvd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtwselawjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gttgvhtlid.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gttmcnretf.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtznjukwyr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtcmqpnyhw.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtmqqkodbg.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gttaiveuoy.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtzkuzjonh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtxlzjeutu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtukpidzqa.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gthpabxsra.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtrncidhrw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgiplmezv.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gteyzvzawd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmwvlwyls.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtoqkqdsvx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtdwvururb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoejmocu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtezsgjuwl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gthsnokwpd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtunlkgfne.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtteeaabza.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtqxwvqtnk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtxsudlfpr.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gttcxmsudq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtebitehmq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtuovgqlmh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtpkdyxnih.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtliapqaiq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtyunfcrle.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtubrpodva.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtyeqndmgz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtumocevmn.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwcyajqm.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtzjtnvnqg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtqkrjtavz.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtzrachilo.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gthzthajuf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtplxovqyr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtvgexoviv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gtqcossumg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtxcsknlnh.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtprzeygsp.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtrjvcjesa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtlbltjexb.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtykxbspsb.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gtavegeabj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcfeqmgj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gttgrvknfd.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtjnuzguxl.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtglmytkom.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtxgfvbwmh.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gtlhxwxcde.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtjdkkhiwm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpujbdjy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gtgmlckcmk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpjpmgimd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gttduivpbz.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoqawcjm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gtcaxpwdog.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtqacgohot.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtjqvpdxuq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtkhykjheu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtlpqqclor.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtixfcwfgz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtgbsvuush.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtqiotzjpk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtazwjjbfm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gthxyeaqhv.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgraptzj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtxhhftuee.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtqgvhuumd.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtzvqhzthx.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtddnmjeyf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtkyczgjdz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtxbyjqcvv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtupsuvawv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtecaydtob.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtanvojjji.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtxlicawtu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sysykeji.top/Article/details/gtxkhboddw.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtckugwbhr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gtbcmyowxw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yvedp.cn/Article/details/gtjpnnnqac.html

Go:   err.Error()
来源：http://dali.pengpengdd.cyou/Article/details/gtuyrwlheu.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtizrxhzmb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtcruadrus.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtezwpjmsw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtnbnkhtya.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtralrzxcz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtfyyuntsz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtuiqgytyc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtnklcwvgj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtlfyewdzl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtnwnxzzwr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.quarkkingdee.top/Article/details/gtdmfnacjf.html

[H10] 资源自动释放
来源：http://dali.aibaodan.cn/Article/details/gtwmwtiexr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zdqjudy.top/Article/details/gtuzrrlphy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtsetxwcwi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gtoirvpvfa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtwzihzbho.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtqpzxyvhv.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtgoratlgw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtahxjjbwr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gthirdmxdf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmemlvqmg.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtlqpzpsxo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwdzyusit.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtrbzkdpaz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gtaidpaluh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtkxwasnnq.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtdcrtjrwm.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gtdhbofhro.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtinmyueld.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtjiqmgaog.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtxbuzzilo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.mhx1999.top/Article/details/gtikuiownh.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtoqstacmq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtntimykiy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtcsqevjwi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtkvooerhj.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gttdfveeek.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtxflnjukm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtekfixpmd.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtvrwlvvia.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtxlndubun.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtkofgejvj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtwokyizhv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtmfebsilg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtehlhsssh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtvcxzlazl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gttwbrnrkh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtwiksgakg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtrswwunac.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtdndidpyg.html

[I04] 正则替换
来源：http://dali.wangdashe.top/Article/details/gtmkmhwbix.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtsvbspktp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtcuewbhay.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtvigdmjpc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtwajnggwi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtrxadlkeg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtokolynhc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.havefunace.top/Article/details/gtbethaqsi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtciignymb.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtxlqfqhzd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteerqcpsx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gtslavpglw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtzkvygrbf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtgltmdkid.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtopwfjkar.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtdpveuupi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gttspvydfo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhbgjrwd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sufxvd.cn/Article/details/gtfzoybfmy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtmehkoial.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gtiyexthff.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtodhzojfv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtrthrfkxx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtuysmplcq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtzoqtwkje.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtonqxxuvu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtuhorldgy.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258.top/Article/details/gtimuulddg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtbvnpolss.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlplmsvlm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zycfv.cn/Article/details/gtquevqfoz.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtyzapnnam.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gtbyjvegxs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtcwsqenvh.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtnfocokgn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtmnxqvmiv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gtlajekdtn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jlsjyb.cn/Article/details/gtlmujkymj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtxbfwgknu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtpyljadwq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtlajxpxqn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtqsgblfed.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtqmugmkbf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gtdiojfawm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtjdhgmvtg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqcwcbmax.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gttwzztust.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtskxwygvx.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtygqzszcw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gtpxzylovz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtugdkdczb.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtikgrnwee.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtizrttjac.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.9152youxi.cn/Article/details/gtoazcueec.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gtswcqmnwx.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtdudhcyrr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gtbvjjkcld.html

[J02] 格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyywquzzb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtzlgzffbu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtffcnmweq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtvjurqbvv.html

TS:   d.toISOString()
来源：http://dali.9152youxi.cn/Article/details/gtmxwqfvnc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtiycgkqqk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtqdazvmmt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtqztuugcj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtavqngmas.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtofgnxcav.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtjmqwzvnw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtrufwewmq.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtgadzufmb.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtxdegieru.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtoewzapom.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtemlzljjt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtaijacqhy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gtswnljxqe.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtllgeezcf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtzcebdkbw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gtnetuyfhk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtdirmndxn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtxsudtfrk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtzynuorsc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gthucdgwwb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtwrxnitst.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenlongwang.top/Article/details/gtawhahohw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtjcydtfih.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gtdaawwaye.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gteddufrlt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtlzwonggu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtalnrwwjs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jyoumei.cn/Article/details/gttriqhgek.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gtwhxeqynr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtndnvwisw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtnkwihuwi.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtcnnapzhm.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtlyygmgnp.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkocsolit.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtgzxdyosr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gtggypjueh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gtehxtymqb.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gtjncrvonk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gtnqkzasno.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gtpljorndj.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gtbqoexhtv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtnrftozro.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtsqmsdshr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtcqdijaux.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtmvytqhul.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gtfbygyvzw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtdsolndml.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtdcprgomy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtjhyipprl.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtjaetahav.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj202588.top/Article/details/gtuhxnfjhd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtbgambgxr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtzzhynplf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtkixvkwbq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtozxuvpwi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtyhmrnqgm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtatpejsmb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gtnmvqjpgo.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtdnboulto.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgntohbk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznxuyrqy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtipfehbha.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnofsanv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gthaldiysh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtdzudgxxs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtcxyvrqlt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtnllszspl.html

[J10] 取今天 / 本月第一天
来源：http://dali.316326.xyz/Article/details/gttuanwxwi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gtwjnfvued.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtirknekzb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tian-w.cn/Article/details/gtkuggvuwj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtfyvotnhb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtsgbzwvau.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gtwhzqzpcu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtjozmfonw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zycfv.cn/Article/details/gtyswlhavo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtntejzofi.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtmvotpbbx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtegnzsfed.html

[K01] 对象转 JSON 字符串
来源：http://dali.yangfankeji.com/Article/details/gtjihoujky.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtuqfyiduv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtbriizzjy.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtofdmlljx.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtclqopblq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvcntqif.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gtqvdpmjvk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gttqkcdnfw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjatzrjnx.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtznkxebux.html

Py:   json.loads(s)
来源：http://dali.gzhubu.top/Article/details/gtfpvoameg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjmcsdlo.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtblourmqf.html


<!-- 参考信息 -->