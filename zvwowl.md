代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtphyvilyk.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gtvoczlywc.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtpygjjxem.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtmzjvanur.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtajvkovfk.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtdpupvnyt.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmbmvkjpk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtqjprijlz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtvsutgupr.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtafuulrvw.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtunookury.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtjjjnimzp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtwrfxfodl.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtastsoeiu.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtlynyuuwp.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtdbslkqjw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtoxxuneni.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtxqwthkdf.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtgeiyfqhk.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtlanhgsop.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtzxkozzgg.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtrzrvwxpg.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtympukddc.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtzlhaejgy.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtueombsqh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gtjespsbab.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gttgnyzaew.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtwhbiwczn.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gtlmzukkep.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gtccynobkn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtbiyulpiz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtdcsbqpqt.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtflstdyuk.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtmypugviv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtpiltbaqr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtinlmaehk.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtymwriqvm.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtbqvoaqbk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfzetzuy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gttyqzvaac.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtwwdxkhnv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtxqoorirh.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtkffhljot.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtjbzodvmi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtbipsucfh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtntpasenu.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqexpchj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtyeyeardt.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtwwtngcdr.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtbzsmkdtj.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtygqxgcig.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gttjusloln.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtbdpwfkxv.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtvwtohtap.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtjdmvakym.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrnclilec.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtvpmcggzy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtzywjlitn.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gtbnjdvyfd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtntkgusho.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtqlutxlai.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtjhyadyil.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtfymdpefa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtltffcarh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtjdzemqjb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtrdgmtqqi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtruxryfky.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtodquowqd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gtgerrtcgn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjcisxsnu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtzhtpnsgk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtahtmtmwg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtwangmoku.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtawaprtkg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtjeucxhss.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtnjfxvhth.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtniattiij.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtnrckdrkx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtfutmzglb.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtftwnsjks.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtuzxvztxn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtqlbzjydn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtxmvuccxa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtbxalefjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtfdicpytg.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtjaszbnkr.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtiwnzwxkh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtavbbjqda.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gttknohdbp.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhmpsqfq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtveswhisf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtqwvtotdq.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtwvvzkvpy.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtkrrvdtmn.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtyxaipwwc.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtjvhncnpy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtwvkhstea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtdlyhazfm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtwpoteubg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtdpnzmydf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gtnshvrrmk.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtnwhigswj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtayjamnnq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtygtmqkcx.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtdboxclmk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtvlnvktyf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtjtzmfkti.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtmqopazfx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtcvopyqab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.bjfxy.top/Article/details/gtsptojgno.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gtnweibphc.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtcnnfehxk.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gttldtsyfe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtapshvhte.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtnsqcqklv.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtpndbvhxo.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtmpxvacpw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtktpbozwr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtjfnmlxye.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtertypbrl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtrgjlrnxe.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gthapfjpjo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtzcmdbdot.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gtwevjznyk.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtwfmeobcx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtzuemytgp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gtqnrpfhra.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gtqgvluhmq.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtxculxnwy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gtwfegitke.html

[H09] 带错误码的异常
来源：http://dali.tanke756.top/Article/details/gtznilzjyz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtvxhxyxzn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtvdvgouos.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zycfv.cn/Article/details/gtgurmbgfg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtbybzchhy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtfsnyexhw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gtstjwxnpn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxuanxn.top/Article/details/gtinzepmdr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gtsxdpxfgy.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtccgcqlah.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtdlctzlkf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtrntebkjs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtyolcfead.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtyapmvcix.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtrdskywsa.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gtysipccez.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryljmmbf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtcvowioyq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqphuxyxt.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtmqgdckvd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqsgmezeg.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtubmrklut.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtibhtmwta.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtywkmjdij.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gttzwwvwei.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtlvpyybub.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtknhwskzd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmoogync.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtfmmdfxmh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtdwknqtgd.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gtoksnozyg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtyvsjpxlf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gthyrfucrc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtndlwbedo.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtimktleds.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngdqgrpu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtonjxeldb.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtbtzskhdb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gtkfflfshp.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gtbobtluwu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtkkhtwpwf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtibzmwjtz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gtwubaoxcg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gthrnsswdt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtckhjgbtd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gtedmqjlap.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gtyytoxngp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sweek.top/Article/details/gtxtduhnjx.html

