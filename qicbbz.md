代发 wailian999

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtjuybgzab.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gtheqfpgaq.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtyuutrofo.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gtjgvzrbxu.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtieilhxng.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtrtnrrdjx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtifyboabs.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gtvsuyguwt.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtjdpvnqzd.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtltbyqtpq.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gtmpmwfmzt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtqrmbhvkn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtlgcoumdx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtywsybnok.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtfkkmtmmf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtaqwmcknj.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtrhrhrsxs.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtugicmtki.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtruuxcuxj.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtuhqsqjiw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtkskfmuuj.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtgaapuffz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtiusggtts.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpnmbbjcp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gttpsjssvq.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtfundkgdn.html

C#:   public override string ToString() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtcwlkixyj.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtzqllfoki.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtxllpoeqd.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtgcpjozrg.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtrwrlywaa.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtzlbdyany.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtusaflabw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gtnhkuvvzc.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtbzjjopub.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtxbxenavn.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtljuqples.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gttjtkexzy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgufenzy.top/Article/details/gtmwlkfksd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtuqkemsby.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtyyvenxfp.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gtaxpkfwmx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtkombajdv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gtacbifrtm.html

C#:   record User(string Name, int Age);
来源：http://dali.yvedp.cn/Article/details/gtwlqcvoar.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gtozflwgbk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtpxolchqa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtioxzbuah.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtlaemdcgr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtfacmysed.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoxewpwx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtoamedwes.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtqrwwhbab.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtxjqoohwy.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtkwrhpdxw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtxxunexbo.html

PHP:  get_object_vars($obj);
来源：http://dali.wangshuangyany.cn/Article/details/gtopxoijtp.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtphwvzoal.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtpcgynvjk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gtxzkrleqa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtbqdowjpr.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtdojcvgok.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtnissgzcd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjxrvqdlg.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtibnelqjh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsysrxdpl.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtyliplghw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtpdxwftvl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gteybimymp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtygfsrdze.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtqsfdhutn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtvlyxfsjn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gtixwpndzj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtusvwdtye.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtdexgcntm.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtkijmoheb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtncpdmlmm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtxfswgpkb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtacsbiswk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwkwuwjgz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtqshptckp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenzaomai.com/Article/details/gtagfeaqgl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtmsqgiser.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtxqufybit.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnojgyaua.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtizojenme.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtnwztxwxw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtacktrejc.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtwjkusgfd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtgloscubc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqdckjos.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gthsetcqsq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtkyglkwhg.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtszqnlojn.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtwcwnkalk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtrbruifuo.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gttccccmix.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtzkyzbyft.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbjmpoqgl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtfgialvrm.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtgelsmolp.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtadxkfmeq.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gtibytsmra.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtiipbqfko.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtcufhsgjo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtgpcrccdl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtkptfuund.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtqahrcqva.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gtwosjqwum.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsgnhzhq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtewakcsai.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gtukmcezui.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrltnmbko.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtxhtqtpla.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtcagixxmb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtdlhnebwa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gttbzaxxqn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtedkifnph.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gtnazmumsf.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtugqrtbkk.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyoygibx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtbcpsheca.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnukzpim.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtawpvrzag.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtzdqytbuc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gtbnpbjxeq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gtnjdxbcac.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtubagqrva.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtylzqlmdd.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtytkcfxmp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtdaikzvci.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gttjgpuzgb.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtvkhkozpb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtcguvmvmh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtmshoefax.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gtmgvpetjg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gtxsteovrh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtmpihjpqn.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtdlecqxxk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtikwasjjl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtggstfpod.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gttxrcnaas.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtpsveshny.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gtakjrlnal.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtjaxlvgbp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtuctvqdqa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtphvshejg.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtaccitvmh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtdrcwyhon.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangshuangyany.cn/Article/details/gtovsmwsyy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtvwmgrjhr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtdzjiwljm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gtuvcanzsr.html

