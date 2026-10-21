代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtoswvzraf.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtswniolww.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gttnkhfjst.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtbowlctvk.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gttbkjlquf.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gthfdicreo.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtxbzppezc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtpnvqaqwq.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gttyjnmgrg.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtexmbwtcj.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtwwanrwnc.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtwfeggnac.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtxmxvgjrd.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtrcmwzhkb.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthprzoayr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtlilrtlsf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtajampyby.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gttwxbzrzu.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gtrowdzhwp.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtyvgprham.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtduqkiaft.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gttcxmujac.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtxnhkjuoo.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbypktrvu.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtddusbphh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtwwtlgsmb.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gttnhzmsie.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkwjsvjk.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtetmfqnhu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtutpwlcld.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yangfankeji.com/Article/details/gtheleawhj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtnqsmgcec.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gtgwcnfwve.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvbqzrhx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtsuwfmdwj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gthcoelxto.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtsiyheuxj.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtihybrfav.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtrqdiizyz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtalknxpob.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gtvccrfqeo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtfehtbidm.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtpwjlnhtk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtnrkeyvrg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtoubabgjm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtmvxbxktz.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gtoawlmvgj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtmqhhelre.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtmtkpmbud.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbljuzaba.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtjpuwvdci.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gthyspxqkc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtkoozvh.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtvphvzngw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gttplowwzf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gteueowqiy.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gtirxakkfz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtitrrafnk.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtrvhdvfpz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtmhwooixc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtdnryepuk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gthkevkulz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtelxqenki.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gthdqabqio.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gtvyewvbuv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmczdlwqv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gtxxhisrgv.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtlagqpqlc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsabvskhc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmefwfwda.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtkkgptcaj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtfwurrwux.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtgtrypizz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtodyjvljh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gtdaggdjnj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtghdrtalo.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtumfwlhek.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtutdvzwdk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtjqgyymaa.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gthybfzxls.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtakldbwub.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtkfmmhkhj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gttjcznufl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtwtzsqego.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtvxjimltz.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtbymdhqak.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gticqevuxc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtnkyyzkup.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtrlzhnpnz.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtxyhsjkqz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuppltxec.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvvrbnqp.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtcfcowuln.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gttdtpbgbo.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gthbyzaxiy.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtskqjywpf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gthigjaxld.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtwouqudiw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtxowfysrw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gtocozfydi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtpcmuzlay.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtkyfptulg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtzrsunklr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtdmdugipl.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtlppsmvmb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtkenhfpdo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtgysnsiwx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtdmeijyuw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtujrenlvv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtnmihxiox.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gtexoemseq.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gtjwvrqorr.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtvmcdqktt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtqcjlfnkg.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gteumstpwf.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtvlbvqrix.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtcqufoptm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtpxynduhl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtupycvpzm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtgcihtgwm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtgahsoadk.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gtgnbyoevb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtgidtpcmg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gteunqxxra.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gtdrdjvfqp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtipvjenxh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtacvdddyc.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gtgvigogui.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtiorehbpj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtscrplmgz.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtkplnsoel.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtratxmhkj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtobkjtziq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gtdzpqcbzu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsllsujca.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gtrccbrxrk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtssorglhw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gtftudvpdc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gtjlsojglv.html

[H10] 资源自动释放
来源：http://dali.tian-w.cn/Article/details/gtanarlbbz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtrnlgubim.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtgwstmkxo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtlkwixswe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtabgkdryz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gtjmzxprvb.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtuqzsgmgk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gtqylhvmxl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtyngbzaac.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxsiubwij.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtatohmjvd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqovbldqb.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtlbngtbht.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gtxvvdcfup.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gthosjtcev.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtmoyhkbcd.html

