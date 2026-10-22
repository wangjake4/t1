代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gthceotujs.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtxelausqy.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtkugnsrmb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtuxkjdpzc.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtuugzeqsf.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gttnvflvrj.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdfgzxyl.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmbtceis.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtauzjjpej.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxpkkrqg.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtsewwsjbp.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtluigjzge.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtyhgninxo.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtkafcqseb.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtxncnufnr.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gtxwtogepb.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtaesyelcw.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtouidxqze.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtrmelrfif.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gteclwjdsc.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtacwacnlk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtccebkssz.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtnzgzvnwv.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gttjugqdfn.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtgyggkvbs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtncwhdexq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtdjqfbeei.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkeuubaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtatotyqay.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtezzvlyhi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gthfahgcjz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gthkdizaot.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gthhkgujqv.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfduijzej.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtpecnlymn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtnssyovmm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gterzgjkjk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtaelwmvlq.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gtnafczngo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtmjvicovn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtxoysjxza.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtqhdvjeqi.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gtpjuqwvli.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtueqifrje.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtzxvvlzdk.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtbhelgbtw.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtqndpghhi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtgqqnprpp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gthfdhnrgu.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtapbbegbu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gttdpifigo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzfdpwbzi.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtyrgtfmzs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtubwvrbei.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtydnbczfq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtbnsnylac.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtlcyjmokl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdtspzcr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtqqdkhsbr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpncbvbjm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtmdfptzle.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtptddtttl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtmapibini.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gttvzexcow.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtqwpmuems.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gthlhqtbzm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtoqxkfhze.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtujdqweti.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtlxgbrwyi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtvhzoovhs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtappkqwgb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtqpygybth.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtlrgytqtp.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtmznlaqwe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtvmntqvao.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtnosiyopo.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtwmyugsum.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtfcffafzk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtaqkpqkgl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtpsixnxii.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtgqfrzluw.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gtfynqbkck.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtjkysjmsc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtieegrvir.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtlkhstbfl.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtjsicegev.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtxaafarcj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtampftvel.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gtkwgcsuwz.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtimrqaerf.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtkkqdvyat.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtqpczmyho.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtrstzdoqo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtweyouzyk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtlkfyvyrm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlxyupct.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtghjbjpvi.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gtbbskcuvi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gttldsdwkg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtpiwmxcnr.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtifonjmie.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtprfyhlou.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtyygiuofr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtketlfpnx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtavqqclin.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gttjaeioer.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gttugmzczd.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtxyngonmd.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtchfjjfzq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gtttskjkfa.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtegxrskbg.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtytqjtetl.html

TS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtnsxwflyk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtswawsnsy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtkrxfbjeh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shzxlz.cn/Article/details/gtoarlxzvc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtafknbdpg.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtujxfpiuu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtwenbgghy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gtjhsbqdjr.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtvmzyumhe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtomppmfdq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gtjjorflxn.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtopqpmska.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtdkiocdzx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtxrkypifc.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpjweyvi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xylfe.cn/Article/details/gtswlgcopb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.svipenyu.cn/Article/details/gtwpmeqriw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xinyue.icu/Article/details/gttdztsbgy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gtetvdkcqk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtsjpqdynr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtxyvodtuw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.316326.xyz/Article/details/gteluasyzk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivjmnnpf.html

[H10] 资源自动释放
来源：http://dali.pengpengdd.cyou/Article/details/gtrjllrzow.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtbgpdexos.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gtczjgiwmv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtnsacdqwe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtyhcdegvh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtaxjzsaqe.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtetvurmoy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrvtyipc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtmyiurxug.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbomlqaug.html

