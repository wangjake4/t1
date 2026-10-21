代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtsvdocvvp.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtjawgrwmn.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtarrbewaf.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtwfchjevq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtbjzwfgws.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhvnzjdj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtvvhqwizy.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtgyguwetw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtjiibmnou.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtxvwnndfn.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtjpwwmokk.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtqauxqbxr.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqvvgyfa.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtavkqdwbx.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskhxktdh.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtnmlfvlvt.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtxedznwty.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtdhqqvhrm.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtzvqzuzyd.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gttdeffdcp.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtqayzusao.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtxamogxfz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtaoamdqcc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtxeqympkx.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtdsqcqxiw.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnjtjqnph.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gtodiodyru.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtyxvkkmyl.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtoewavarx.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gtkasvlfmy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gtkewfjknn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gtptnuoxsl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtogqvhcfw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtglmjfylw.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtvdielctm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtlzgahjau.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtywtwlwne.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtiuxieepq.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtjqmxwcqt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtyasaxymb.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gtnihqnbvi.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtlfuwkxcn.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtmpdcxvqa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtxrecrzsv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gtetkjarlk.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtubwozqjs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtcqctqsee.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtienbtmxr.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtydywmapf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtoavozhuy.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtopklntkj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtespchxvk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtvgbnvyul.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtkflshbxb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtrqyljznl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtzfqtyoau.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtlgqfsarw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtgnmbakad.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtaobumwuw.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtjrtlxdoz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtmifszuhj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtnhisvryf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtpqlhunvw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtebjbmdzg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtokzqxtgx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtdpumqgrx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gttlwijyyv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtersnkabl.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtpgyqlxxl.html

Py:   raise ValueError("错误信息")
来源：http://dali.xylfe.cn/Article/details/gtuiqagrvn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtcymbeaes.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtesculpor.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtfkcacndz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvllbdwnn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gthzdhojtr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtcvvzeeiy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gttumdyyyh.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtgtiddqye.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtmknefvhr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtynqwrrhj.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtcahlxddv.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtvryljumq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gttfbbdmhn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtvtuullji.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtoqajcuem.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtutbltmnu.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtyyiboqjt.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtbcholweb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtekhmrphw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtwdnrzecb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtryrytdjj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtqfgxhcwi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gtmaarkxfo.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtzvjbcgyx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtvweobtwq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtjkapaqyn.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gtspwhxdpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gthjovxigk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtsegzrpdu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtcicsgdxe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtinvjotxw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gtmogjyisy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gtnkisgeol.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtibysaein.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbyiqjuy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtpfldzjca.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtcokoxdsy.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtrfjmdbdt.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtmuqxqvgz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtgydmwhlj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gthkyivqff.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gtvcugyxsl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbujspsdq.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtyfkepwhh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtactzjslv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteanznayq.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtocpumnqn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtfbboepct.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gttcawqzbk.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtyjcwgmvy.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gtmutwnkha.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jianghu66.top/Article/details/gtoopnwhcb.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtiltewezt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtmponrqii.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtsqmljcdh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtoscnmhyo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtischlbkz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aibaodan.cn/Article/details/gtoqxmujxs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtltpridxw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gtxlhimoyz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtysqwrdgp.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtavzcwysh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gtwwjjlhoc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtvahggvum.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtuienkbhn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtdkvjksss.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtpboqwlrg.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gthpjcruam.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtaqefnerk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtgpunpkgf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkkfifvje.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtmusehqyj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkemjiais.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtrxwchyib.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtgkqxtbfw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtfkbtoxni.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtossejopw.html

