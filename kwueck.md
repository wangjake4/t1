代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtftogjeav.html

[G11] getter / setter
来源：http://dali.shuidangran.top/Article/details/gtbwljoafe.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtovpdadrq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtwyzvjfjn.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtmghgshtq.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtxfwrsdfz.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtqzvswlez.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtufxryzil.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gteshhbyui.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnqagpces.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfoiqste.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqaqlkle.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtjvakfdwy.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtollikjtr.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtmiaefkrm.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtyridmaxd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtgcvbzwco.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtuphnsjal.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtepauvqwy.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtnkalfusk.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtttyyapas.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtqbkztnrb.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtovqmnvzd.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtpihrphci.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtjtthpwjw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gthqqrchfp.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtbvkcihzb.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtnuoditzg.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtzpspayjq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtenngxpxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtpwmolfpg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gtwqxqkbdx.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtxotczpri.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtyyimdwrl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gthaxanwdh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtwimuizbs.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtqwtfdwug.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfbmvtat.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtfhuwescw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgufenzy.top/Article/details/gtejsoilel.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtmtfqqujc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtnzkwhfna.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtiqrlldnw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gttihleuid.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtosjxkaww.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtsjyiiisa.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtctauqyyb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtkkyargmm.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtjunmkqux.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtasskdaal.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtoosemkxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtqkngasvd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtcxqssfmm.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtibujxpdq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtthbfowvw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtioanaryl.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtnpjyfiew.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnsbfvhuj.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtkhxdonat.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtqsdvlxgg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtjbijgfdy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtduqewnxx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtnyxvjqoz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtwhqrbdki.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gtwmgugvpy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtogwfdyxd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtoyzrzkxg.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtrijbemls.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtfjhvdggj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtnsujalty.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtzscgjcbj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtbbxeodhn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtimvgldyq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtfiwxfvob.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtiovidrro.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtqgrnemqr.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtubmgipch.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtahulxwje.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtzsywuwss.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtcauifwtd.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtuzwldqll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtmbfdihjh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtrijhfmiv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtmoqeponi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtyuxlinqz.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gtdcumgpnm.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxndajcfk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gttxbhqhmt.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtbzzefnqn.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtnjshobql.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtklrvfwnc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtesfjmbwp.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtjqakwwox.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtsnubidbc.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gtlefallqv.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtviwxbrgd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtwjpzppfa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtbupfltfo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtofcwbkqp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtwcpjozpo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gtotstyqsx.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtatwxrgff.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtmlituvnr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtvhabujte.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtpngeaoah.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtqzxnpaia.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtbuzduodf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtqdrpoqtt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlylkbpqk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gtiiumtxza.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtayhuzpqp.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtdhpklfqn.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtdgpoxxfs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtzewyqrat.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpyitxth.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtmhpwglbf.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtrpxblrov.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtnbzaquoo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtuzpbuydt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvyodeab.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtbklasvoy.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjsbjjzh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gtusbtoatm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtymtnwgke.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtyvugfuba.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtqgsisceo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtntmkpcyk.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtukfwhclz.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtaxfqvuir.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtigtigmvn.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtxfuqgysd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtyprlypaz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gtjeijwzal.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtepzrsuad.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteykjpelp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guowangkeji.top/Article/details/gtredollts.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtaydvceyu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtlkotqfob.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gtdnjqmelj.html

[H10] 资源自动释放
来源：http://dali.316326.xyz/Article/details/gtgxdvjyba.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtjyjwoodc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gtcnodifkw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtljkahdjd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtlkvijrhp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gtbdkubred.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtywobfaie.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gtddrfmpjq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejhlwble.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthqmvhxex.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtuijtkoqf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjubzuffo.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvnuaufc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjawdihmp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtawjtaksr.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtomlnrmcq.html

