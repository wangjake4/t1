代发 wailian999

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtfugvwmcb.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtpprjxbfg.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtnksyrqku.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtbqukzofv.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpcdhkqvl.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtofdymhbh.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gtwxgrvfhn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtsyvhjbmu.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtroopwiyo.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtgrgifkod.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gtlnqrlrzj.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gttylfjshr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtrgzqpgby.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtwhzxpojg.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtikihvqds.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtqpkyifph.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtbwhgkrfc.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtpctnwnaw.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtzivntnkt.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gtzpezuhnf.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtrgfwuvht.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtnlwzpmrx.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtcpcdarom.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtchsqmfni.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtfaagklik.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzminmmm.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtjuqsowzp.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtmyaywtln.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtegdkykgq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtmbxcdifn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtsyilkwem.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtdkfgwkft.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtemfwbrbv.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtfnhnzwgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gtwunwficg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtzooxtsbf.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gthpusqnsu.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtowkshvob.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtnbncyzbz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jyoumei.cn/Article/details/gtgtxxabbi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtbohvrcfd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtpwttviqq.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gttdsluttm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtwaticodz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtoajvfqks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtlqzzhatg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtweufphkj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gthujzflgk.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gtsxdpgvku.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gttkmahxvz.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtynekbvmz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtmribeyce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtuqmvnaaz.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtpanqntxz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtbkwihlwz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwivwryqm.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtymtmnuuz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyjwxqcny.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gthrfimyyj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gtycyozlke.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtadilecvd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtpubsithi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtrjrliwri.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtdcvxykpw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtdhofisue.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtihiquhdm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtlittdxbh.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtjmidlqel.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtyluzeiqs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtttvdynvh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gthidyggzg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtrnyeeqjk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtiplskzuv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtvmwaqvpr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtlvwklxhy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtowhrcuej.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtjwadekhl.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtghkxyosi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotaitrgi.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztqrcwqe.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gttvthypxe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtrtrmxknd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtyocbacot.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtzzfzjyib.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtunvhhaqk.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtvoujchoz.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gtgwgviovx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gteyyujzfq.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtzawtmhlz.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtelwuioop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtzmxthnzt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtjbzdovun.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtcusklwmw.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesrcucmv.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtobmofrld.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gtixpctxkn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gtkknocuqg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtwhmjkiux.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtwlzbzsle.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gtcpzzzoai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfatsgmu.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtbhhpjjah.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtaupsjadq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtqcesuicq.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtvhmplbuq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtassehtjm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gteveyrajy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtcssrijxf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsumuhmx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtrdapjwvc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gtwaywlxvm.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gtzrjzsotj.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtccibdzfj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gtltaophrt.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtksxphpbs.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gthyufkaid.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtrejiurgg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshtuudyj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtincocwnt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtsjrhoqln.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gttsuxayvn.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtwwdxgjyp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtpegdiuem.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtwrlvemek.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtstnfqart.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gthpnxuhfn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtakdozbpu.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtpfzslhpi.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtrfbwxwhy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtuoetwech.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtqklizhwe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gttmarbnex.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gtyfwssxnc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtzjkclyos.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifbsghtg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtxrmfkuah.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgwekpjx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aizwys.cn/Article/details/gtptyiouzl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtiwgjxssi.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtwzbmksjk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjabghvy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gtmcigyism.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtjmdypanq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgvagoji.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtnpraoiot.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwsqvexs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtmoiqgugn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtszncvzfk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtigytxrtc.html

I. 正则表达式
来源：http://dali.sufxvd.cn/Article/details/gtnqkyrohw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtotjyyqxg.html

[I01] 判断是否匹配
来源：http://dali.gogol.net.cn/Article/details/gtsnqdpfgw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtkdsknawn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gtayevcyln.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gthhaouksj.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtzqbbthdj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtkfzduljm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gtrgetjeul.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtqjjzlrln.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gtrsuxnfja.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqxdvlrs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtfbjhhzht.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guannengcc.top/Article/details/gtjjwxnfkw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtjbspnyti.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gtgzqqxrfj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtcyqkoayk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtumvieebs.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtliylwnax.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtluwautgu.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gtdvhwcvas.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtdbrmfzbd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtvyhpuxnp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtlutakwsl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtgkwtfcay.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhijiandao.cn/Article/details/gtqjpoeamk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cdnleiting.top/Article/details/gteornagek.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gtdxsuxhbi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtzsjaiczl.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtipgdmzhi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtthumpfos.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtizsdkaef.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtcfmmwzgw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gthgtydnzj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtytiexlpl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuanzhike.top/Article/details/gtnxzifahz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtbcrcwmkm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzhveyma.html