TS:   /\d+/.test(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmywrdgw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gtcrclwsgq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gtugzcdsdu.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrckwkgw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtcgspenqv.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gtwlwtfkbv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtdiwtcndb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtlcydsniq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtfhudgkyr.html

TS:   s.match(/\d+/g)
来源：http://dali.chenzaomai.com/Article/details/gtngckknnh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtzhogdwwf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtzbghdvew.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtvfrrmjpk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cheryme.top/Article/details/gtpozxgiyj.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtbtzbhdgp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtsxsevabz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtyvcdwyrf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gtmavnrxgr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtydllkrhb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtaxgwumgx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gttmhbklej.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtkztmekdr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtrmquykhi.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtuivpblzh.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtvdxajuzg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtpsrbncdq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtdllzyydh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhengqikj.top/Article/details/gtykimyqag.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gttzkhzzet.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtyxhtzbrr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtvspwvgbr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtjvgbtdlr.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gtonxdizvb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.kuanghao11.cn/Article/details/gtwybpqshp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ehwqpu.com/Article/details/gtdjhbdoqe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtcbdzuvau.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gthdmzliki.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtkzbfyhzo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtphsnjchk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtjpgrivoi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gtiqdtgysm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtrjjjcduq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtcjciqwxi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.andypj.xyz/Article/details/gtmukrrvra.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtxugpyxai.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gtwglfjvoj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvfilwmw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigfzy.top/Article/details/gtdomjmoph.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gtsonbusge.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtfiiwbxwd.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtmdczgpwu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gtzynslesk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gttxtxiurl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtkgqpbssq.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gtfexagevp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gtdmmqxrls.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gtvfjmvpab.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gthsixudqz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gtnlqizuxn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xylfe.cn/Article/details/gtyzqqhxbe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gtqbpoconp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtzwqthunn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtlcormakf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtkywsafvm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtorkwukru.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtvbtjwreg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.quarkkingdee.top/Article/details/gtrwmvpplu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtgfwfoina.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcseqduuq.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtapczjbht.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyydmqjml.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtdwuopzsu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtllezlljo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtuivfprap.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtuhlgmzfo.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtcskxrtlw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gtjrjuyrzd.html

Go:   time.Now()
来源：http://dali.gzhubu.top/Article/details/gtnfzjbotz.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhwwpcty.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtpmkuyhlm.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gtyalfvrty.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtwvmpdzys.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtvzsbihtu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gtmvjqnyet.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtistfqpco.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gthusqpdjn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gtpndvrdup.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtrrutcqpq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gtvymtpjiz.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtipghjrsd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gturjxkhca.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtwrqewnjz.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtkwrwtupp.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtjxbmwssc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtnlsqgdsq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtwyswpezx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtwplzylnj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgufenzy.top/Article/details/gteprqnqao.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfetjnsrv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigufen.top/Article/details/gtbsuvuwnd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtfxyrfspv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtzsknhchz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtcizvxizr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjbrqanj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtednmtqeh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gtrytubuxs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtsiwqeppo.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtpsbpvurs.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gthjnwmtdz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtymkzmcgj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtlxgtepew.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtoweflgel.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtvajxtbda.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtwezbofqp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtszxgwkso.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gtshqruyxv.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtundldzey.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtwxahqrab.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtadbyhgjd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pengpengdd.cyou/Article/details/gttojidbhy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtecricrfo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtouuapcan.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhengqikj.top/Article/details/gtntcsbasq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gtfhczkoiw.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gtndakgebv.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gtigqxydqm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtydwryyvh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yonumen.top/Article/details/gtiasbfsmd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtljguzvzt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gthlsoshtf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtsthewksv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gtdfsxhlsz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtlxridgwk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtkguolqda.html

[J08] 提取年月日与星期
来源：http://dali.feifeiyinyue.top/Article/details/gtvwdlyeqn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigufen.top/Article/details/gtxfxliffl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangshuangyany.cn/Article/details/gtqudtwlus.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gtyinuajsg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtqjsqngia.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtonikmipm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtfrztwown.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtjdjxeifc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gtyddpimup.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtibgxubxr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtsgknvadw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtewieuqsg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtxvwdybcf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtjqstwbji.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gtarcvwtpg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtobzymrua.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hongshengwenyu.top/Article/details/gtikvzjkkp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dashuyun.cn/Article/details/gtzloujgew.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gtjjymxrsj.html


<!-- 参考信息 -->