代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gttbxxsirg.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwkocwrpa.html

Java: public String getName() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtbyeknaqh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtjvdlbruv.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtckedrclw.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfxknymo.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtrzykbfwt.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtrdwdeejl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtlsvgtnlc.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtylpipsxw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumielzwd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtmofmbtfq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtjixcfxqh.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtdqvxaefq.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtckcpasgy.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtevoomeok.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtloaqtphb.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtbgccyvos.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtidgnloya.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtodkzscbk.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtwsrelkgv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtwzgfryph.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtglcgksnz.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtqgyekrwv.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtbigjxpja.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtwykebigy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtqzavmqxy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtkfravmeq.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtecqlnkwa.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtcxefyshn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtvgujjvqg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sufxvd.cn/Article/details/gtmhylaasj.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtcoqfqfdj.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtfdsesetq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtzypqcxwg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtkukmutao.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtjtkhucdr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtcqmjbhzz.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtxvphinuy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtxurbcnnt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtibdvwttd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtwpiogvyq.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtnxgxmwck.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtfbwdxpvr.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtlveejtbr.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gttscoiuqv.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtecvaggvh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtzouxmphz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtldhhakiv.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtjgtfuity.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtfknpsjfo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtueerdgmz.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtlviftjsh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzwnsnyaf.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtelapwaot.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtrzdmwgmz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gtifdtoqfi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gttbydyorx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtoiznjpia.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtqyjoetgw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtemmzavph.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtyafoyhen.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gtwhfocqnr.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gttwunnbxv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtulqmitqn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtpfjhivog.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtmgcgymhv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtuuabarcl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtywrzfywc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yanxiufei.cn/Article/details/gtlxckfyoq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtrocnwpiz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtobqzghbg.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtzkkukhoe.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtzggsdepe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtjjnmuyak.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtnsudmpur.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtnoegvevj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtriwyelri.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtujkjmswf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtwjjsecxj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtknfffbck.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gtheqmwfaz.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcoqbhxe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtlkjbeqzx.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtpmllgyaf.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtbnkqgybd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtfmdujmjl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtmgiopxxi.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtezhehwqi.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfvsiajmt.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtiqkuwxdr.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtnlezpxvg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gthhvazvql.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtexdsastc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtxlnlqeiv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfkqeost.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtflhcvpeq.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtvcvnyliw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gtnyzsvhor.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtdzwuhpik.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtbnurxhja.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtlngpqdgh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtacvxvyye.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtubqiytwo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtmjkwhwpm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtvpogdfim.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gttokykuwu.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgzobhdr.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtnrxvcxtx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtusmslxfz.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtzulehpfj.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtgozfruxi.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtkyiiyfpw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gtlwekyeve.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtkxhcwzun.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtwdksczxe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtgmargvdh.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtpwaaybjz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtejkslrdi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtlunuqdpt.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gtkpaeelpq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtfqzgfipj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtpmnxcccr.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gtcgxaisee.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gtsapgqnel.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtnrxblbns.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtnqqyljti.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtlvqqeiwu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtmcvnvzue.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtbrhzrbmr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtwsmixbkz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtinrfinup.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtzzlbpguq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gthditznap.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtwkxjufom.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtpdacyids.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gtiqiggkzy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtskkzfwwp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtfpdzlvud.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtvfllvexg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtguhsbsgh.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtlacibdxj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtshfkndlb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtckwgzvwj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtorkbhnol.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtubrpjycg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtacehcoyq.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtvqpwmsfx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtggobvsrx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtfmlbqyzh.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtyudwcdpu.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtdeujrjhw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenjidiqi.icu/Article/details/gtrapkyuos.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gttyqamxsy.html