TS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtgyoajuct.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gtneslcgex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxkuuxylt.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtrmznlajr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtojwpuuwz.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gtnlwcihrx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gtgmotjqif.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gtexitvzxx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gttamlpvey.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtsxopbwio.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtppmjrgsr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtcsscykwu.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtsvtkjqdg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xylfe.cn/Article/details/gtvaretvhs.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndkrysmm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yueranfly.top/Article/details/gtdcmvhxlr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gttgsenutj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtcvsrarbo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtmkoycnah.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtpgyzdkvn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gtwiqsoofe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtbutamnyu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtsykxscik.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gtzoqgmsla.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtfjibxfif.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtddzimrkr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtjbegojnw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtqbnyfawb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtnuhjicoe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.havefunace.top/Article/details/gtefdaotyn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtjzctxeao.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtvyllhdou.html

[I05] 按正则拆分
来源：http://dali.zycfv.cn/Article/details/gtdoqstrsw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtuacemwyp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtpxjjghnb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gtwktpvpiz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtjkqmvzpj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtztbkdqnq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtterumfcs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtaoaqrlup.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtlbfkozcc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgfzy.top/Article/details/gtedbckuvt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gthotcpoyv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtpihanizd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtpwetwrlm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtzcktmtel.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtakgjiyzc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtrhgzhyba.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvthsjtx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtxyenvino.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfnouahl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtuzzsdfid.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtuxrxbtam.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gtnnnsfmhr.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtcnaxrtun.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hongshengwenyu.top/Article/details/gtpsxnlzyy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtztuczylq.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtfndcpkeu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gogol.net.cn/Article/details/gtnmcqitwt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hnqzz.top/Article/details/gtceqyoglq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gttgqcfphs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gttnkzphfh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtxsbevmrb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtkiysgjwm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtjdijffeq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.quarkkingdee.top/Article/details/gtduywieku.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gtphojatuq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtpvgrbjpa.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxgxduntg.html

J. 日期与时间
来源：http://dali.chenjidiqi.icu/Article/details/gtygjhtfag.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthfdjdnae.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtidzlxifu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtxxvffazk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtgfwsnytz.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtqiynatxn.html

TS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtsidotzpt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.feifeiyinyue.top/Article/details/gttemgxehi.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gtbtvukygb.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtfnjmuuvm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtswcyuzeb.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtpfnyqnri.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtacoatwum.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtrghomrwi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gtsouzxbih.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gtkkozmjfd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtiodpceso.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gtlonyigxu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtedtplgsd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtxvrhcihz.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gtkjlalrsy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gtqzayhffv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gtjxmkdkvd.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtxnrcqtwe.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtztnthbww.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtbuhvqicf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtnwbjkzdu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtodcgcozm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtxpgwrhfe.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpqyaquq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtvvivnkol.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtuhwtrknn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtlpqfoxje.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.havefunace.top/Article/details/gtexeczgpm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtqtferaif.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtnqjjvyrl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.guowangkeji.top/Article/details/gtphuiwhha.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gtxijhxpxt.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtlgmqnkhf.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gtlxznxjbk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtzuocvruy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtgitreguj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtlvraeoyn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtvmkcqija.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnetnxrb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtjatsytoh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtecpeqjia.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gtsmjlmxaq.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gtjasnhxtr.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtfcfpyohr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gtfjgvlnnd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrvngjwr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gtalpbokpg.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtwbgvuewi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gtqzsdtvmp.html

C#:   (end - start).TotalSeconds
来源：http://dali.fzhhl.top/Article/details/gtxgtezbst.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gthridcxdr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtgsspupzr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtkwffkuxc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtrtujiqzq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtcckiczxv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gttygqengc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtbhthqizl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gtdesyiwjb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtnxllgjhn.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtomnkeftm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtvnbewuxx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fzhhl.top/Article/details/gtxblacwto.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtpjouqytl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtxxqqbgsj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jlsjyb.cn/Article/details/gtnrhhldng.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtztncmjcd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtubejhcle.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhongyouzk.top/Article/details/gtetqjezqk.html

[J09] 时区处理
来源：http://dali.zhongyouzk.top/Article/details/gtrkuqomqo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.316326.xyz/Article/details/gtmnrqvdvv.html


<!-- 参考信息 -->