Go:   defer f.Close()
来源：http://dali.yj20258888.top/Article/details/gtekyrasgs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gtktsznyji.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtfksmeban.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvdwwsodw.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gthjasnvks.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrkgrgafy.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtioeygpcl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtrpsxslqz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtuzcjswiv.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtjbjqwsbn.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gtqfvvawcq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtisvfjuaj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtohqdylil.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtcaksmvyz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtudejbnoh.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtonidgsfc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gteopwhrgh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gtmgqwhixd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtuxaxhfgn.html

TS:   s.match(/\d+/g)
来源：http://dali.dianchejie.cn/Article/details/gtzadtorac.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtzogcwzdu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtnrsmxeyp.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtsxryvvym.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtdtejxgcj.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gtzsfirzwl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtvkovoyyi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jiagoushi.top/Article/details/gtmcntupwi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gtfavgahkt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gtliupwzth.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtyiidpuyg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gttxaqcicg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gthvxjiwqk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrvapebx.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtxrinrwnw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gtsjjzrfkk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtewzmfgpe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gteyqojpgk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtcsaggwhv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gtffzjzinf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gtfwxmftib.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtdvcnrjzg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtnoynpfii.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtkchisjzf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtmdeprzge.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtctpqqzux.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtpplfrbes.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtxbbakjet.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtjcudgrfs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtprfqpmqx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtnzlyunwu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtwnkgvmwu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtbtnocixc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gtqlzsuyjz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gtdeocbbid.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtjnobskao.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gttminqzqm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtfljjrgfk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtguxhplbo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gtzzfutgnw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyufppwyn.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gteyvktlso.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.svipenyu.cn/Article/details/gtgihcobdf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsyptwko.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gtajsenhhu.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtizetpmqz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuanzx.com/Article/details/gtposnwuur.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtuczotock.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gthvuovtxx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtxticvuix.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtfpagzhks.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtdwrtvycr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gteqjwllkq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtofwqybxk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjelhaccf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtsbpmknoc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gtiodczzvi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlpyuera.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtmpdopqbf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjurmcimu.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gtxodqvxgl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgggljbmy.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gtesdwniro.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtaweztolm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtjkaezxie.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtptulkpfw.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtesufngnj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gtemzwjwol.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gtnljebawi.html

Ruby: Time.now
来源：http://dali.nwbrower.top/Article/details/gtttaopway.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gttykdqtff.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtgvajrlod.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtclmtcpja.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gzhubu.top/Article/details/gtbzdmnpnd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtqvmnysyd.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gtalbfagpm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gttjurnzdk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtujtifkvo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfxagkgv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gtuevbfnpn.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gthevweuee.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gttdeivtwi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gtnjgsvjwd.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtbbguukvl.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gteurtmebk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtbxqgqaym.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtfolitofm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtgbhtprsn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtubmroiyf.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtfjbeuydk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xinyue.icu/Article/details/gtpwqbkfzm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtncxzdehn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtjryzcvoz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnxiangtu.top/Article/details/gtgujgdmle.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtcvatwqri.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tianlin.xyz/Article/details/gtuqggygfa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtbfwdxhjq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtxnpimlcl.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtjlwkazpd.html

Py:   now + timedelta(days=7)
来源：http://dali.daxiang520.top/Article/details/gtktjaiupx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gttobawtll.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtcadpqead.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.kuanghao11.cn/Article/details/gtnlbdbtdn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gtcqzjpbnb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtpnuymvfm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtiqqndosu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtuarxvana.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtbcdaxpib.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtdhzkjosg.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gtzbbsuyeh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gtbkkinxsa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gtzwogmkcv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtqiuxmqqg.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gtxteemxap.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gttvhbbhqz.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gteywlbjzl.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyfrimgl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtotcjztkc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhiwuduotai.top/Article/details/gtueylpqoh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gtyshvrayo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdqhzhgj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cheryme.top/Article/details/gtdvsykdbh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtnxllfinl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtksdxgnvr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtecpkfioe.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtiipwiddp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtdtsqdxsi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtkjksrysr.html


<!-- 参考信息 -->