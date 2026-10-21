代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtwjojcxrz.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtxnjbvjzw.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtjqtfekmn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtsixczkaf.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtddywgdmt.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtrhlqpflm.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gttwsvrmmq.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtoeouzear.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtvunbnvog.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtlzdrfgge.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtjrcyonip.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtiezekwyq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtmkyjrmnn.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gttuxgzjqk.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtvvmkqdcj.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtkaaoecog.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtiooivnzg.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtllmlgudw.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtvehktmmt.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtgurfjhtf.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtiaqaxxgl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gtyfglgewx.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtkjtjmbmu.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gtyzbkjajg.html

[G14] 数据类 / record
来源：http://dali.yj20258888.top/Article/details/gtfnpshucl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtyytjbvye.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtlinnygsi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtoniyffyp.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gtyphdlbuj.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtvwjxuoqt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtpchcrxpr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbiqjoif.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtfglemiss.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtizyjzhkq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtfjugckkt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gtkcxshwve.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptgzqnxs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gtjdynppti.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtbnnmfgev.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtdxhecumm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtjfcghhof.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjoalqee.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtzexmspva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtujgjodji.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtxjovylxv.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtphfggiaw.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtfhwywqvw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkicqesq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gthaobhtwx.html

Ruby: obj.instance_variables
来源：http://dali.jinqigufen.top/Article/details/gtgrdwvanh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtgjxczxey.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuaxuashm.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtokpvcvwk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcawuvjx.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gtczzlcgjj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gthgkfqnbn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gtqvhncpzs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtmzszrgvb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtjlayqeue.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtxyneggkd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtzduabzak.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gtpluidkxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gtvajotuvs.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gthevgiohn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtvrsfjyob.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtgxtdqspe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtehccrkey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtxyhlkdgg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtoeeazhhk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtmhnpradi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtqarzdutd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtkbtnywgx.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtbytcagmu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtvopihsdx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtzffvnpqa.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtuyqjueos.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtqamqbsgj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtjwwllbeb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gtbcfyeqwv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtfpckfwpw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtqpewdevm.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtdypdnyml.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtqgcmypmt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtaykixuud.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtwzkxjylh.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtlpqqpjqc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtojurnmlo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtfyofnaus.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gthzpaqinl.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtomysesei.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtzcujuptt.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gtmxihnunw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtnptdcsuv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmabapclc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtpiloyhqy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gtpvejjiok.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtgiwvrskx.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoybvbwi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcwbzvlxh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtkxjixxxs.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtzxhnagya.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gthsvdjwam.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtmniznjqb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtbixriljr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtgujebzeq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtumuxxcya.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhbrxyra.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtztfuxsfk.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtnpruktah.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtijkvisxp.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtfnlkzfta.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtapfvixgo.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtxivjvcwq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtdahlggba.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtotblxata.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gtorwhkzra.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gttbnhzbes.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtjhvglemv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtojvlrxlt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwrzlnat.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gtujuxynhh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gtyvphhchu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gtcryowvhs.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuczhzsb.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gtffheaywe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtnlckbugn.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gtsgutwujs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtekaqcbyu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmflzaqsl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gtsfushawt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.kuanghao11.cn/Article/details/gtbqjhpoto.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gthspmvtmp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtnqqtijtr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gtoksymnlc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gtldwjdxkk.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gtmzcnmffp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtxnrodkqy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtxncbguht.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtcmtfnjhn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gtnbxkuxek.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtudfcpyor.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtxohwuuos.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cashguo.top/Article/details/gtcetgtsgm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtjjpacopc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdjaaxbxc.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gttsxfoniz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsyvkvfvj.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtfaddikwx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtlznpjedx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtbguzlhdm.html