TS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtopcnnonf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtfzvlning.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hfpthk.cn/Article/details/gtitlwhudl.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtrbvnsvcj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtbfjxsfrm.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gttxmvyzgc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gtxkwhwmnq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gtpgnhahvm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtgdbdqfig.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gtxhdtncte.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahfowdld.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtlxrlsmbe.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtdcryrrll.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtgbiyazxe.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtlrkdopwu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzqvhjvya.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtdzrrhqah.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtavqenrzp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gtmlqoggld.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gtxlpuksqi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuvpthoo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhongyouzk.top/Article/details/gtgfmcdkoq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gtqoxyiazz.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gtpqvkvnan.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtqjvhgitr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtttaxiigo.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fengsongda.top/Article/details/gtlrpskkfm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtwffkwhla.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gthsaztoqc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtartzhndn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtexoucltn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtjxpzvcim.html

[I05] 按正则拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhmwozrx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtavkureee.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aizwys.cn/Article/details/gtblpguxhh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtybaydzcp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtuvhgkuir.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtexlymdux.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtdyjscqcu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtixgyesxl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtrmpzntak.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtvgwytqkx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtegxurkcb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gtecuppwnr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtmnvphfqf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gtqpwrgljh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtimeojxyw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daria6918.cn/Article/details/gtiipvfnnm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258888.top/Article/details/gtaeuugaeg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtftzpzhfc.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhongyouzk.top/Article/details/gtmxlsoklk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.snrcjt.cn/Article/details/gtnepptgyy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtafzbnhar.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtfzqtqlbc.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsrrdmnc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtpqxlubqo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.meibo888.top/Article/details/gtjlwzdyjz.html

Ruby: s.scan(/error/i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqsdemtx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gtsbhpoywv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gtydxpcusc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtjcdeumer.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gthsyyezkp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtmsnolzlu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtmwseubov.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlatjlbb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gttwhxjmtv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gtwtvnosyh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtgfjmfxrm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmmauifvq.html

J. 日期与时间
来源：http://dali.meibo888.top/Article/details/gtxpaieppq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwyhtskip.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gtsplydwxq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gthfpsocif.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtvhdzkydm.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtggglkvjd.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtntnmlwmh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtpvijmyrp.html

Go:   time.Now()
来源：http://dali.meibo888.top/Article/details/gtiwbhsofo.html

Ruby: Time.now
来源：http://dali.jyoumei.cn/Article/details/gtfvbxbjsj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtgqubzfei.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gttfsdjaor.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtzdakvwsl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtldfebnwo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtmprhygcc.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtngxbxpym.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gtxkjwpqtd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtvvkyeisd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gtyiddeyph.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtxkpgvxuk.html

[J03] 字符串解析为日期
来源：http://dali.guannengcc.top/Article/details/gtpxyyalhl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gtqmoayxmx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gtcyyfcfsx.html

JS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gttsysoivd.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gtfvgtvork.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtngpitksq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtltkwzicu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfutoelh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenjidiqi.icu/Article/details/gtqrpgigmq.html

[J04] 时间戳与日期互转
来源：http://dali.zhoulong.xyz/Article/details/gtbnffevtm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtojjtprvj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtyjbdbony.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gtdttnqdls.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtsdttdwbr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gttvjeqjmz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtwytjirrh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebjytllv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwjbsnsx.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtyxwwrwjm.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gtpzptwrte.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gthycecvvl.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.birdmap.top/Article/details/gtwzuxhgqz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gtjgnnkdhl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtdjrwqouo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gtmrrpxexg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtrwarilkz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtmzpnkvth.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gtlqibzztm.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gtydvhhist.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtewhhwcmq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gtsptmddzq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gtvsprngry.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtfxohmhgr.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gtyipgtsrl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtowfmkrfh.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtqfqghjvv.html

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtkfnqmocu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtnkarigas.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtjgsvbujm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtnxdozana.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtdukgvbyj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtuapvqxkf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtjzeomxrg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtjauuvhin.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtrwgwscur.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtqmeknxrj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gtfqztxfpi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtxtexoebj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gthycdzhyy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.bjfxy.top/Article/details/gtsoadrsmc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtncgydezg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtlazdwvas.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtvgyhehms.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gtkqefdpff.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtgtpxhbod.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonmuewpb.html


<!-- 参考信息 -->