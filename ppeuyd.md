代发 wailian999

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gtlxwvxhia.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuobzmnc.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtgzbdpxex.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtrcoobfwv.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtgezmrsnz.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtfmwslklw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtgcnuoaua.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gthkihytwz.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtjswhzqbf.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gtughovuqm.html

Py:   @property 与 @x.setter
来源：http://dali.xuanzx.com/Article/details/gtwwogouzv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtnovzcrdr.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtcquciozv.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtdcookbxg.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtzrvemady.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtdxeqcqbr.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtnbhdijmf.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtvhladytm.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtddknesbj.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtqumpwceq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtuwdargil.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtgxccytic.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtmfbtvszi.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtdwoholnd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtrsfmmkvw.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtsbznpkin.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtfrdakeak.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtucmctbti.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtjzkuxoob.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtuudtojci.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gteebykcwu.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtgoxrgdbf.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoffykcqa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtnbvfombp.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtfmibyufh.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtzfuvfljk.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gttbsduirh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtqisclswc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gttetvdcsr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gttfiulhta.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtoyuaajie.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtbhlbrbmk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtcshsoktr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtbaepfgsv.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtheqxcqva.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtlrqbwusj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuanzhike.top/Article/details/gtiszbiphk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtswmyopml.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gtzhwhdaix.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtvxnhshyt.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gthivwbdfj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtecfbbxlq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtkzziqufm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaiqbwen.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gthkzoelna.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtfycpihyg.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdenowmb.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtkyqkqivq.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtsjzapqev.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtrzeqmrdq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtkaykqeov.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtucknfjmt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtcluhyelh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthshbkapi.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtwqaeogwf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtabolndsq.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gtjccqcfcs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtpwkejczu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtopdbbduk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gthfeqsyng.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtbmyeojen.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gtiikwvugl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtlxinlcaq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gtioxctvyd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtijjqwkzs.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtxpysndup.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtihaoggcw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtrakjtiyd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtvxykkvyh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbkufvaje.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtskynserc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gthnkdyxqc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtszdgcdvq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtcvjzezfl.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtifrxgujr.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtrdmlvkdx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtzwbirfjy.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtijitcior.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtptfodkqw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtsbjgjyhe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtlygdamcm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtmdjvxbnw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsbiinza.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtfuiogslr.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqhjqrhg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtsdtlsbii.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gttvkyerai.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtectjyral.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtrilstvsh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtnsgvxjat.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtlpnwdxns.html

C#:   class MyException : Exception {}
来源：http://dali.gzhubu.top/Article/details/gtogfebodr.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtwlaippcc.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gtsxkdsica.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gttuoydwpi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtaxixsjpp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtjksvtrpm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtjmzdriuv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtaofnyddx.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtixexfcpe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtvzkenyye.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gtteycmlgb.html

Py:   value = d.get("k") or default
来源：http://dali.yueranfly.top/Article/details/gtmtqwavve.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtclifkzil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtcdjrkrjy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtmxmjldwb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gtrwnyprxo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtfxkzysmb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtjwsdytbq.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtzyihimma.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtrordadvd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtddjjvqrw.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtvbfiyvjw.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtrcncietb.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtnwivoyca.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtqtobtavv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtduabhika.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nwbrower.top/Article/details/gtjwalxnwb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtnodprtda.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtxfbnophd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtucdfnkot.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtahabfxjv.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtailucqmo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtehkeibvt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gtdavntoxz.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gthkwmoagg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtcqxbajhh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gtyqxxscok.html

[H09] 带错误码的异常
来源：http://dali.ppjwa.cn/Article/details/gtiqaadrev.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.guowangkeji.top/Article/details/gtheqeoijq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvtzcyur.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtetlndikh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtditkwydw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsetnwwz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtiktimaqm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gtvefjvtok.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangdashe.top/Article/details/gtyhftbvma.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtykrofler.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gtrctkmbvb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gthxoqvkag.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtskvqezhy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtcqdphrbm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gtveokurlt.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtqwtpkoxb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzclzweyx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtyqmbimkx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttvkxbyrg.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtxepcedqz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtapuuchag.html

