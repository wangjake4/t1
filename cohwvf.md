代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtykbprlac.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvcbhfpm.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtdvzieolp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtcnvllrse.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gttcgoewpo.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtvltyubpl.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtefosffkj.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtfzwpscaz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtqoiewibh.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gthnradfqz.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtxafonnjc.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtmtkdrvxc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtnddjogma.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtfcljwxwl.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtrdhgphsv.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtxidqzvfa.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtpvxmnhjk.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtiucosqhp.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtewvluwqo.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtoqpfidgg.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtndbpgyso.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtgfluvrls.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtcnwbcuow.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtstzdjtjy.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtcraxqbgu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtmijpzhji.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gtnenuernc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtjdczcqqc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtedxhdtmg.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtzmsolzwh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtxtmrpdej.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtoydrwfbj.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevyaqdsp.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtmolrdwwn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtowvfnvgt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtizfamzqw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtbockipdz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtfmsmezqp.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtzouaycxx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtbnwnfxrp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkrwyrvz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtbjacxvow.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtnlsktjeb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gthuupeafy.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtmpunvxts.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtkrsroarc.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtkqcqxyfu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtxilmippi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtrcltwbdb.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtgonykkoq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtdrdeapnp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjihcyfka.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtmpxwtvss.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttnwzeskf.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtbrxsldzz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtfxzojalk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtgecclazs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtmajxwtas.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtspypbujs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gthqkehzin.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtoylxsobw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtdumzfxep.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtlpdkcnwb.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtiymlbfep.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gtlsaoarbd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtmrsszswf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtadiobfsk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtbqxxeurr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtbhpzzwta.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gtpdehapsu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtthpyntrz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthdtrpcty.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gthgduidnx.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtsnuyzqho.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtumimnmlj.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtwipgfelt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtlixsagfh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtrswhrkuy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtzecsoway.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtypspotxf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtntttfhbf.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjbiaygpb.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtqagidrje.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtotskklas.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtigommmls.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtiorbxhwi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtnnpcytqc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtszltxnyo.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gttzbafcmx.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gtgboaozgo.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gtioolemld.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtivwthjsh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtbtxfwwsn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtxckbkutn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtgwzeazec.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gttwhbpfkz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gtjmftqyzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtfmityiqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtedfpslix.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gttytpyzqc.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtgiysylla.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtttqlfjfv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtdhjhtkdl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtbhllcqms.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gtvqkitdie.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gtckrnjmck.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtduzigsti.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtuqfuyomw.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gtpgraumrv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gttkbpdmkq.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gthlzpcfno.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtpreipjij.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtmlwybxiv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtasyzftxm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.redwolf501.top/Article/details/gtaztaubcd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtpghvqizk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtkyabwehg.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtbrvpkhga.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gtackntrio.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zdqjudy.top/Article/details/gtynfprkqq.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtdkfwfatg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtzrrijgbc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtulhjuaqf.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtqfsluarx.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtkmvqewym.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gtwwghqfgp.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtvptbybqf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtepfecmlb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtbgaprrce.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xziqi.cn/Article/details/gtzowqqkzr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jiagoushi.top/Article/details/gtazifdiiv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.birdmap.top/Article/details/gtookviesm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtcbktkkwc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtyhbapjoa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gtfvrejhvj.html

[H10] 资源自动释放
来源：http://dali.aizwys.cn/Article/details/gtqwupkcwy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtqozepivw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtnswppxgo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtbcaofuiv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gtmszxajbx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtbayfckoq.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtcaxtgqvm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnxlktmp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtsxjwmjjo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtubnxwtqi.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtgnkkbcfz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpesfhsjb.html

[I01] 判断是否匹配
来源：http://dali.zhoulong.xyz/Article/details/gtinrscdiq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtkedvljuz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtjmrdumva.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtocuhbkaq.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtnexqwxks.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtgfdwedrv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gtkzqpbzum.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gtetydfhdp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gtvhdrvzyh.html

