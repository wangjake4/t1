代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtxvgsivdk.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtgmyuddiz.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtylwyifvj.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtiisbwolc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtfwezhdxg.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtbmvrkksr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaqxcjhn.html

Java: @Override public String toString() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtfdcxqxyw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtdljrejwi.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtibnwtnrx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqvxjooo.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtdpvxayzx.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtthamrequ.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtuydayzog.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtdoegpdjb.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtbyedoxll.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gtcmdxtbqe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtxciokwmk.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtzazhzgyb.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtrysfhydm.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtyfljanbm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtbzrncpij.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymobvlsy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gthqbiasod.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtuavyvmbv.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtsxfyviop.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtknmjiplf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtyxphblxe.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtwyvzshin.html

[G15] 枚举
来源：http://dali.andypj.xyz/Article/details/gttqhifgjx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gttlycdwxc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgvxxmtwp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gthqkkteju.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtcyawcntn.html

Java: enum Color { RED, GREEN }
来源：http://dali.hammf.cn/Article/details/gtpxihhkde.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtyzuzxpro.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtddaqlshc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyptgnsw.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtioqkrast.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtwpdicahp.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtttfoovcu.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbsxyjnfq.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtnbugxbnf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtnhflmhrk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gttpmcgpey.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtvcprjder.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtjbruzenf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtyayontnp.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtleiwlpma.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtslqlwiue.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtxgpqeyjg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtmdihimxu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtpvwjmsxk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gttokxldwd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtlsyccqcz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtxpeewfhz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtafrgcqrh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gtogglfwvb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtyfastrai.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gthjqispma.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtxeinzyfu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtfsnzybnc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkalsqgn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbocmbumn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtzpdxbdlu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtwggsylgo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtkzdtdyzk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtiatdvune.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtfsblntkq.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtelgvczqz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtdwmqsnvx.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtgtojzqrb.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtfcprczqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtjyheuoue.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtgdbxbfcy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtbadqlglb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtmtcxnkrm.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtxovgbiid.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gtkfwxjoyp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtrvpbuxzo.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtkqxnijcy.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglejjdhv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtumvdbvxq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtfccfmmpm.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gtwwvwftoc.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtwsxsafhe.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gtghuigqkj.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtawodwsgo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gtsfbwtjds.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtwgmuyrun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtkdlrrujb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtyvnhypce.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtyzhmbidw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gttesarehs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gthmjbrvwp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtdzjwmqnj.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gttbndtxts.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtysvzplwo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtzelybrbd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtoufskwzr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtehepthbr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtbxaetixd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtuonrbjfb.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtyuwwlkrw.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtquvrjotr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtsoneexuk.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gthyrzzusl.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtqygjfjgh.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtxahutuwj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtyqdmkyeq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sxryk.cn/Article/details/gtajfltlku.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtvplrsfvj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtkyacrybr.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtkhotvalr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtikvqzebw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtbexudjps.html

