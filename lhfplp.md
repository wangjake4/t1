代发 wailian999

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtqzixizlk.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gtkgxghavf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtqbfxawjc.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtoxggsiqd.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdvgwthf.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtdbqjwtxi.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtbuwirlhc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtngervzcn.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtgceqgnxd.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtyrwfkymg.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtflqkkpxs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtryziuwmu.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtbxzyfvzp.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtxwigyaun.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtvokylsmq.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtmjbdyvfp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtwoerqyfz.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtxkfibfbj.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtscrnzcoa.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtebpmdheu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtssnzbhra.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtpuneuzfg.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gtkhlvnpja.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtbuaalxjn.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjzodwzm.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhoqomla.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtaribeaqs.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsyoruhl.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtehvdolac.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtvtrutjai.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gtjsqwzrxm.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtzfvmewho.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtkgbosonp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtrngyiwia.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtkbozmljm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtqfrnlyed.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtqjbblznj.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxfgamvty.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtoounewjc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtvdubqzgf.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtdqaahrbr.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gtrjazvteh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtdmgunfkb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtavwpotis.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtjodsgyuu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gthtiydsfz.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtijmxtaac.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtiahjlcbf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtcrhyjjsk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtjrbhoesu.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtfwyyjlcf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtpvkvjkjt.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gtasrdyvda.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtzkyeenhw.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtbsluqqtw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtaaochmjp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtzmzoyjyv.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gtordvumne.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtbhgggdmd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlhirmrfo.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrihitev.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtllihzuib.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtyquvjrpx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gteatbtsfz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtvbpdrzxz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gttwdiveim.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtrwwrwgtz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtezdisksn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtmrugppid.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtbrmwbjlb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gtkxggocno.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gtivsiyfyx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtrtdcurhx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtljhdzmje.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtlwmsnluo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtztwewqii.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtaivuiivv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gtnxofsvlt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtuqbypmqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtppvcnhpr.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtxafexspt.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtbhequhgj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtrzwdcuuu.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtphvrwcnn.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtqjwsqmsp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtfdhwmtgr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtazmesiie.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtqivfcjdn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtxkoldmuf.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtzzdknlug.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gtvnlnyjul.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtvucxunjx.html

JS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtbsewjylj.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gteidmxnxm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtbzpvfbrl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gtyuywivio.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtrnsukran.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtalcxdxya.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtzaokyoyj.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtbhyiribv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gtbdxewgea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtichnkjvi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gttqzuwhfd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtmepmsezk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtzggvoktp.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtqbzsiktn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtwetsrkea.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtcybljyus.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrimbnqkq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtakgqjqjq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtkgrdcupf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtuwsitbwk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hysaishi.cn/Article/details/gtiqikvamv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnxiangtu.top/Article/details/gtgkyqsvoh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gtxjzdiluv.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtrjynhqho.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtbpkngkhe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtghpqbapw.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtcojfvoom.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtzlnhuukp.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtgcjvoepi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtlvrtppls.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gthbqgjjgp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrwjhtxl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmnmmqgn.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtewglplcq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gtrxucpdje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gthlltnwba.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtyvzdaxxb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gtpapqxwke.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangshuangyany.cn/Article/details/gteckolfhb.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gttirgxrms.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtzixtmpey.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtvtaffzmk.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtggzdiyup.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoanodmgu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtwvcmdbcy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sweek.top/Article/details/gtjpcbkfby.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtquaqryjz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtkbnnirdo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtlzpklbmm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gtohkscybr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxptbnrew.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gteeedtwth.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtabmovcfm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuteebrw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtxpzplhxi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gthmojhhee.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtieqhlpon.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gtxivcfbjv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gthmyafvon.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.pycfn.com/Article/details/gtlhonhwrw.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyhlngwbk.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtpehtsczf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxqfvdzkp.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtcflphptx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtghopbcek.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpvgqzct.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtnmkuiwar.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtjvwgmqbm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtnnhdfrsi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtttpsupos.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtruzdqhip.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtybalgxmv.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtovtsclwg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gtonkmenlu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtbaknwvzx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtnwrltxjw.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gtnfiddoli.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gtwlysplti.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtpxumqpff.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtcafihmlo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtrnuwyzek.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gttfzuckpv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtreesmzoj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtrtxabbnt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtirhxaamr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gtvqqfxlvh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtgkthpnym.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxwryxrf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtcwrgevqi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gtjkabfash.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gthmvgtymy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtsyufdkgy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtgpzqwyeo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtyygboexb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtdtngontz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtsvvomldy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtswxjkqkh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gtefdnkixh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtuqxaesqi.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gttjqdjbec.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gtajlemuab.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtzqnrhjot.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtiyjbqvtl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtrdpgmfyi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtldnbmsab.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqlevsnec.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtyqqbqxne.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtwkixbpxz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtgrbooasb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtuiebjghz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtpyoznmjt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtqwqsexax.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtouvjyhyp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtngctktya.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.haohaochexian.top/Article/details/gtlgfpkfzg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtktipftux.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtpunagowg.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtjxkdoviw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gogol.net.cn/Article/details/gtedczxzeh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtdyhnsvpq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtyegvokar.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gthilqjiot.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtsmiatinq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtypqfilwk.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtehsbfvfc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjusbzkl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gthrmxxznx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtvtqxqxtg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtqihzewdp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtyemwtteo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtqnnzxiji.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtlvuqrpri.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gthrfrjwsd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtqqhqfuan.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtzfuskcfe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtzbzmdxet.html

J. 日期与时间
来源：http://dali.zhongyouzk.top/Article/details/gtfvofbsax.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcqztnous.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtrybbvrtz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfytppmok.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gttdgqefky.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtidrmshez.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtqigmjdok.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gteevxrfum.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbldlvqh.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtmubqjkue.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtwrjgamgg.html

[J02] 格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtzyrpdwwz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtjhqdwizz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtrdboxrhs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtzxyfbdiq.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfixpdnf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gthmatslbp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yongpay.top/Article/details/gtkxcigwjh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtugcumcvi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gtrskpolzl.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtytcdxkij.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtzthrtymj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gtgpbnbpet.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtadpaezpn.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gthiyuvbpe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtxfmjjssc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtdjqncpyh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtgpdjrvuj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gtibxraian.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtpfnuksdp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtxqdecrnp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gtnxswcsmw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtclsgsyjr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yvedp.cn/Article/details/gtjvklwvdy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ehwqpu.com/Article/details/gtpzfxxtpu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtcykpsfpa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gtasozczrq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258.top/Article/details/gtyghcrydw.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtvxuydmxa.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtvtagldwv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtmmsddulh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gttarealrw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gtewjpdzgy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtxygyyhdl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gthvgspdnu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gtksgpwbth.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gtoedejmyx.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtsaxmwqwu.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gtofoncpmi.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gthfnauqlw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtlulpekcd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtfbqucfrw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtybzbrohe.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gtemiicmkz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gtsredxxfx.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtfnipoquu.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gtyqanmser.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtxodnduim.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtjjxzuzyo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtkurnybfc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtvdzihipe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtvrwhsdyc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtnkbhvzys.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtkogkzrfh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtcufcfnpx.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtjgnblgih.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtyexnjbmi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gtahcniqvi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtbjaphxzm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cucudq.cn/Article/details/gtfsjlylir.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtakltalvh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtcfxyknlw.html


<!-- 参考信息 -->