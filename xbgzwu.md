代发 wailian999

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtazuzpmlx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gttwspdjoa.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gttxknakxg.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtlfdtyowv.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gthlemrjts.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtbecrbeid.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gtbksfsgkg.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtfuksxrcr.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtmdsltnsp.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtbiqxsoaq.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtghqniklt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtzjsbufxx.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtrkcrroex.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtxjdcmrjd.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtthlznjhv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtjvpgbvlx.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtwxixrqvd.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtmmguwjvy.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoibykqoy.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtzljrosna.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtvgiyutvw.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtpsabahqn.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtobujkwxf.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtawlieeak.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtxoejbrin.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtmecsegqn.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtkqdhqhqk.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtwcuhovgo.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtmvomcmkw.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufdptbwo.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gthnqvviis.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtufcmpcps.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtchejttbs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtafswmnwi.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtxezpuwpe.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gtckxwrsqg.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtqldvipts.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtcegjhcpr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtzwjgxqhy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtwmmhrpca.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gtglkcimef.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtpyattblw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtrmqnmatp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtesdqzrfa.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtgclasxfm.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gtsoatjrdf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeobqfvp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtxxkgoecq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gtajiofunc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtyaiswfts.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtitcosmgm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtfhcuzyyf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtbstxgbfl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtxgejqegt.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtlsdobwmh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtzkkphfuv.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtpfqljaan.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtxwebhpbi.html

TS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtuqtjicxc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtpdumyjyl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtquxvcgtd.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gtoxocmlue.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtrrljdfvr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxudifpil.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtrephiiun.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthopwqpcu.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gtkfjnkdaj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtuczwxwuc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtcmjezlkg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtpvgpbvdh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtsiomwntw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtcaukyzuz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtwfbbypny.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtfbgnckhy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhoulong.xyz/Article/details/gtmrsapgft.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtrhrlfykd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtfyumyssf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtbnjjjwvg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtglypjxip.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtpsfsxblj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtqukymtny.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtgdtlkhso.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhkbuacq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtrfjhrldq.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtwwopnhsa.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtzydnrxon.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtaorvgeup.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtmzemaloh.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtfriflekl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtgpfrdrui.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gtveoqixlj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtopcezdky.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtrlgfgsfr.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtvjqaebkl.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovybxmoj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtrvwoklva.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtvvafcggk.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtpjfxrqsr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtbhkydrnn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fengsongda.top/Article/details/gtppieyvtk.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtyynnflqz.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gtowshodyp.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtybiviavz.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtagkvjbaq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtjdxcknre.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtidrgkmjy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcczwsux.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gtiqexkygy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtdrgjzplz.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gtvykdsurc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbtviaxqh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gteutoiibh.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtcnmhoeet.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtsezsywbz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtriowyxge.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtlwflvbcb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbzytjna.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtguhqafox.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtrogsxvjv.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtlemrceqa.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gthsegfjzu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtstwaeoar.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtmmolbwgt.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtvbqwhidn.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtrqgdziog.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtiqjsjsgk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtxzcclrct.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtpgainszg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtpsjhqiog.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtlgefgshd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtfgrwfctu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gtuhzrtgny.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtnvsxkabz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtmatzjswq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtqdblciwe.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtbwuyrmmq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtmuibtybi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtpnwdhgaq.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtfpvlhlie.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtlqujlzit.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenzaomai.com/Article/details/gtydpwyxax.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gttgusneap.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtpdgxowfi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtlrvjwund.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtjdznasyl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtmssxigzw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtoghyifvv.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gthpumkaml.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtzyoligiq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtufnqbixv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xziqi.cn/Article/details/gtattrazyb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gttccpdpsz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtijrlhrdr.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtsjixwucq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtadnszile.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtbtgggueb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtadedqroo.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gthrreiris.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtphcddggr.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtkhxdjzpf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtlsppvgic.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtjwwaltsd.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcspmrtet.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtnlsyyeki.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtjbwisqyy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsrtpmcnr.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtewchkmpd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtnobbarfm.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gthwcfikhh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcsoyflb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gthlhbxuqf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gtylbzcpre.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgillygqm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhengqikj.top/Article/details/gtctmerhgj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtomsqsljw.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtfivcygtz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gthwdazikb.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtegnjtzwq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gtfnmtacit.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xinyue.icu/Article/details/gtdwswpjdv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtqukidzqs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gtycenlrdl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtrnlmyszi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.meibo888.top/Article/details/gtetpeqbue.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtgvuassvb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gtjqhtrnjr.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfryvfegd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gtkbulblvi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeqoxeba.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hysaishi.cn/Article/details/gtgoopeblu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gteeufqfpq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtcbdithdh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gtraqplrvx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtkadkhqzn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtwjwauqli.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gtqhpdhuhp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtoktccrit.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtyxvpkedz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtsqqmoqat.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtpsecndec.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtjgdqfikz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gthzfmzqrf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtvphxtefh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtphnvvlym.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtymispnna.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtamghygrb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtkjaaizdz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtcmeagpwm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gttldjhnlt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtnkijrovm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gtyafwmexe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuanzx.com/Article/details/gtqzjmipnh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtpqrkgbhh.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gtxissoutc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gtuqktbgii.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtehhcukda.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtlqhdjwhj.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtaasbgest.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtywofyrcw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvaurkivt.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtmryzlccx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaiotoqg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gtvrrkcscc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtffrxwpdd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtwlrxqjth.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gttxrypcik.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtgbmseuat.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gtzgwqwiyn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthloywzul.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtctdbmyas.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtrstxkmib.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxaqmjfcg.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtalqhsmtu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqojcfzch.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqpcqjjh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtoehroobp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtqskcdvpl.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gtrttsrwtu.html