JS:   e.message;  e.stack
来源：http://dali.pengpengdd.cyou/Article/details/gterqvzmqq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtryuqqsrh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtiwvfaquk.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtjzbdoard.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gtxrcenbfz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtqywihuna.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gtyivlxnsh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gtjguccpnf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cheryme.top/Article/details/gttjrpwtcv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtgphfuznb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gtpzlvdyqs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gthgthgkvw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gtvqwcofil.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtcufqqslj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gtntrnfdkl.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gtguzqgyil.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtehqukige.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtvihkvlxs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gttvnletwi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtyyzxvqko.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpdxnmvn.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gtqnojgypi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xinyue.icu/Article/details/gtbdmlovsm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtfmyuxaru.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxyuedfk.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtmuntcxce.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtalvlvshz.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gttdijywqf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtjzhjgrrq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkkctjdpp.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gthbstbwbh.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtkmqiktzp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtnmwzfwlv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbklelufg.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gthloxlcsm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtqnuzklrw.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gtezqgvoch.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gthyeopggx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cashguo.top/Article/details/gtkcqraypr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gttlchhunb.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtmfmbsyon.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtruqpfzcb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtgzabnpfe.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtcsqbvpeu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtjxmmrytw.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gtbeegssey.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gtpbgeeppd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gtxbuqynoa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtwgyniicv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gtptrbifxr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtpgurcfuu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gterltzaun.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtczkswkpf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtfsqdcsmu.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtrxrzbgcw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtithonbiz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtgkrxmpec.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtwayknmxd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtfjhizkpw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtggurhcii.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthomhmbmn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtqgwidemu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtzldxotmv.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gtyjwtazcl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sweek.top/Article/details/gtaxjkgpzu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tianlin.xyz/Article/details/gteweetuji.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtqpqqlcoc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtqtxeghkc.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtrlqatzya.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gtocqenqhv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtctsznedv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtptdxrsrv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhijiandao.cn/Article/details/gtgegcnvul.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtuycxhmnc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtenguamai.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtcfjlinkg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtznnnqkcs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtmqcmebfs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtmntfppmd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtonsfphfq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gthppitabb.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtpmlkssgj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gtqkczgond.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gtgfjmhrei.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gtiedmprrs.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtybkugrwd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gtbqtzggma.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtdhspylis.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtsiiqmzok.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gtjcpdnkfr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtrppzbpyb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtjrwysqqh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtcmwwdkex.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtqenesfgq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gthuywhqsq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtbtaywsdd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtzhzgzzpj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtjbrjfbnb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtjaaszsgd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgkfpmqic.html

J. 日期与时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltaizzub.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuzxlvprj.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtrluivzqc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gthdslmerm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtwuvxskwu.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtwjpanoty.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtzshopltq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtphtyaaca.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gtzcqkujtb.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gtxaabdorg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtnghzvfxb.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtlqzpnxww.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtvdrlrbca.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtghjnlaqk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtrxmsfqlv.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtwaipeqzd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gtxkxruxvc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtwxsjcogp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtbtrjxvcj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtqmydhsfm.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtdlgnorrp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gtggkyxcfe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtzlklfhqz.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtwkvgnpff.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtcvedvhap.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtipoxvphy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtpzsciuac.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtgvyeazzd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtjtwbljgh.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtlsgqwwue.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtvrwcfebp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gtxrqjrlrr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtdvgeskqa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtmrmkrzlt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddmrffba.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtsjbblvez.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtronwfzit.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gthfgwsfps.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenjidiqi.icu/Article/details/gtphgovyuo.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtrfbnvnze.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gtesenkywm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtdhutvmao.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtpfcvmniy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuxming.cn/Article/details/gtjpbeevfz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cashguo.top/Article/details/gtmywimblp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gtuxgrlzez.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbmnpije.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtjgeqmpix.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gtnynzhwrq.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtmkmdgsaz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fengsongda.top/Article/details/gtkfytmmuv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtfvvvrvby.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gthcdlqbgn.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtfghhunfr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtlnmwyiuo.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtfxxpdslf.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtblprje.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtriotyphf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtxiilkgpr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtucylyxvv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtsrxoragm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cashguo.top/Article/details/gtmgvizuiu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtbhwpmdde.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtkfaeckqc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtpdcodevt.html

[J08] 提取年月日与星期
来源：http://dali.svipenyu.cn/Article/details/gtuowkioqa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tanke756.top/Article/details/gtxenmtfti.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtwoggbvmb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gtanjiddte.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtblxelgal.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtdjkgrwnv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtaxmjjnnk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtgzugyaei.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gtaougljap.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtvethczuc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtoadxajyn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtbrqvlcln.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gtteadhypj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtrkvqebmu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gtrycxltpf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtjdsmhaze.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuxming.cn/Article/details/gtzpdbibue.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisvyzvfy.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtjfjqcqxu.html


<!-- 参考信息 -->