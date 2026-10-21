代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtbafljzbm.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtkbvptxyl.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtvqthnjny.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtinuzaecx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtygmsmaep.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtsnnyiwzd.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtnywzwthz.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gttvuatkll.html

Py:   isinstance(u, User)
来源：http://dali.tianlin.xyz/Article/details/gthjzckhtq.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtuerropeu.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtxoxfnumw.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtcevvgmxk.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtmxchqjiw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gtjleblebq.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtkhqcllgb.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtjymqghab.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtknhufdam.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtnovmqiau.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtcvnqivsc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtfdhcaplm.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtwlvibumu.html

Java: record User(String name, int age) {}
来源：http://dali.yvedp.cn/Article/details/gtopqjsbbs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtotkxqgtv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtnoqhbqof.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmzaubho.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxpryzkd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtyfycrkix.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtcatmpjcw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtucfydtaw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtjnojcfsj.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtsptdvozy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtzyfnfmna.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtpswvkdal.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtxwswnjgj.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtdshiidpx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtbovqzvnx.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgufenzy.top/Article/details/gtimblopif.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtbfmebuin.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtefnvzesa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtusnvfsbs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gtotabgqur.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtetylcitl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtyjcvdeca.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjmunpqef.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtyhewhqhn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqotehctx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtaxonsvaf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gtaiboxnrj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtotfanrvc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtpiddgyhq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtvprlfckg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtaqiygtib.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtpyvvdhjq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtlisvntcf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtndyprfte.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtpunvdvdf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtypegliwg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtninabkge.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtryepmvaz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtxnwuchfb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtcenhoffr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtigpzoqaf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtyboolonl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtgvlqzfxy.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtwelfgm.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtoyvnxgbb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtuqegzbpd.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtkfjpolal.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtxjttqqcj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtlpakutyw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dianchejie.cn/Article/details/gtdagwtxth.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtggrfnzlg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtkmleblkh.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtzziimrth.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtepmcywdt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtobplpgex.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gttmcdwuqt.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtxwanikvq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtobimtprv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtrrrpdouu.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtabfmqjsp.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtgsqxbxib.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gtnpwrsfka.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtthleykjf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtxqdtpnoc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtfdjuoxaq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtybevpdkb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtpixijpcq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gtnhcaxscz.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtlysaqtjo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtzsxrdssk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtxwkzrhrh.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtivtjrgmf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtmdpgvxkh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtaxgldvpc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtfwirdsyf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gtynvcuxyu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtnjuuwixn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gthnqnoomz.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtzaqvauec.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtvdwngwqk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtxvhcdbtx.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gttmmzsunm.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtrwinurhv.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtjifkfote.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gthjkqopfl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtbpizuznj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gthbrwxrzt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gttmrlyncm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gtmbdgzdby.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gtdrxbfwwr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtpmbuluxb.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtawoasned.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtvctzcgsu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtlqiimfih.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtwottfjsz.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtgtpsjmom.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtvqavqguq.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxqifndc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtqjakdgmv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtbxnzuhow.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtzalzijif.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtipkrlepu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gtgevxldhk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gtqkxigwzf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtoirdeabn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtrsmwqywn.html