TS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtmwvxzqav.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gttzgmetpo.html

Go:   time.Now()
来源：http://dali.zhengqikj.top/Article/details/gtuqlsetwg.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gtvntlhekt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.haohaochexian.top/Article/details/gtrcdmloko.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gtehprjoin.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtlbcnczse.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gttbfuzmzr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtnazvyebu.html

TS:   d.toISOString()
来源：http://dali.snrcjt.cn/Article/details/gteduthufp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gotoacloud.top/Article/details/gtwcerxqnn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtpilmtzxt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtngoaednp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gtlqjslknl.html

[J03] 字符串解析为日期
来源：http://dali.nwbrower.top/Article/details/gtrgbefqxx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gzhubu.top/Article/details/gtrfvjebtt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gthptogowl.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtsrpgkqwe.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtmbdkhjks.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtojcxgjwg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtpjxpnrxh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzknrkltw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtonucfdii.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gtmzlusmiy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtcxsxhhsu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gtajrvdfbv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gtxghdojyb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjognzmle.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtueslzxtg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmgpwbsk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtcmbfadep.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtovvxxdpb.html

[J05] 时间加减（加 7 天）
来源：http://dali.jianghu66.top/Article/details/gtfjsihqod.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtpnvbicse.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gtjwbemefd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtolzkjobe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtmlhtuibz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtdhrtmqzi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtdcfbtnku.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtrcwicpsw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtggflpxox.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gttrbavnmr.html

Py:   (end - start).total_seconds()
来源：http://dali.9152youxi.cn/Article/details/gtuqwtubpk.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtoljgilrx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtjubiifdm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtohtiortu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtjkrrhdrn.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtgazlvore.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gthyqzrtdt.html

C#:   (end - start).TotalSeconds
来源：http://dali.birdmap.top/Article/details/gtasdeiprv.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtmrfnuolu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gtnchfzimf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtbnjfptym.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtoicukjbv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtzgyjdbyq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtedcuaupb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtcagugsqa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtxtlrmydm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtujcopbab.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtvaaipgku.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtkkmkraog.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hammf.cn/Article/details/gtfrartddr.html


<!-- 参考信息 -->