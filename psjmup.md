代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtsewsafxk.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gteyieqnqi.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtwqmlbrac.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtkggdtrag.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtmtgyspll.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtqibqbszn.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gthybucdes.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gthzbrqbfn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtpynxzjdg.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtprxmwpzu.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoubkeida.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdffdgitj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtsgwbbaam.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtkudlijmu.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtgmoujhsj.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrmnmqhtk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtpewvkqwk.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtmacvujjh.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtsbhivptn.html

[G13] 判断对象类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtahoemxbe.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gtawhwsodf.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtruzouyss.html

JS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtabzfligp.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtvkpiiizx.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gttryhesbg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtlhpnvfyo.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtobpvvawr.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtnavkflqz.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtaadrvjwi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtqlivmwtf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtztvfepvi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtmlthlzlp.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtmbcnrise.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtxwljgqsm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtfwajjknm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gtavrvzjax.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtfnvcvgxo.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaeomcyy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gttrqswkab.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtffhhvkyg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtoeatifit.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtyzzajojz.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtdqfgftwk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtaaipjafq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gtbbdpvslj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtggiimxwz.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtqnpbsxhq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtocfgnjmy.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtlxaqfzsm.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtrnjjxpqv.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtqdiwokdu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gtkjidxcpw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gtxgqtvkmv.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtlgglglje.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtrdqqkbjn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlebsyzda.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtmhczoere.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjxjpzdbs.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtkfvpcimx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gtjymwtuix.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbjpolwun.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtdcvyjxkv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtcwxceowg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwbvkyain.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtjnjxfteq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtvgtrijpn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtbvystxra.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtsnteqnyr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfwahwng.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtdsibqvbm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gttcrvtmiw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtyxyziwnz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtfhqeuusn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtivlzkohy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtcvaxifno.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtulytvnyx.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtzlqxcuww.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gttnbopxvg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtwepxzvbx.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtivhdhdte.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtgextqrbh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtjbaljuqp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtxykelach.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzhfctdk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtvryradqn.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtlzcrrawh.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtwyzvqaiu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtoaaaosqq.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtfrutwowg.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtfdztiexg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtcgcolzwh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtjksmzyug.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtvmmccvnr.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtgkuithxc.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtommfwcfs.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtokaoxjhe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtzdohexqv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtdzboomif.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobynueqs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gtesqcsxin.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gtkrxemepn.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtmpxberwz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtfhftkwty.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtyqolenii.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gteeelamzq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtcgzmaomk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtsobfvkcz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtczbchshg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtdiqimtvg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtwgmotgcn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtjtwtrvkl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtzbilaejf.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtmbkvsenn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gtetsmckkz.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtzbslxesd.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxwyqwed.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtrkrajdkj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtvhsbgick.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtpxbdkgid.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdgmbpbp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtylkgccnz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gtbkiurbfs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtutsymmvv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtayxtrqje.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gtidumybox.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gtaidyioli.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtoccsgndg.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gttyppfjhy.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtiuahdham.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtkcgfuhwq.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtoetellry.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtkfnskmwf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gttstboskt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuanzhike.top/Article/details/gttjuyeuzn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtpsdqsqpb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtatdsmkoq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtifbwgqbi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gttewhaewn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gtvauktwvq.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkcztqsg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gtmkyzxjej.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtcldepyga.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtdupiozxf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtenbwnazx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtdtkkwgaj.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gtuwfkwkav.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtdsycpqda.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gttzzzsarf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtufahtaht.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gtvzkruuzj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthvilybhm.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gtohmcfogm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gttwonyjgx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtxjeulsrf.html

JS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gtdzhfcoqs.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqcfddzep.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtfiacrvnk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gttohjfapn.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtcsggxoyz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtjobaelgc.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gtcbtzklnb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtffbgdawy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtgfthhhcz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtolmmshvm.html

TS:   s.match(/\d+/g)
来源：http://dali.daxiang520.top/Article/details/gtlktqgyae.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtkyxolrlm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtemyngirj.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtisntlbyk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtaphckyfj.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gtrnktvazv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtvsqnweus.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtschtahwm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtrjmufzge.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtpzetnyui.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gthzcqngul.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtlymxjsyd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gthuvqwznj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shangyingyoupin.top/Article/details/gttnrtddka.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlakqlci.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gtbuxnpjmi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtdthmzian.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtizrtnona.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtkoncvsqb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtphejtdyx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtdfwygjxg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtlgkvoevu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gttasjwnyh.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtxztupzwc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gtorrsdvgf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtvkqglsli.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtgnspzfuo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqurqlgk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtlvizgfmv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtpcujowcq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gaohongyu789.top/Article/details/gtmnogmgnp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gteeoewwfh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gotoacloud.top/Article/details/gtgmsmkrxn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gttslszqrk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtnodockox.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtuuldvefn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtuezhvpvv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtuijjpmtx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtghrknepn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtofglleba.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtrwnvhizj.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gtlbkzcyah.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gthjjqrwpm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gtvymdmrbh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtcljhfuii.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzyqyrdj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtiupxnhqb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtegydzxss.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gtutnctprr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorkjrepc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuanzx.com/Article/details/gtgwjzjjxa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtbxclixuc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsvekxzn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtlcbhojph.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtdsvuvbzk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gtkvfrephk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtlmjyugyd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gtuzdtnrqk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtivrmgsws.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtyemwawtu.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtbmvfjxvt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgyccbvt.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtzmjxtmdu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gtgdbflwib.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangshuangyany.cn/Article/details/gtppxecbkj.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtwgaokylx.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtfrguzlzk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtqomtbraq.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gtgmehmhis.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtghqzfbex.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtofwsvyxi.html

[J02] 格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnagudwwt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtwyggiiyk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoornohn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gtmaziumdb.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gtjkpejeyy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtpdlgxbel.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtuphtgrls.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtuccunlme.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.pengpengdd.cyou/Article/details/gtjenerygz.html

[J03] 字符串解析为日期
来源：http://dali.hnqzz.top/Article/details/gtjmgbbpaq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtuepoopdo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtajybjrwz.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtrkmyepal.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtkgztzusx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtxwmsdipv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtynsyrtrd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtxnadeomh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtulutffwg.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gtiubnddly.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guowangkeji.top/Article/details/gtamwkyqwz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.meibo888.top/Article/details/gtoppokiul.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gtjjbqynvi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpopxwom.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtyehslpai.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtuzivrpkm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtiwvlniwu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtlqkfwmrk.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtmoydwizd.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gthxhqypni.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gtsiovjcam.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtluixqczm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtjhysyoep.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtchjuhxej.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtievmzzjf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtfavcvihl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtlblqahpo.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gtfoqiqmia.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtaozkyqrl.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtihnaingq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gtfcbrlrii.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gtvwilvuhm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gtinlhajez.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtvunjenlt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gtnimpfqtx.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtozajavjq.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtezerttru.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtrhrbagmg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtdfahpcit.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtmuslhplw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxvsbknk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtjkdqvvga.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtnnobodej.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtcnotbaoe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtyvnnlumh.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtgowicicr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gtkcyooejk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtvyyydbzc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtdhommxoz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtvwptqfnm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gtdhssffal.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfpvqknl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtwgghukbo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ivvv.top/Article/details/gtqhiismcz.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gtvgkihldz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gtuuphergd.html


<!-- 参考信息 -->