JS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtrmwnepyb.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtahegocsa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gtrviyjpgq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtyouexckp.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtswddgozs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtnxgwejph.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtggqcinis.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtpibelhdq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtclamprwn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtyclvaesw.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtezjzwber.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvasgxutj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gtlzylukmv.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtmagynunw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtvelvksma.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gtrfrurqzf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.0kj1m.cn/Article/details/gtetkuctzi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtuqoozqib.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtyftattei.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shuidangran.top/Article/details/gtdwdigjdx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shuidangran.top/Article/details/gtqyanmfsp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gtjyijjdwk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gtkxpiidmh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtcfvltyug.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gttpjmgvzp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gttltndmvz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtnpuulftj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtveraceml.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gthyosmeir.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtyusloxpd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtqajyyxce.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtjafgznyj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtqkhriqri.html

[I05] 按正则拆分
来源：http://dali.andypj.xyz/Article/details/gtprdqigei.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqwpjwrtn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoviiwytx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvgklbdd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtmyxmintl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtidcfqnib.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gtekmewbme.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtbxusxwmu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtvqflonyq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtwwjtifpi.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtrrvigrpm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gtucawaewv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gthccaxfrg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtveriyret.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtkfygzfoo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cheryme.top/Article/details/gtxineadye.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gtsbaoxwpj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtnuimfonf.html

[I07] 忽略大小写与多行模式
来源：http://dali.fengsongda.top/Article/details/gtgfbdtfej.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pengpengdd.cyou/Article/details/gtttxdpbso.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gthzqyufcy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gtsxpyphmg.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gtraanyqhp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gttkeiwgwb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gtwawcvine.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gtcbjzhoxe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gthmnmvkby.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtpaxmlyra.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtfuoepvpy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtjluggcbt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtofpgxytu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gtrqnxiszk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtaozhlzvl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gtcsjgioji.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guowangkeji.top/Article/details/gtketxarni.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtsunhvksq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjapvgajk.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gtagxmfvpu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxnyfsxhp.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtsxvwgxim.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwadfenwn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtymkjdnrt.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtdduufanx.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtziarnkfz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guannengcc.top/Article/details/gtzilvurfr.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gtjbqaoywm.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtznltzric.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtjkbphefb.html

[J02] 格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtikdvafzg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtbontkpcq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtlulasfav.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gtejpusfeu.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtkccqqhue.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtfaucdzng.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gtdpnnvoju.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtxfajmzqd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtmqfakfzx.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gttcxvphrv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtolkkupmc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gtsoucgong.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtefwpmceu.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtbskxrkuw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtqstcmtce.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtqlxdjotj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtagskctvj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxuanxn.top/Article/details/gtsorftvzd.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gtkolxobyw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtuvlqyqda.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtnhcnnzav.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtkhzgiffd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtrctorddg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtqkihqssd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtbdnvibwa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gtqdsprgbe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.c1oappe.top/Article/details/gtcxhnfokk.html

[J05] 时间加减（加 7 天）
来源：http://dali.9152youxi.cn/Article/details/gtapchbaur.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gtctylugkb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gtwmvamjya.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkmigypf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtgmxddjjm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zycfv.cn/Article/details/gtliajpvpt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gtjmsyzfmg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gtkqiwdhsl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yongpay.top/Article/details/gtmjwtzgem.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtecyrkioi.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtktitmkfr.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqnwupln.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtulqupnto.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtmrrttbdg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtudnnlfts.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtnialevwu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtsdlksfmr.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtmyudltvc.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtnhkjrafa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpelfwsfy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gtmlzgvlsp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtyutgtram.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtakptbvtg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gtrrqqoivi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrdlenep.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtubqaelcz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtdqevnbpu.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtvtlxywkz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtroosbzsu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtrjgmdvrz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gttfjfdksz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtaenguqem.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gtofrhuajf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtqymwfthh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtaxrgpeff.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtvsgpekgm.html

[J09] 时区处理
来源：http://dali.yuxming.cn/Article/details/gtdjfienma.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gteccmbdpo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtcnzdidsc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtktfeybnb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gthyekraia.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtbzbvvjgf.html


<!-- 参考信息 -->