代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtudnrwozt.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtwkefwwub.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtwbzkgagj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtnjtanapm.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtvdvgdysh.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gtprqilyky.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtmqlemnbv.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtzanexlno.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtndkypxcd.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtgzdwpseh.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtvyvwbruo.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtujocpdgs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtecxeqmwd.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gteyynpupa.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtexrshght.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtdppzqonk.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtosvibfnf.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtyrcjvsul.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtxdkugytn.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtnbvgvmny.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtkylypbme.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gtvixfnbun.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtsfbqfozc.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtmcahmrzc.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gthyvrzhpq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gtlarrmaqs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtiyusetoj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtsoqhnojg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtecizenek.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtvxdeirtr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrujeczh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gtferutmyf.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gteqeugmlz.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gtopaueetw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gthjvjwwkn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtwzzkkbdk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtnhrisdgp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtqfgwwotm.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtscnqrtnl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtznjqizeq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtdtchdbka.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtfklfphmu.html

[G16] 对象转数组 / 字典
来源：http://dali.smart0.xyz/Article/details/gtkwtnmhxj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtcwbuajih.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtityjmiwi.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtktklyqbn.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtczvxshnq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtfgpcwzvb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtzlqbwwux.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtcrfnakgp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtkgpxurbq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtihedpqeh.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtbjybmyye.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtokyfqcgc.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtjfckkwsy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtdvcpgign.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtufiybghe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gttqferpki.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtxbylvhsx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwvoirne.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtwnxfmrkt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gtgbstaluj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcwhqmtkp.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtbixvyjkm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gthzgkqjbh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtrxgkjahy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgovpfnqg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtcphxjhhc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gthoitnmqd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvlxdbsx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtizwpbhzz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtxxapzyta.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtqwnhxjvo.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwcwpzjo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtrjxorheb.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gthjvmlgft.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtcjvqvzsz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtewsybsew.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtytyiicqc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gtrtridhwq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtipfzufev.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtwcudlnuk.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtzlyksmcr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtmkwydwaz.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtyqolnlqi.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtrrnjgtup.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtlwtfjenr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtnkjnfhqc.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtelbuujxp.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gtbxlbtmde.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtjguuzpwp.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtnbeozptg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtqglswvwl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtxmqrkcda.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtcchpsbrd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.mhx1999.top/Article/details/gtijehubhb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtdylglhfw.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtzdsgjrqb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtsdgjyfvb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtgxruaycc.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtsudkvsyf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtldyxjzxm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtffnwcmxf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtzqxfmbqx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtypaiivjm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gthbugmfqh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtfcbvqgnk.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtvtxbedai.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtsbejfzdp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gtdssmfyir.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtasonmbpd.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtvfyzdtot.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gthofkldea.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtfgsxtwkp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtmdneaakm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gthdcpivge.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtjpjymsoe.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtdcleakhy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gtqmjrvihd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtavuxbfvl.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtgtlyzweb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtbszqgdar.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtjmejpfrs.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtoxlmxdzi.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtmpfzktlq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtwyutfluq.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtvwnmkdxk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtlbtpcuug.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxtcjshq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gteqqzmlfo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gttvamdnse.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtwiesbqdp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gtjhokgihf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtbsjmlieg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtroaglvba.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gtpqktuyuj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtirvpespn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gtxgmenbqv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gteuqgjdpy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtumeoijhi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gteawlcckm.html

Go:   defer f.Close()
来源：http://dali.yongpay.top/Article/details/gtuaobfxrd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdylyvtbo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gtxutgdvsm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrruimgrb.html

I. 正则表达式
来源：http://dali.yueranfly.top/Article/details/gtbofgggwu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzkauyded.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtymkugrfs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtodkheyui.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtzhtqinkm.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtdvkrtamg.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdklzognk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtzsqvqhib.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtclxfkyqv.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtomqaniqp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtttaecepz.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtuxwlnhiv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtybgmwmyg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.redwolf501.top/Article/details/gtboerbzxh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtepxpckbk.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtbptwvyjh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenlongwang.top/Article/details/gtzqzmjxxo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gtwosutimn.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaetzszyo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtqgalyjvn.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gtevnoayug.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gtjgvryodd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtbokvkdeu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtauuhydoi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtpkccvdwk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.iojbl.cn/Article/details/gtjkjkmulf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtlisvwpkz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtljiqzmyc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtvwczhcbh.html