I. 正则表达式
来源：http://dali.jiagoushi.top/Article/details/gtnwdgzwwl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtuixkuiiu.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gtxyjwsvux.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtuwzoayce.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtravoqeqz.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtyaivzacw.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtasoddayv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.quarkkingdee.top/Article/details/gtjmqpvuot.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtublnimhf.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gthaldfglq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtfvkfmboq.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gtdnurzlvy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtchrwswwf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gotoacloud.top/Article/details/gtquiosmsi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtmmgyrnkv.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gtvwlaceya.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtqnkmbkav.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gttjdwzlhq.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxypqaoq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtwvkxscxf.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtrosozqqq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtfubyvciv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gtaycuekem.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtedoxxhuk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtnxeoghkz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtebwlhsgd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtedattxya.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtkcrwmtrc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtwcpspjrr.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtpvkautsz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtsweeqowg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gttilqqnku.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtqjkxatsr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtozdbyjcp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gtzxvhlqrx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtxppvkvjn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtdpoinxyh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtjjokaott.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gtbyjsxefo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtocyazlzk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtakqrncql.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtzfaagfqc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtitsjeyml.html

Java: s.split("\\s*,\\s*")
来源：http://dali.smart0.xyz/Article/details/gtdsgepjtf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtghehhtxp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gteneqcdwn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtkupdjpem.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtpoikluiv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtsvjgeork.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gtdocazmrn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtpgudzdhg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtmfdiknmm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gtratpnhlc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtgozvfbho.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtsomyzpks.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrcsbipd.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtwycgdhjf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gtnpcweyhe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtmwwfquzq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtmnwkybwi.html

TS:   /error/gim
来源：http://dali.birdmap.top/Article/details/gtnigvjwwc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtzsqhtahv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigufen.top/Article/details/gthxfkljkf.html

Ruby: s.scan(/error/i)
来源：http://dali.xuetiantiany.cn/Article/details/gtakcgcadv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtvymluubu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gaohongyu789.top/Article/details/gttdzgsshr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangdashe.top/Article/details/gtbrfkzkub.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtkrmcbmcx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gthwspxjdg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtpfefdnoh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtpfrqqiyb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gtqarfqnao.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtzsudmzwg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtgpqtschg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsiaeemkn.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtawlexnbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsayoxjim.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gthexnxvzo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtxtsvpmsu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtwiocjzce.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtsllkdpab.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtarykboda.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xziqi.cn/Article/details/gtsosfjbht.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtbgsjolyh.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtyspoomvw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtgxfonniu.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtyaqwxgxz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtlbhbcusm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gttixnhskb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gtkxvxywfs.html

TS:   d.toISOString()
来源：http://dali.aibaodan.cn/Article/details/gtlalyvgrr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtwwtfokcq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gtfevriunp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvupoyxvc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gthmsuakuo.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtukvbqugf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gtiuiomwkh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigfzy.top/Article/details/gtoxtbbkhv.html

JS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtdhegdoef.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtwnwcwkew.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtrbqhbrqr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtixvsxkmy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtdpwmwzaj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gtscujkiht.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtmzwigqzt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtocsgldhb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gthvzbcbuw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtailhvxah.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtdzvlgpjr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtujpxigto.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtuqgvsdfw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yangfankeji.com/Article/details/gtxhmodkxi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtxyybsrpo.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtwhnizhtz.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gtoighjuen.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtkjvbvzpb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtpirzjawu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtvxtxqldw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtrkyapwcr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtxmcchaiy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcgqqkfm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtrvnkthjw.html

[J06] 计算两时间之差
来源：http://dali.jiagoushi.top/Article/details/gtujclolle.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtltvfijgn.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvghdqzew.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyyyfesg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aibaodan.cn/Article/details/gtsydcyial.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gtitgcwqdc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gthojaymmb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtnlnkabvv.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gtcsuzlopb.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtmbdfkoyi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtzlfzawvi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fzhhl.top/Article/details/gtuckpnfoi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtatplcslt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtneinfctb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzvlntdtx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gthgimbrqn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtbcjwscli.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtpxzwtiyi.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtvbskltcl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sxryk.cn/Article/details/gtyvccnete.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtfdxanikk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jyoumei.cn/Article/details/gtidgxnumt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtpxzyglur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtwcwlwxym.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gtdynufzks.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pycfn.com/Article/details/gtszqlygoc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gtyiexzcrl.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtfonqhwpj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gttwrpojck.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwrpdogb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtvzlhsdjp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gtxhsmzuun.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtgfqjpazj.html


<!-- 参考信息 -->