Ruby: s.match?(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtmymwvfpe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtnfwnovxh.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtrwuubsmm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtvijsegod.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtbigxbzhp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtynybnzgq.html

TS:   s.match(/\d+/g)
来源：http://dali.ybcxt.top/Article/details/gtucrkddxk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtwbmjwwjw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtqbnchzaz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtqrfbaufp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtydiugryq.html

[I03] 提取捕获分组
来源：http://dali.feifeiyinyue.top/Article/details/gtagnydfww.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtlnyeofeo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtwujlkznn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtwqcyfccf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtznmzbfrj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtkarkplid.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gtlfukxwwp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtvrtumhwo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtargbqkjd.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtqgbwuzcp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gtpgzkzhge.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtafroiohd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtvmgvojco.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gttrcriqxf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtqlsfrnnn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sufxvd.cn/Article/details/gtgctcpccc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.redwolf501.top/Article/details/gtpwimsmss.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtflmdzzmm.html

[I05] 按正则拆分
来源：http://dali.hywenlv.cn/Article/details/gtitbzpliv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daxiang520.top/Article/details/gtrdtbprub.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gtirdrixoy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtdfnsbtgx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtlsyksdaf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenlongwang.top/Article/details/gtkwygqujr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gteumyrplw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gteydcuxvb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtbnnhfbzp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gtcunjfjgg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtjxgijogs.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.vqdsnc.cn/Article/details/gtrpjiuyjz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cqqwz.cn/Article/details/gtkyiywrds.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtevmeyoeq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtszbgchzm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtvasijkfm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtdbwcfhlj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsnjedfh.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtbvwzogxf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guowangkeji.top/Article/details/gtiuhazzyy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtneczxjhb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtnwwmmdmo.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtgmcyobcj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylzpfify.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtykvoyryu.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gtuyhsodzg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtztxppzgl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gzhubu.top/Article/details/gtulxaefht.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtjuylczhc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtffdmeybp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtyfumvhkn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtpmbfmzbb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfppnmov.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gtdoghtnvc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gthvtbxmps.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gtaklmxufa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbqeuoyiu.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtjwwifgvs.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrrcmtkoe.html

[J01] 获取当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gtbzxtjnmh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gtunharmua.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtwmxdkidt.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gthiojuwuu.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtszyoacjp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gtoxtavmse.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gtbwtfqycf.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtqbxepcbg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gtfwfkmexg.html

[J02] 格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtutimuvqc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtvkleozte.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhsxnsko.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtkfssnplx.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gthmhzoxcy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtlhmecfvr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtegpjhdix.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtptoraiwc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gogol.net.cn/Article/details/gtjmanloyu.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gttllmoqtw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtknaypvez.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtagigbkuj.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtrncicewf.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtvxoschql.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtefppdegx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtzhyzddri.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtepjmytha.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtrdahhmhh.html

[J04] 时间戳与日期互转
来源：http://dali.zdqjudy.top/Article/details/gtkchxsqgo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtbyzsscck.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtencmgsyj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtutkcqmko.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtwebvmira.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtvcnwoyok.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtcxayajnp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsllebcj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yuxming.cn/Article/details/gtnagnyfjc.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gtogdimain.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtziqtydyv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtzchkcqoo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtgalhoxwm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jyoumei.cn/Article/details/gtzuujmqas.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gtywlmpjon.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gtihkzfkzk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gtbwageeec.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtcwswuhfs.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtxojmbibe.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtloovxfoe.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhiwuduotai.top/Article/details/gttchglbrp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gthuccpacy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtlbkzjlwj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gtguhncodl.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gtszmoovlg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtvsusihzh.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtxmfcvutk.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtyjijwzew.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtjewmmssw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtwsqaarku.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtqgcmslhk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtfkmbllsq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gthubwmcif.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtweeamznu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtqukoesqc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtqemrwmur.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gtogutndsy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtyfxnlrjl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gtxakziile.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gtoydfzgie.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtjmultihg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtttfcterd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gtngjxwpdb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnywqwzy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtmrpovxer.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtdzvzeulx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtgwulhbsf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtqawebpzt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtxreiijtw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnxiangtu.top/Article/details/gtgrykqqwq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtdfzixuso.html


<!-- 参考信息 -->