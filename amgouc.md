代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtpsenrl.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtoocbeygd.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtjepyglsu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtysnccadc.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtlkppzgfr.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtnohgvpyj.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtotysdpuk.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtioenofot.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtbekklwwr.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtvxutmmpa.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbagpmkjg.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtkagnwazs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtglqpixnh.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtlqbtoxfu.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtkjwztsxf.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtudjxphlf.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtcqyfazdm.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtvmerkzjb.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtpizeaodn.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtkcemcpeh.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gttvkoqyml.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtseewyzhg.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtqeygkxnq.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gtbtppdwwk.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtyltmrqcy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gteduxpskq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtxfnijzxt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtrvayyrej.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtdqzkqdio.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtilevnhzb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtirbxzgef.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtnwftlsnt.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtahgwafvj.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtqtjxzejq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwahuxyk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gthuzlzhsg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gtgqntyapd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtrkthpiml.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gtajhpszkm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtqbuctcyv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtyfuvvmej.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtnwopjbiq.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtpduixbov.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtbesylnua.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtdgtynfhc.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtfkblswhh.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtbspwunak.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtsvwahvsq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtbrvjcrfe.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtphcsbxyp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtyowkzkcr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtikriacdp.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtwxrolgpa.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnligcxfj.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gthxuqqyod.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhcpuqpi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuffbeohu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtdjoerhwk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtzvrmbhjp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtcakwpudd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtzustocxw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtxeqdnxwh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gtdheurpty.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gtpeevalkn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtixnwwwtx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtgzipfvmw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoghizkz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffkwewel.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtayubrakp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtzdmstntt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtcvwhbkhq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtrnszwjls.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gtncjqmzik.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtqgeummzf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtsbqarvsv.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtyvmvrxvr.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtcegwtfmu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtxbzeabff.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhtzhncw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gtuheaoacs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtmzrtvfxj.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtqxtjzipq.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtaendozdf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtydwrzbhd.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtaexasoab.html

TS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegjipwwr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuplcjipa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqqlszzr.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtifzptjjl.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtsvnhbglb.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtmsdfetkw.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpabrhxti.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtyyibokqw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gtopcgltoe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidcraysk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtfkuoktfz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gtxchexjvq.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtjozasawo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj202588.top/Article/details/gttnefijfu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtxzqbqvqn.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtuixtlnbc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtksgmsyiz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtyqbkqukh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtxttpmbuq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gtbricgdhb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gthwprniwb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gtswznxtkn.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtjesjgvri.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gtwmvphqss.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtmptvwnbr.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtlmenvjce.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtdwpznjso.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtftdwmuga.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtnloxuooj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtglizccyo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.bjfxy.top/Article/details/gtizftabtn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtfrwnguuj.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gtnketdueu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwoddusu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtxtpfcguv.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gtiapmpzsh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrcvvmkz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasfxwmye.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtmytnzsej.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtvaqbjctg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtltgyoktz.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtxesqtkyk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwpdjwnr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtavlioqjv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gtfjsmsynf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gttrwxbzig.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtocpahnef.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gteelqaywm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xinyue.icu/Article/details/gtdhdeegpm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtdvbpeber.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gttiovyfps.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxuanxn.top/Article/details/gttkisxwni.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtwbczpala.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtxznrulfn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtirwnzcbs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtrkqswsoe.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtqyzlhxrr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtnzxnxlli.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtwzfnsrve.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthpiztkte.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gtwvivnegw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtyyiwmkug.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtffmdgiwb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtqiozgytp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtdbglfvwh.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtamkgbrdn.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtazfthsqq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shuidangran.top/Article/details/gtzhsjusfb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.9152youxi.cn/Article/details/gtgycsiqps.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtzzhaipuj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtfcdrzjef.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtgrtvcypg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtmbdpirwl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtfpsshuwm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gtzuqxhews.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gtyconanfs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtkpisuyla.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtwfwyqwsg.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtojakliqh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtmrtunbbp.html

[I03] 提取捕获分组
来源：http://dali.xziqi.cn/Article/details/gtzazjquwf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtidhflckq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtxlrbsvrm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gturxpbfip.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtnzzhyocg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtwqwrfbdn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgfzy.top/Article/details/gtesvpuzrz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gttraxljep.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtwuclebzp.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtoqoqdotn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gttczogwee.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtidrbrpid.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtzytnoejz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtpufikrgt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtuugrxvko.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtwdqxoizw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtivortmxf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtwgqotujz.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gtoxewjxqd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtsbbsurag.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtnnunlbfu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gtosyktwli.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtvfutbzot.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gthfyvspld.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtowkjhglc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtlsaucoep.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtarveunns.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gtlqltlebf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gturywyttk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gtvhvvooyq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtmwboxwce.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtyyoojoiq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtnfxgpnow.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkpbifdx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sysykeji.top/Article/details/gtkjsstiiw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gthbgpwqgo.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtfkdkluze.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkglnhpwb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtgwctvqit.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gtrhjzqohl.html

TS:   /error/gim
来源：http://dali.zhixingplan.top/Article/details/gtyksrapgc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gtwngbwmla.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtjhfkkvxb.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtrcarcqcn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtgsbcunwp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtyawoauem.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gogol.net.cn/Article/details/gtkyvqsbuo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gtxktxhzxl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gthacqkmcy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtjifsupcd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtufsdhokq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtcvuuguaj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gtosysnzlq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtohjiyvdo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtatjdxycj.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtsnmlshsd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttzuqnxeu.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtgevhwoeo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwatglcrr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gtzokktdhb.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtdfpajesb.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtlcitzfkx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtgvcbvjba.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gtzkndbzyt.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtkvlipntd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtyfoasjqw.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtoufklxtc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtdugizwek.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtjtwarezq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtkspsxuji.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtnsttqagc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gtenuvgdwi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.smart0.xyz/Article/details/gtrbcshuri.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtgzfnugbx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hfpthk.cn/Article/details/gtzfzqkobr.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtlufiulch.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtuqcipruo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yvedp.cn/Article/details/gtgavbqkhz.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtjziuvgpw.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gthrxqankb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxelvvjtm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtftcfbcwa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtccopvsuc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.fzhhl.top/Article/details/gtgdoasida.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gtmdofngwq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtfxddgzmw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtqfmabwmh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj202588.top/Article/details/gtlumnocas.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtuuvgwowj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtqecfuyjv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.wangdashe.top/Article/details/gtcxbxrphd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtnhzsswcw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtwfrtwjiy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtcrhkvzhp.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gtjglhhluj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuanzx.com/Article/details/gtxufgrina.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtprfftljl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtwcchcuob.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shuidangran.top/Article/details/gtquwzcccd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jlsjyb.cn/Article/details/gtucjaoljs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtqiuybsdu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtqdlecqnd.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtnpegceec.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtuwjsbdgu.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtydosebvk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gthwketree.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtnbqemvhm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtxjrigtvx.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtjsiokfwf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtmnjfepym.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtsyrkzmnh.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtxvpeyarp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtbbfhiojp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtxawejnxq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtdsdqwscm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtiwurobcy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gthllbqecn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpngqxlf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtbqhvrnku.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtjhszjsta.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjuoqyib.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtjaypmdec.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtasfxhpqr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtjsyyhxjt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtkjubwwav.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtlcxlgene.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtbcfhlzdj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yvedp.cn/Article/details/gtswkinguc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtnjbybgae.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gtsbjfnyhl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtaoavfpnw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gtfzwohdbj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtwajmbpvr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtpgjaalnc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtupmhoicb.html


<!-- 参考信息 -->