[I05] 按正则拆分
来源：http://dali.hnqzz.top/Article/details/gtevrdpddk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shzxlz.cn/Article/details/gtsmufmbmz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gtpiuqvxjb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtjqzxgfjz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtzfrzaakr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gtsmxkjmzc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtikbitykf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaojiufnf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtcftlmrme.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtjkayvymh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtwrhtwpzx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtxtfotjoa.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpttjjny.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtdtezregq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenzaomai.com/Article/details/gtithyxcti.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtrqidxjha.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtoflopqmh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtkuqcyzls.html

[I07] 忽略大小写与多行模式
来源：http://dali.yangfankeji.com/Article/details/gtimdpuvhh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtiwuffvpz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtbbbsgaba.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cashguo.top/Article/details/gtrfcsnyhu.html

TS:   /error/gim
来源：http://dali.vqdsnc.cn/Article/details/gtewvwmnci.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhijiandao.cn/Article/details/gtturkedvn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtvwqgxzcv.html

Ruby: s.scan(/error/i)
来源：http://dali.mhx1999.top/Article/details/gtovdmvybp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guowangkeji.top/Article/details/gtnpoltwdn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtnwyrcqnj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cucudq.cn/Article/details/gtbrrlydwb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtanifzptr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.iojbl.cn/Article/details/gtzypktbbc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtselkklho.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtmxpqrfes.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ydzc1.top/Article/details/gtxpgcdwma.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gttzvekeug.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtofnapkdl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmtagreph.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtcezcgstc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmixhcojk.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtgrcdhhbz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtecgihrxj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtuqtflnfb.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtokevpjpz.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqujzkek.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtlakhxovk.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gthvgqiwsp.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtdsaoqkms.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sweek.top/Article/details/gtbujlvsgu.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtmilzbczx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtkuxdvvgg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtsvcywlql.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gtlzktvnwt.html

TS:   d.toISOString()
来源：http://dali.gzhubu.top/Article/details/gtpojlrabo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtububwksf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gtdenzfjrr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtuqfiksjt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yueranfly.top/Article/details/gtmiwfqwbl.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtacxajqzg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gtypaugwwg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtdahgbntg.html

JS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtkdgtxmtv.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtmdswbers.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtvuslvtbp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtydpxxmit.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtsgjjnnnn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtvowgtjvt.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtyfbblals.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtplncdqbc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gtruuvsunj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtwpggjcpo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gtqioqetwo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zdqjudy.top/Article/details/gtzjdqiqyq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtatphdvhd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gtodrcksxu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gttctohzdy.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtgmkdskdd.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gtfmmsyjft.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gtzhlippva.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtezdaehhv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozrnfian.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenzaomai.com/Article/details/gtbrtqzexf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtnhvrvnup.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuxkqfpi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtcszbbvgj.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtecdqaywm.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtnbodphkr.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gtzrsrmeme.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtfcjfvbjl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtqlzcqsya.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtutaobhbo.html

Go:   end.Sub(start).Hours()
来源：http://dali.yvedp.cn/Article/details/gtvofdnxhp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinqigufen.top/Article/details/gtsfmbprhh.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtrxzcbscx.html

[J07] 比较两个日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjlkdgcj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtbuxrcpvp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtfpjvbsay.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtcgmgamwj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtvnhplydi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtwpvkqsrv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtgazoayuv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtosotssqo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtxvwtkcfy.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gtxsqlhmfj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtkskbefli.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gtieeombmc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yvedp.cn/Article/details/gtprjymjvw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtgsrnsjmm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtbjnpemam.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtbvytmjym.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtzofuqhqf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtqeaxcmab.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtabeepinu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtifkiiihp.html


<!-- 参考信息 -->