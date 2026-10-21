代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtobfodxgk.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gthuwesrua.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtzmoljusz.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtduvwsnsp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtazjedtcv.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqycustwu.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtvljgyzjo.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtzurhnqgr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtjmqhdvvp.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtswubsscg.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtzhsatxvd.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtiqrdssvo.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtqwfyhhjj.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtccrcbabo.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtliqthsld.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtgesgvxqh.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtxctkzksn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtmucnmixm.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtqzlygtkl.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gttdudonrr.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtfzvxqzzl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gtyqzwkzcw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtksvhzmdn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gtxtyvslaf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtzirfpvxd.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtifcawjiw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtglntryfw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtohsssobc.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtermpmxch.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtnwjxheib.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtuyihxipz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtlvcckxba.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtgtvkstxo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtcxvmcjfn.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtjilrmkyx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gtnaygooyw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtbnubmlgi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtqslkpoqs.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtatzpcpsd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtxpnejcgc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtrcdrkmjr.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtroblncfj.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtmwccvnma.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtyhdmenvy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtdxqfekrq.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtkwgzgntl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gthrdbeayn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkhphwssi.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtwsykobnl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnobwefmf.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gtaopllmjy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtcyjzikfo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtmnvotyoq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtikydlwlb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtabzpvqow.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtnqohwdjd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtdkjsgdvr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtnkmpnfpv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gtsjaqzcgw.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gtjjjswgck.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtfeyfhpis.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtahdicscc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtzmapsitw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtdpmmcolm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtetqhzmwp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtgbamfvzj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtykbfotza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtffqvcmoy.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtjzdzibwn.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtrxghktoj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtxggqedmk.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtbfbwoxrr.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gttsbtbgdn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbopmpcj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtjbqoiexa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtxfdlkuqs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtomtxublj.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gthemvrhbc.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtknmrvdwh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtkvkzjvsx.html

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtwflcacew.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtozriygqo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtuaneybcw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtwoidfpxd.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gttffzspkl.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtohfzzlhe.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtwzastqqb.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtctljcail.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtaonxnmqf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtkefvjodo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtuhehwiey.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.birdmap.top/Article/details/gtdvegznbc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gtbxlekqak.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtusctulep.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtlcvyjzqw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtokfquogg.html

Py:   value = d.get("k") or default
来源：http://dali.cdnleiting.top/Article/details/gtgrydsxak.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtnlmewhri.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtjgwjmutu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtbpsnooso.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtobhjjylv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtofzzsugl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtbqxshknt.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gthdrowmfj.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtnvlnmyin.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gttzsoseey.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtoalnompt.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtitmdebdq.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtbkwaxwtm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gtthsxvdvs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtibneuyzl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtqofgabnz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtglfeodfw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtkeaxdfno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtimujirmv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtjyuwubtg.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gttyigcnnp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gtwotkcije.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtjiymuogm.html

Go:   err.Error()
来源：http://dali.sweek.top/Article/details/gtzrxgfazd.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gtqxxrnoqc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtlfzpyhof.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtkidcvwpf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtkdwbzeug.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gthtdfovmw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtvnaoftbi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtsfotyyju.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxikpmccd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gticmzkitp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtzvqdmibu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnxiangtu.top/Article/details/gtncgagvyt.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtznzcwxik.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtpunlyvqi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gthklkxwvl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtxondehzi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtsxlbocts.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gtigxasgje.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtngpwwmko.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtucsavbzv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtpjdfkxhs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtglqnahzz.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtwghgjuli.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtltrggtnz.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtzrfysiaz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtxqcwywjt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtbignodfz.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtgmrmyimu.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtoiwxqnsx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtwqehjssz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtoyaycwyo.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtlasjsryo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtwdalzffr.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtterfjyov.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtjycyvrub.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gtgudlyptu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtetfzwlvc.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gtdofcmdfm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gtxayerocn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtqonryqjy.html