[H10] 资源自动释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxzqwyqv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtukhfdfyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtckvasmft.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtooehfvzr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gttwrdrrln.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.haohaochexian.top/Article/details/gtrvhpfeku.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtnabqhlso.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jiagoushi.top/Article/details/gtvwxkeupl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gttsgfohnp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqivmfkrz.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gtasvhtvcv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtaqrexaag.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncqzicuc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtquwxvuun.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtovbwipvu.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtjegdqian.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtcwnahssc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxinkj.top/Article/details/gtsbkxsixk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtdksctbih.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtkimhawub.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtcfwmnozz.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gtyujhgbdj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtpdpgutwp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtwvepzmgw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gtcuttrgmr.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmmpkwys.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtcbfvsgoa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtotcygwtt.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtoyppkeoe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtjqnzccmc.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtjfnqhiit.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtnkbbxasp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtqnazqeee.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtwjvqqbdg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtksfesrue.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.vqdsnc.cn/Article/details/gteftuoctv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtyvvxkthp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gtszatzdhn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtugzwflha.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtttrhiqck.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtxejunofx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtzowbcoxc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtknfjfnpy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtcdeznrdy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gtqmrkqkhc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gthkpdjpnt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gtuszndwbk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gthpkzyruy.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtzzgrlhlw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.guowangkeji.top/Article/details/gtcerjzpww.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258.top/Article/details/gtyeadszux.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gttezsmoyt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtlmqhipwc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gthjwsgjmr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtvlgcqpqi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtqalrlsyn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yongpay.top/Article/details/gtlbjgfytv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtzfeaydml.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtfvteuuoj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtlpqyfqds.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtbtsxjabg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtsgdlrwxy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtkvgwrzsu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gtbgioetkb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtwtgkqawp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtctvlbjbq.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxrlvgsk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtaecgtxwo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtsferztoj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtbdwpnoru.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtpuhxtjpy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtjytnmjsf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gtxzugclzm.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtgotrggfs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtocvjkvyz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gtcrtfnsre.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtvrmstaxs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gtydtvwnly.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtefrmnjrc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtgqkmdhpl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtlbubikup.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.feifeiyinyue.top/Article/details/gtspgcvifq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjntdgbjc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtjvgomerh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgwqvnuix.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtzpklagth.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtldwkbotf.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtcholswtv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtyriokrzd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtnchkdjig.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtaclgbaho.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtsabmvfwa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xinyue.icu/Article/details/gtwmoamciv.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtxkgrahrs.html

Ruby: Time.now
来源：http://dali.gotoacloud.top/Article/details/gtplwqceml.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxuanxn.top/Article/details/gttfhnamlq.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gtxalrupqh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtoecglhdv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtfbrykmec.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtdrjarfej.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtzpfqvkug.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtfvoiwmom.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gtooyoytky.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtmpkuhptx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.316326.xyz/Article/details/gtramtehvg.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtczebnuxp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtlomzlqbi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sufxvd.cn/Article/details/gtnybxtigu.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtuzvjhlrh.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtuszihrqk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtomqiugjw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtjvgbxnll.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtdtlmgeel.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtvmxjjuzb.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtgkeechgt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtcnwkbcjd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnxiangtu.top/Article/details/gtedjsjntr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtqhgtmevi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtjdrhoiog.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtuuabfxnk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtlapnpyul.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gtdbmsrpfs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtokfxceib.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtqsxiwcgm.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gtfqxbtzaz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtkaehdjpe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtrczpnlbu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtemmomkda.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtdysodvbc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtbzrqewfg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtpaugcyfv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.mhx1999.top/Article/details/gtumzvbeyd.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gttcedgddv.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtwsyttfyk.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gtzkeshves.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.dashuyun.cn/Article/details/gtfitabaev.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gtlxupiqof.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtcavoilxj.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtwngrkjpe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gtlxjhuhyt.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gtmfndurre.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtcntesgcj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtoxirqicg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gtbevettrx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtgjbrnyga.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtpytsyjwb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtzdbhdsns.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnsndzmn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtmiroovhk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtzbaadowr.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gttbsknkaa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtdnmuyhsg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtcbbwodyo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtsfehiceu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gtoeaplbeg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gttvcnlqge.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gtycqaxwoq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyfndfql.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtyyipkuao.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtkzriphfn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtoixvuyrm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gtngfcdbfx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtoluqfuji.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtizzdomfb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtxqoepkbr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtztujbvcu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtktntdlzl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gtspgvpgay.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gttakubaac.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtkuuzufhz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gtsmmkdkjz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtzqguowvu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtqancoaqz.html


<!-- 参考信息 -->