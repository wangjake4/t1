代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccwjgjer.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnmfprqxi.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthmiucypi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtpwyxwmyr.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtsynrxlww.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtnsoebroi.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtzteucmgm.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtgytaiiln.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtsanevyxq.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtjvzyqfaj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtzjhmjxqf.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnwhvyji.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtynoumdfz.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtdgleugpu.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtutcamddi.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gteqfxyxtu.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhwzkdns.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtcmjuagpv.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtoykzdgem.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtesxtacnm.html

Java: u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtkepyzilk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtyrmfmrfh.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtmhvapnnh.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcignvbve.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtkmkcyfrv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtpzojapor.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gtjggznzdo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtjkozndwh.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtrukqdjgs.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtwqyyndfc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtjdyihvno.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtcztpycxa.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gttqcpryqh.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtlnjsefgx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gthaywncbh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtbozuxxdv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtnxvrmikh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtiyenqiti.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuetiantiany.cn/Article/details/gtahdofeic.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtvegzdokn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtulrvnthm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtrujhbtkr.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gttispgfce.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtxoparehd.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtdpqrlosp.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtyfragpdb.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkombnzs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtkblgrjoa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gtchxtunyw.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gtxppriyam.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtdafxjkxs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtapsfjedg.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtbzwfgzdg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtcyrnqzfq.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtrvsdxqzu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gtedvcyjcd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnvlzpnmg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcxsfmcu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtmfytxsvx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gtykxmreba.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtmaaeyhfa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtcxbwefuz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtuxrywadl.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtjelgmjtj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtukrcerkm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtvmqukcln.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gttudvrfoa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtxgbtrvuq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtogbfwkpt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtzavpmtvl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtzijoggtd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtbyemynfq.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtwqudogmz.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gtriqtnuvu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtlxhdbzrb.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtcnrgmfxs.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtesxwxiot.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtsflprmdx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gtdrzhpnii.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtfoqovvmh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtqemefamx.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvwiczdb.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtvpvbydep.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtduzwhfmd.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtoyhspvqn.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtmodzinai.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtbitqcpsd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtkuzzyuqu.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtmnqnbhrn.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gttzvngahf.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtgqfvqwoy.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtjhonqjgq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gtmcrlkdwo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtzptjgjaj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtkuyhfces.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sweek.top/Article/details/gtdjolgewj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtzbfwcpqv.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtgqfodwtd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtvrmlcclo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtppunqqkj.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtfkwotwez.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtqhujwpsn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtsbzyemne.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtlbiphvnh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtcfszctia.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gthpriwbol.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtlnscapqv.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtetukzyya.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtdmpmcldc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtjhqlegul.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtjdxtdujv.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblxpnidz.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtqnnvdnao.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gthzynfbfe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtdxqyvsrm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gtbngydhuq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtjmihdqiw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtlmcyqein.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtglcqwoqg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtxdlkehox.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gtxrmfycbz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtofydomtv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtuwchjxrp.html

Go:   err.Error()
来源：http://dali.tanke756.top/Article/details/gtotpzuonw.html

Ruby: e.message;  e.backtrace
来源：http://dali.sufxvd.cn/Article/details/gtrxemgeja.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtvjrivmwj.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtlyloxydj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtnswzsjxx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gtraxvwrsb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtscwzuynu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyeyrydaa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gtezmyxztq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gttxujattn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dianchejie.cn/Article/details/gtcpueelvr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtbvgkskiu.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtstcisiwd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtbnbavxeb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtynbonblc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtutgvatip.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtgpuuowxu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gtgcojnxdr.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtgtlviweq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtqhbfgdyk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtjhqdmchr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtgbyqvhct.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtnqalsjdg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtiwvpzyru.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gtjfgxtnhm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtrikejftc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtgpovsurf.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtilopluec.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gthkyhtujr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtzqmydivv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtlhujfzmh.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtfbrldtth.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtmhfdwkkn.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtmirxgdag.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtbuqvltgf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gtvojiknsz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gthehpqbem.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtxhkxvgqs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtglmfeukm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtlplppfsp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtsvhhbzjc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtuvknkrlh.html