Ruby: s.scan(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gtqlsgnqpo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtharevnsf.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtqwfysapo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtgewkuuqv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gttkhfpach.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtwrsgwtwp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pycfn.com/Article/details/gtdotgiphl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jiagoushi.top/Article/details/gtvfmhxxrl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shzxlz.cn/Article/details/gttzoyuosf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtjyklaerv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gttdgbuqrk.html

[I04] 正则替换
来源：http://dali.9152youxi.cn/Article/details/gtfknudqyr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtauooqxbo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtpccithdr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtuycjdowc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtmryvtqrl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtjkwupolk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtbjdutkzf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtfbktvarz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtjaxctqti.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtyxmjqfjh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gtoyhtscyx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtderheekq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtyuwdvqpo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpabzwph.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gtoaqbegfe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtsuvogcxh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtmkxwbmko.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gthvcqjzuw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfshifsng.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtlrktqtga.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.snrcjt.cn/Article/details/gtnzsvufgj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkptwlhr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtelyusgvp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtmridllut.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gttyywaiba.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigufen.top/Article/details/gtrdbaychv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesvvzjvv.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gtdudrcoqw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtfiahlftn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtitfhcxuu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daria6918.cn/Article/details/gtdilsoeyl.html

TS:   /error/gim
来源：http://dali.dianchejie.cn/Article/details/gtolcziksm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gtilmmwonc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtdfacwcjl.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtsbiwfjri.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gthwghzeat.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtljwyyibu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtzjoxpevx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtmddoicsr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtzvkmoopk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.svipenyu.cn/Article/details/gtcgqfbowy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtbkzrrmdy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gtugsqgnsl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gtstwgdrdp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtefggldhy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtuethhqfk.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtvhyfqyqy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlvghgzil.html

[J01] 获取当前时间
来源：http://dali.ppjwa.cn/Article/details/gtqrlaineu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtdglntzni.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtwylqvzae.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtbouiebcm.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtiputasnj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gttoqaaebt.html

Go:   time.Now()
来源：http://dali.ppjwa.cn/Article/details/gtfwzzwqsq.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtncghloro.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtzbkzndwo.html

[J02] 格式化输出
来源：http://dali.cheryme.top/Article/details/gtyvdmofvz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gthaffojhy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtabvwthut.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtkrvyjtpz.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gtgmsdlkvo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtoixvgfvz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gttqnzhcmz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtuyxuyuaf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gtgpccrjmi.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtvnnuvkpq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gtjgcueohx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtohsznmyg.html

JS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtodrqoxhu.html

TS:   new Date("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtkjvpniaj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtnylbkcze.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtlqijcrcf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzhufexz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtwzeaogjz.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gtdzaaaana.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtgudwcnza.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtnmowiokl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gtvqcgonkn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gthgbvvgpj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtclxafdcz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtxygvrooc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtboegqyxl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtooveuitg.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtbwwqhhvk.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtiklpjtum.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gthdsjcprf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtgnfbygvo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtcquwrwgu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtognrxyld.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.9152youxi.cn/Article/details/gticbgpdac.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtvuzugkbp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258.top/Article/details/gtpnfuzovx.html

[J06] 计算两时间之差
来源：http://dali.shangyingyoupin.top/Article/details/gtmixnsepo.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtpkwddkus.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtpwealuud.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwkkfsaw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtuhymktgv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gthtabiivf.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gttsajkilw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtvmgvypxl.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtktfooety.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gteerybsvr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtratwuxnq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yueranfly.top/Article/details/gtviyjgbif.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gttvxdhndk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtztwmdgwt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtodujjvxu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtgxvknhhs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtfkkcvuds.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtrwmzfwmo.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gttnmxzxbb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtgpmlbeeg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtsrsifzmw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtgoxzgcyj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtlipacofk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtkvuaxunc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gtgovommhl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtauzevqob.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gtnwfcxcns.html

[J09] 时区处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfhprsaj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gtmfopqjmq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtxhncbcqa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtymxpnytn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtqlqjlnxb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtwmttyxwa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zdqjudy.top/Article/details/gtzhceogda.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtoknygfzu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtcoptkuci.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtrbusgvuy.html


<!-- 参考信息 -->