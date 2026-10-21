代发 wailian999

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gttbokwaiv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtpmglnyvy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtmxozalyn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtsrohjtrw.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtwgcpdylf.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtuhxvpvjy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtrypwggyk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtnotmpncq.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtxqfkafpo.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtxijeiyqf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtqeqyrxfh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtstufyveg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtacutymzu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtiizjeulf.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gtmcqqmmlm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtniaozdjv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gtlemfdqus.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtgzedydtp.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtixzfhcaa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbpkkixa.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtwsqzlnpu.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtxjzglkkg.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtumggwxkv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtkczkugwd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtyuoieqhz.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtlftuptyo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtsivkjohb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgfyeqxwp.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtlwoqnmkm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtonkvyaxu.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtifxjkrgi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtnaquorqi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtdoqhmrny.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gteilnvwax.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtbexfgsym.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gtjqagtfdn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtpnplusli.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtrsvqlyfj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtivvirtig.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gtolayfkbn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvphovma.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpfsgwiul.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtrjsunvoq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtrepafifh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtriiyivca.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gtbeyoznto.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtijncuzrb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtlkbqcfba.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gtvhyxqjds.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtorqsmloh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtcmnwwuhp.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtpwuiiaxx.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtawyfaixx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtlhmcddcy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtxoqwnhde.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gtiwzqgluq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtsznsetol.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gtvpzoqdza.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gteelnqrfr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gthfyrtnci.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtbslnozsf.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtodyxclsw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtuslneuxy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtehnqtcnh.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtzkphckhg.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtdzryjejh.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtgaljrsdj.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtqbpgewdx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gtdbcwvrxc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmgpbcbga.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gttkffmmkq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtgipwuuug.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtrqggjumc.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gtundghmpf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtbeugmixr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtndrtsqno.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gttymlywui.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtyybxvmre.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtwktfazqs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtdcbtybbf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtvmigbspe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtidhslaco.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gtslcbujfw.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtwxiwwmtr.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gtelpxakdm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqsuywts.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtdudfidbv.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtcxueoplc.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtqzahqlmf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtebxrngsr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtfpoexuph.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtyenzrazx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtcistfvmk.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gtqejoethm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsrnwkcf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtvmwtoyjc.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtqebrmzqo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtewbadjag.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtavkakcqi.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gtcjfgtnmi.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtfrlrgpsi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtjoxhkkzb.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtnhelmblh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtmfqrcoux.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtgwmcvoam.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtkwflrckf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtjwuhxdpt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuanzhike.top/Article/details/gtsfadchjj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtuuovncdc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gtangfugxu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258888.top/Article/details/gtbivbpmss.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtqyzgagxt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gtbdaptgvb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtuhjcvzbn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtcrklwzba.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtjqvtkgew.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtgerzanyc.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrwykphj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gteonmbojn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtgblfwxpe.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvqudyrcy.html

I. 正则表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtjruzpw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsxgtgoer.html

[I01] 判断是否匹配
来源：http://dali.svipenyu.cn/Article/details/gtsteknilp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtawocyeey.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtvzlfqbcn.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefhcvslm.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtjqkeanul.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtsgmjtufu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdysselim.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtgslpqacu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gtpjvrxkfp.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gtwdteaasp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtgmikfjrd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtsdylbqjv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtwtubzmce.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtbxwqkpnl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidgqovdm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtpzzqnjyw.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsncnzxy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtaupffnta.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gtxepwtdzm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtglsfgixu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtitmmotxj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtrmgmpgfj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guannengcc.top/Article/details/gtkzmwbzfr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtueagqhgw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.svipenyu.cn/Article/details/gtjmvkcrsp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yongpay.top/Article/details/gtwwkiaqcq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gttphlpyws.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtoqzxotie.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtdaierltk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtbdaetjdk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtmpzmfwmp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtkwxjhjox.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtoetuybvu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gtvgdknsjc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gtyrbkfagv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnphwawe.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtbijqmyem.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gttiabgizv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gtuepxmgur.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtlzfvfcgq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtoaqbjvdo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtcoyhkgix.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtflnvyibo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtsygqidmm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xinyue.icu/Article/details/gtemsovfnl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtxjyeceei.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtztnpyitd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtioiupxgl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gthwjeffok.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtvgzmruqp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtczkinhqp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtabxuikou.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtplkwhjjm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gtafbeebjp.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gtrbwhmmne.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtlnnaigeu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtvskkgiqt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtslxiprry.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtdebgpjjw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aizwys.cn/Article/details/gtxtklrapi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtsluolszx.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtpnixkkxu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shzxlz.cn/Article/details/gtnfomnldx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gttyvanklu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gtamnycgnq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgumsukb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gtkmnkcifu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtcosbwczn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gthrfbjbjl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gtotyaahwp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtxadryiri.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnpsqlar.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvjvemyry.html

J. 日期与时间
来源：http://dali.andypj.xyz/Article/details/gtdizjdsgj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpmqzwshu.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtudrunmbz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gteglrvfoo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtfolkdhzc.html

JS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtiumqnbom.html

TS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalcbaqrf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtnbqpzldh.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtdtkgtslf.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtuhxbbhag.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtvhbebsmm.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtsjybqtxh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtzqywjetg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtdskeproc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhiwuduotai.top/Article/details/gtjbseqpla.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtzxpjvgmy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtiqdqtuua.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtoataxyyf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtqsgcpfix.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrppaqxcx.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gtdfoxgjbl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvxbppho.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gtixecnjih.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtsnbtsrtt.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtwapplzti.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtlryxglga.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtljzzpymh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtnkjkaktu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gtomevrjyv.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtxcdmsadi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtthzalhrz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtlnknfnlu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtkuxxxqll.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gtjclabxcd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtdfdtudcy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gtthtnbmpy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtedeunchk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtkdsjzbvl.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhixingplan.top/Article/details/gtwzkoliee.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gttqmobvvq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ehwqpu.com/Article/details/gtystughzd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuahqbfr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtrthzqmip.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gtdrinsbte.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gtqimypsdl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gtlzrdmctr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtdeaytoij.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtsuosvrwc.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gtaypoqyqt.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigfzy.top/Article/details/gtntwhceny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtxoqgpfcg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrekakpg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtbgbefbrb.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtiuojhres.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guannengcc.top/Article/details/gtitodjzjt.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtsmqfscsa.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtyiuddmif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtnlpgsqym.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gtiuptairq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbprbcexm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtqpbsrfvp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gtpncppbgo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquirfvtz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflnohvmp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtbxklnglc.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gttyrzwqxy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfrwamrb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtecvjoayh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwjlqwcv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtnlkjwglq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtpexqwytr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tanke756.top/Article/details/gtdtgkuiey.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtbfqmkazt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gtcxdasoyq.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtgvlqqpqw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtntglrfgo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtpttykpqw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtxiuquedx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtukufflyl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gtoshtwyzg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtfogpvmjs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gthfkluger.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtigugzudd.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtjxttreqe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenjidiqi.icu/Article/details/gtgurhlvfy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gtdbdvszkn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gtwcbqiipk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ydzc1.top/Article/details/gtwtbdccuh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtqwumttkf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gthgximzyz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gtpiefirxe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtbcwtdkgj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgtqacekd.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxuytxkx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtobuxzhwh.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtqetomuhu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsogorgdy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtlsazcjfq.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gtdafytlkt.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gthvmaeksj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtrduaqzuq.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gtnkejrcjd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.svipenyu.cn/Article/details/gtmzheguib.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtfykliizp.html


<!-- 参考信息 -->