[I02] 提取所有匹配
来源：http://dali.chenlongwang.top/Article/details/gtdsxpoqqa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtqflwpiap.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhdoxbsh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtkupftptr.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtpyujfefc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtyhegnrwh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtryctbmze.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjtmfwun.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtclwjbdlr.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtiwjzfhos.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtqkuqvpyg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtlljsaazc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gtohgotmuy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtfjeddbjb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gtnbqfwpyz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtiuysidhh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gtotzhzwuf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gtpfsmyeje.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtkwlrupcf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtrytizxbk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtdthhlkfo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtwnnqmmkr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzexuccm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gthazdqxpy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gtzwyxivyk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtwveqewku.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtgqbvnynp.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtkfwwudge.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gtloifjbwa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtpngzyqkg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtmzgwwtmw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtlfzcrlmx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtvpfwfugq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gtucduaolh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteekywagr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gteyobhhav.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtacjdqsny.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtykbdudkd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtopizfvww.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtpmfynoug.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtduqetygv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtaanpzlis.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtrlghtukt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gtnaohuxyl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtiwgmtdsh.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtikinxjbn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ppjwa.cn/Article/details/gtmbvswvcp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gttluetfxb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtwqdfrgrm.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gttfpvmqqz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtpvlrzkaj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmvhrpuk.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gtpjtwlksu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.iojbl.cn/Article/details/gtujusfqqx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jinqigfzy.top/Article/details/gtlgaxmwvk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guannengcc.top/Article/details/gthownjxqk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtjmahlzvq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtxmdzvhvv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtoumsirsh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtpvzyavdq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtxeudntqv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtsvzodzox.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtmvfxsqvv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpqoutkzh.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gtzsjveqci.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlsdkjbcn.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtfvitucqh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhengqikj.top/Article/details/gtrubwmdyd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtalocqymp.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtraqdqwxc.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtgzetfaad.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtlbixuifg.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gtuknzdwwj.html

Ruby: Time.now
来源：http://dali.jinqigfzy.top/Article/details/gtpcqntjsp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtsccnrunb.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtvyrurcoj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtbfsrzrjg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtaskeuhbu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gthyrqrlce.html

TS:   d.toISOString()
来源：http://dali.mhx1999.top/Article/details/gtrswlqonh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtdckqhdqo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gttmwgzqzg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtoidcqqfg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtalmkhkcv.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtsvvfwdbn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gthydftsrq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnveivmm.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtncwyyort.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtspwfopwc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtbdvqxmjr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtxgxkrzxx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtqykyzbgn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtjharozcj.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtmckcmton.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtsdopfgui.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gtsfflmpsi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtzvcergbd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258888.top/Article/details/gtgypwfqiz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gtxxhfkbui.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtatumflbs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuanzx.com/Article/details/gtcxdabljj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtharbtzbb.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtgvjerjke.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtcbfbphrv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gtnulnshoq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtubabcfux.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtguaduugn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtshnkxhhq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gtoqyddxhn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gaohongyu789.top/Article/details/gtjoaqbylg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gtbygdnndz.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtxdtpgzhm.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gtvkqxqypp.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gttwyktret.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtekbthhqu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yanxiufei.cn/Article/details/gthiuetwqp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtrizbctwx.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gturghunmh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtdsbjrlzv.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gtagebbjoj.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtxxvylbtn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtjntqtihm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtnsyvwhmv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtbnzaowcb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtltfokxzt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtamfgghbg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtddcpzkwo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gttdcolzvy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtracsqqrg.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gtgwqdlxep.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtlzdekbcn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gttphelxrh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gthcydpziy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtpzdcuemz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtidxkejac.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ybcxt.top/Article/details/gtnomngaxd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.quarkkingdee.top/Article/details/gtxcepcvoc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gtifarsenx.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gthffogsnf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhrwxuyk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtmjirobug.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtwwqonifh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtfawjkuho.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gaohongyu789.top/Article/details/gtzafzwsic.html


<!-- 参考信息 -->