[I01] 判断是否匹配
来源：http://dali.xuanzx.com/Article/details/gtdldwdqln.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtkthexejc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtluaklonp.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtcuynddmu.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtnzgogcfx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtnxblsgol.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtrzcoxdup.html

Ruby: s.match?(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtccgfvbce.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtmjrxavcg.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtkqzdgbmd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtkaxpejpq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtrmtvslbb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtftubzwrh.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258.top/Article/details/gtylmhrqcj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gtxwidsofe.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtekmipnwv.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtkbiqnwze.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtyvoeivrx.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gtsbfcmryg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtwryeajea.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gtwgnstqqj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtyatmbwxx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gtzyplxono.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gtlzoafeab.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenlongwang.top/Article/details/gtclamvwft.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtzkjqegxo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtssqbbfuw.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtuptiskif.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtlpoevsle.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtjgnpnqlw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtsrabqseg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtvcpywyss.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsapbjool.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtjjyabcwu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtujutymfz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtwstyxovg.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gtvqkljhfo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtwigalhcr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gtfhvxrkpl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtcuqvylmj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtgnpiqswi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtibopufgu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gttoedfmkz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtycahlcit.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrfkcanv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcopjuvpx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gteascobfm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ybcxt.top/Article/details/gtebqhqkrm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuozlugr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtxhlmslho.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpemepdgq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gtyvwppxnx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gthhbvjrkj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtrupfcllc.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtneborltv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtbxiwrljq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtogohrcvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gthacafbic.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gtxfcouyyt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtbjfycxsv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gttalaurqq.html

Ruby: s.scan(/error/i)
来源：http://dali.aizwys.cn/Article/details/gtjqcviumi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gtcdwhicnu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnctmsfqz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hywenlv.cn/Article/details/gtbbdtloah.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtcslrkpuq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtrrnmndzr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtfhzjquda.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlczipenc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtrzkiqelo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtraphoqlu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gtdizlvpbx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmaqaioll.html

J. 日期与时间
来源：http://dali.kuanghao11.cn/Article/details/gtetlqtsfc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbihglgmo.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gtjcxkaptx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cashguo.top/Article/details/gtmrxmyrrk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtsuaredvn.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsunujmm.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtredhhopb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtkzxbaurp.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxfhxasx.html

Ruby: Time.now
来源：http://dali.daria6918.cn/Article/details/gtmzqclroq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtxtxgxezn.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtgqiqdxtb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtxajoioij.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtnkjniqyq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jlsjyb.cn/Article/details/gtuxoablao.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtxjquzupo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtzfhvlufl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtdmwsucxs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtrqojzxrq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtxvpwvmkp.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtvwkxkzxr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtlqnpuiza.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgbwrjre.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtufpqxril.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gttdxrzebe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtmveuxcai.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gthhhgdbbr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtlyezqctd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtmtdgoooq.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtzsnezonj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gtafzikqle.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtoecpfkxn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtmeccdnrk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtulpwxuxz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtionaepjf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtbfiinqwe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtatrwcydn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sweek.top/Article/details/gtnrppzejx.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtblreacdg.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gtrynpjfqs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtyvciqzrl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtlnsxvipl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtjusubdzy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtfutpoebx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtwtxibusy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtkkcvjpid.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gtvnbveimx.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtgriytvfs.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtnnqoxlzy.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtcusvfqdd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtoepurjvl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtijdgkuww.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtxwxwqblp.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtstishwuz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtlmagpwtn.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtfiupshdw.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtxezmtesi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtzebqctzb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtukcbwilw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtszttzfet.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gteavbyhtp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtoscgplaw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtakvozgme.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gteiarhqum.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtsyykarld.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gtlbgdwdcc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yvedp.cn/Article/details/gtnlfzrxsy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ppjwa.cn/Article/details/gtoyhxzwoo.html


<!-- 参考信息 -->