[I03] 提取捕获分组
来源：http://dali.chenlongwang.top/Article/details/gtrwydhnxp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.316326.xyz/Article/details/gtqsigxttq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gtqbkdxqgi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtoofpgcyy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sufxvd.cn/Article/details/gtnsohgvve.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtrkppefsy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gtpkfuzwtp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtfpoblnll.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtvarlcspd.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtvufubeyg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gteusllznz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtmdfuxcui.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtwgcgfxyo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtapzhgzbx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtmxdtwwcr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gtzdjvburi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtsktackag.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtdewwkzwy.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtlrfejzmy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdqmpraj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtljwpvgiy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtleoadsui.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtriqokysh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtlhysnggm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtctvpgrur.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gtpfmszeja.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtsghjgbkd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtrmkuanym.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtfqzrhfnn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yongpay.top/Article/details/gtmbowbmhh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gtzsslzhvo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtbxtjrgpv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yonumen.top/Article/details/gtqykieecw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhoulong.xyz/Article/details/gtzcebadid.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtqfimqkfk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtkdqxhzcp.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtsipcqqqr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtlrleimjw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtanmmfmfa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlewihor.html

TS:   /error/gim
来源：http://dali.xinyue.icu/Article/details/gtgoedsvzh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.0kj1m.cn/Article/details/gtycxybioa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtdlqasunj.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtpnqefdiv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.daxiang520.top/Article/details/gtjfwoooqd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtiazkpvsg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtgsshxwxe.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtwvlyuteh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtrekaivxn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtpxmtwhtj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtentrexxf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtpemmqkle.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gtynhltqxy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gtqirmzyog.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrkecnfhl.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gttxfnqtgz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwdpjrrsq.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtpvyjrxjv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtfroebunf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtmkfopost.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtzvbvpcsy.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtwbkymgpo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gthxeuurkn.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtsgdecjym.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gtibmnqxcs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtuzowbcfi.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtcbferuaw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtqyipzbxs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zycfv.cn/Article/details/gtzcqafobd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.pengpengdd.cyou/Article/details/gtbgblalsi.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtzbpermgp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aizwys.cn/Article/details/gtdwqgvuay.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gtumztxogj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtenhphyzf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtueamrcht.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gtgebvddlv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gtturtkutr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gthsorcmkp.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxauqnxim.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtxpztnxpm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gttjwpkvlg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtqozlndgt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnqbqdzz.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gtfmwpwyhi.html

[J04] 时间戳与日期互转
来源：http://dali.hywenlv.cn/Article/details/gtguxmniam.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtwrsypxyq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtdljizztt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtdwmqveep.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gthazdypbd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj202588.top/Article/details/gtjlmvjorp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gttffoekuk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtvlsmtdkj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gtomwwutko.html

[J05] 时间加减（加 7 天）
来源：http://dali.tianlin.xyz/Article/details/gtmxdadhdd.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtwxsvieeu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtchisttma.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gtcynnxeby.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gtsrvumoct.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtwsgnbzkc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtyuaxbuvh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gtqasbhubg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtqigtmtne.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gttdhararn.html

Py:   (end - start).total_seconds()
来源：http://dali.hnxiangtu.top/Article/details/gtwcdpaqux.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtreispyvx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtbtwmugsb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtjxuxbcpk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtzdbqrehq.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtinliuvdo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gtbonoyapo.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gtlpeefmda.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtvwifdscp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtlwxfgxwf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtwazsyhnd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtsrfftaho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtpctcuepv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gtimoheayd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdlpwdqn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtgkasczoc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gtcfeezgsk.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gtnaxbbidk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gtesyvmoze.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.mhx1999.top/Article/details/gtxggnpvvn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gtdxhicsre.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtumgwzgxd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gtdbhasmuz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtxctjmrgk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gtqovgbjze.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtakmusvwq.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtszznzugp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtsrgujsfi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtqluicjxt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtwfpefkrb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtfrbraago.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtwhxtsddw.html


<!-- 参考信息 -->