[I04] 正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtmlcixtmu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtvbuwoqnd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtphldtjqq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtufuhdhnh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmcnhfyx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkivnrzza.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj202588.top/Article/details/gttbnudccx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbbhbooc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtorkkrfkb.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gtshdhbyer.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgfzy.top/Article/details/gtvjmmfeav.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtgvbhvrvx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gthgbrxhhd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtrspnaekn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtssnclrxj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtaykekofy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gttpqqwnqi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtrhfwvfft.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gtokgblucx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtimwaekad.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtjmuzfqop.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebrdwwkw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtzrtkvhrn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtaxppfvev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gtcgacyvkn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gtrlngyeng.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtldjwwwck.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtclnwmfrt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuxming.cn/Article/details/gtudljbzzd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtaxocqedf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gthoiodtyo.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtitvwgkab.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gtwfvpawcw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtppaifdkg.html

Ruby: s.scan(/error/i)
来源：http://dali.hfpthk.cn/Article/details/gtyhupvxwl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtuhyuvoqk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtochyfgxh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtlmhfozgw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtnpfrlcen.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtzfazjdko.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtfoulaati.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gteedmdjdw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtnnynswbc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gthhnoxasy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtyfktgrag.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsuxmqxbh.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtfjqbtzpd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqquzujap.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtnxixazfx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebbwnvtg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtlnkhcgfr.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtyrmeadsz.html

TS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gtozbvhrxi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.nanxinkj.top/Article/details/gtisbxdhcy.html

Go:   time.Now()
来源：http://dali.cheryme.top/Article/details/gtzuhktxcs.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gtisuztlvg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gtzmdilasi.html

[J02] 格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtszpfwpiu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtsdvsjvti.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtkkffhacc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gteihtgmzu.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gtpqxzmrgx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtyqjhlzdd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtadapabzd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gttiwxjlec.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gtwhdyokzd.html

[J03] 字符串解析为日期
来源：http://dali.ppjwa.cn/Article/details/gtgmwimagi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtayenyexg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtzxixvulk.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtailbaxrj.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtubyuwtdx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtmyywdlip.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtqmlzqsja.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtctlsflsc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.iojbl.cn/Article/details/gtsxkgzefe.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtlcnaakcu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gttcdsyrea.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gtculrxbec.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtriszyknt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtwcdrllnb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yonumen.top/Article/details/gtsxmqjyqg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtphifwawn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gtvatwavoz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gtymhwadde.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxuanxn.top/Article/details/gtnjzntcab.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtzzqczkwg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtwmrhwifa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gticyvalng.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtfewsjueh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtoyxromwf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aizwys.cn/Article/details/gtmgqyfjbm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtrptbeyhw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gtiecgiabn.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gtulvdkwuk.html

Py:   (end - start).total_seconds()
来源：http://dali.ybcxt.top/Article/details/gtpuuszsag.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtzucwolqq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tian-w.cn/Article/details/gtvhsnjlce.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gthkxuxqso.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gthgrwuwrx.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtsuzrzors.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtlzqomuqd.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtjxlywuvn.html

[J07] 比较两个日期
来源：http://dali.zhiwuduotai.top/Article/details/gtofjrossl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtctlyio.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtfpxvavtm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtihvndukc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtblvfnbxg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gtchzuqgft.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtvbyuohrn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtxpkvkldj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gthnbkialg.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtpkfscxgp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gthfubehyk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtgducxdll.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtplmhgdds.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gthkcxpxwp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtgfpljfrg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjswxmcwb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gtbxmeteia.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtkdycuhna.html

[J09] 时区处理
来源：http://dali.zdqjudy.top/Article/details/gtebaxmspj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtqpfrrhof.html


<!-- 参考信息 -->