[I04] 正则替换
来源：http://dali.guowangkeji.top/Article/details/gtuclhhgxs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gtjpimuztq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjvezgin.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtlurjoxar.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtqxkyyonj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtjgppvokx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbcxkhex.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtsppfwpuh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gtvkbatpjv.html

[I05] 按正则拆分
来源：http://dali.hfpthk.cn/Article/details/gtoxpphpcq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlivylvdr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtyzjuvcvv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtylqynpqj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gttwdmdhse.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtkcaaodov.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbzjvujl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtfhuqebvl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtckzfpqfa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gtbwcrhkjy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtsdjgdlzb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gtbnpsjfmv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtehpvhpju.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtkbyzngyt.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtcxrfuryv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtathqocgd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtxvmlucom.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtkegkvdba.html

[I07] 忽略大小写与多行模式
来源：http://dali.havefunace.top/Article/details/gtdbikeeuj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.0kj1m.cn/Article/details/gtqxjhntre.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtqpdzsjju.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sweek.top/Article/details/gthkzparml.html

TS:   /error/gim
来源：http://dali.nanxuanxn.top/Article/details/gtfmhdfnic.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.meibo888.top/Article/details/gtlumuzhug.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fzhhl.top/Article/details/gtwrezlgid.html

Ruby: s.scan(/error/i)
来源：http://dali.hysaishi.cn/Article/details/gtzryvmyyb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zdqjudy.top/Article/details/gtucmoetzq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cqqwz.cn/Article/details/gtckypbyxc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gtjuamgxxn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtbjdvaqwl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtnysvuapr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtfhckfvjv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtcxiwibzl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtwbyguurd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gtpdjvzcnf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtohdbvymb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfjxeyqws.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtnvunkvvd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdmvserpn.html

[J01] 获取当前时间
来源：http://dali.xinyue.icu/Article/details/gtkyscrdpe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtbkulccnh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gthwiypmhz.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtspezleli.html

TS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtmtzvipqp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.quarkkingdee.top/Article/details/gtciparxvc.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gtwbdseona.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtfecehupd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmrqsngr.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gtuorvmfar.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtasmyaxfu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtkgnodwdg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtbolkjmys.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gtmmkxuxwx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtbmnkuuqf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shuidangran.top/Article/details/gtmxujpzbw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gtziggvgsi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gttdudofnt.html

[J03] 字符串解析为日期
来源：http://dali.yongpay.top/Article/details/gtampbwxck.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gtuwdzslee.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkymwqzce.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtvzrlcwbg.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtlppgwchu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtjlvmgzye.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtoishtpdn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtcxsifrkd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtawujcwlo.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gtszngtwrm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtkkpdrkye.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gtmqfjaeti.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhixingplan.top/Article/details/gtpmketmut.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gtxlarangp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtukxkthqd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gttrhhjpzf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gtfwgojzql.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtfqndzico.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtbrqrusgw.html

Py:   now + timedelta(days=7)
来源：http://dali.hammf.cn/Article/details/gtezmempdh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gtjqtxmfqp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtlohwbnks.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtufrvwjlz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtgjkkkkbu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.haohaochexian.top/Article/details/gtatpwqvfm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gtapnyxglu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtxfaxfhtx.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gtddwqurta.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gttczlgzpy.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gthlhzrxto.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hysaishi.cn/Article/details/gtiuwxurcz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gtpabtznxm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtoqjzoduw.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtjdtumpxq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gtpnhjgltk.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gtamfilkah.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtvjtktyxj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtufvozvnb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtnuydkjto.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzxbmuif.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gtksyigshm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtyvyaidqr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gthaniolii.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtdbcimblq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtyzwdedrb.html

[J08] 提取年月日与星期
来源：http://dali.ydzc1.top/Article/details/gtthpukaqj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtgxhdxtcy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtnywpqbnc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gtxufpbhtv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtquwhjngj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoszkgra.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gtipnnpjgq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtduhrigkb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtfeeoorby.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gtxhwdblxa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtqqsyyaqr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtqpmiueae.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtpcavbiek.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtszmityjg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnfpflrc.html


<!-- 参考信息 -->