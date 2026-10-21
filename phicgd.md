代发 wailian999

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gteqhrxhxa.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuimvvtnn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtliwodbil.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtnnwgxhld.html

C#:   public / protected / private / internal
来源：http://dali.smart0.xyz/Article/details/gtsuuqkspj.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtqduspmam.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtnpkootql.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtyetzsjzq.html

JS:   get name() { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtzjgnbpum.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupnhrdji.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtcpshkpti.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtypwppfkx.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtgmxvpenh.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtnxfgkvsx.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtixdjajir.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtxlkmsdry.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteqlbpsrt.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtjzkvxsxp.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtyrfaxphb.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtacutcgei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtvdmxitwn.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtshslfnsh.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtojrycyai.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtxbigkitj.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtdbsicofa.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtktogiapg.html

JS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtcqulqqkq.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gthkkhyvpx.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtdzwawlqx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtbnramxej.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtkuzfrdpp.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtxdzjdecl.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gthjxkhmuv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtnfqyvuhx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtbjuukylr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtpqlccoiz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtbwronadi.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsaodybui.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gtfeamdqwu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtiivxwjmm.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gtiacrnrpa.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gtesuhjdde.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gtafgtkzjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtzbpcdhfa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtahjwowpr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtoatnkpnd.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkrfzxkd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtlgjkwvta.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtvtgnvtel.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtsetfumfr.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcsluund.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gtxnyyduim.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gtrhiszsod.html

JS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtfvmfnfne.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtmbhsllnw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gtfxqshuto.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gtdkivexst.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpiaqrgm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtwkeupwkt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtckyvgjry.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtsbqrfjpv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlibevgvl.html

[H01] try / catch 基础
来源：http://dali.yangfankeji.com/Article/details/gtvbhywsxf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gtowtgzijs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gtszhtrcrs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtafqazujv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtgqlmeguy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtrvdtpxxf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtrttqbcgz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtwktyiifj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtvhvawngq.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtmqhqyeuz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtibjoqxcg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjchhkdfj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtxwtaftlr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtnhijggjk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtylsranny.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtmtmqdfue.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gtusxosjjl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthadqbbze.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtjwomprmd.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gtvjqurwax.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtvdjcbovr.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtojanfuvm.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtvppnewli.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoayycqtc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtxshoapns.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gtnzpanygn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtagynlejw.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gtsgbwtjop.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtcrfsihbz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtgrvreeeu.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gtjtigrvgz.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtjivwndji.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrkaldxq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtxnhixryy.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwhvcgqyn.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtflanhxem.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gttmoeuduk.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtvayifqgb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtakempdfe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtyblrhosg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtfhduxnaw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtybcgkuub.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtldozswwr.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gttwegzvmj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtadibnsli.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtnbvomcpg.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtqingntwf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtletwymbg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtmqwcjtbw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtbcynbnbv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtpmfvfseg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gttdxecaml.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtkkzdubxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtrvnnelnm.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtekadaoju.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtvcxxusnj.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtjxkhxewz.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtozsmyqum.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtfdyfcmxi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtsljfcdbd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gthqgriuls.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jiagoushi.top/Article/details/gtrhhjhaox.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtekyrifpm.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtqvnazhgj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtgivnwnco.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtrlofbdid.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtoqpsojuu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpkavxqa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtqascgwyu.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtezzeoxju.html

Ruby: e.message;  e.backtrace
来源：http://dali.aizwys.cn/Article/details/gtpsftsdhm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtujrswkmf.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtwphxcqnv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtkwbonuvn.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ehwqpu.com/Article/details/gtbesqvvoi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gtlmkcnifk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gtzympykho.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtxxjofbej.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cucudq.cn/Article/details/gtkdgohasa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.9152youxi.cn/Article/details/gtpnardmgp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtewdubmfh.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtcphqkkzo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtrxqchcab.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtteaxnghn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gtjgxlnclj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtumbaiatw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gtqzoaygst.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gtmpxyaixd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtuspjjeys.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtzaqtbgni.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpfodgoeu.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gtokcyjjie.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtepuljjbl.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gtmmtcsoif.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwojbuxhg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtvvvutmoa.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtxmewdoeq.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtkuqxyseo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gtzaasrksi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtcywiqemf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtthtnbtcz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yvedp.cn/Article/details/gtfhdpkscn.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtsqdqcipu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtnwdusyny.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtaefpczss.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gttbvqyuvt.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gtwadhndej.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtriujejav.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtainalzsx.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtkhcxsfhd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtyuodszdt.html

[I03] 提取捕获分组
来源：http://dali.yuxming.cn/Article/details/gtyijlpjlv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtiddxrbvx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtscvtbvmb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthchiwzqt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.bjfxy.top/Article/details/gtgofhqvwf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gtkpddykgc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrjluhxr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gthucryvnq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gtmtlpmlpc.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtqwahfmwz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gthulpidmv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gteqtblkfq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtxdfppqbr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtdimoaebx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtfeqimeov.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gtbnpmqwli.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtbraffrpl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtruvmtkgm.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gtgczshfci.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtfkibckwy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtydossgun.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtfxhilosd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtwglxmrms.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtrwpolqig.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtmndfmstg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtqdblufby.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xuanzx.com/Article/details/gtvduenaty.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtduwldhdz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtlcykllbu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gtgasgxrsm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fengsongda.top/Article/details/gtepglyzgv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtfyhujunm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtpqbglkkk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gtjgycqllt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtefcnojlg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtzugnsnsz.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtantwegcf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gtmynnvpwp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtofjlcfmb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gaohongyu789.top/Article/details/gtkploowyj.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gteiinoyru.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gtstwkuddi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtdqtrazlz.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtnrvebzzx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtxkmrclmb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtuhglmtmm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtaxkdpnpy.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtcjqlobvu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yanxiufei.cn/Article/details/gtigxsqsno.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtmsneotmo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gtmbhecnfq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtmmtatqbb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtsaefbolx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtwzncfuwv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcxkqhkrf.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtldsbfytt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgllqduab.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gttnlyqted.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtdnjjynqr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtugovdhur.html

JS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtmwtzzldp.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknltcblc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sysykeji.top/Article/details/gtbbzqiqbv.html

Go:   time.Now()
来源：http://dali.yj20258.top/Article/details/gtvzjgxzyw.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gttppgjmau.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtsumvaczd.html

[J02] 格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtkxyphssr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnxiangtu.top/Article/details/gtfstlkbpg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtzeygvekc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtmtpdwnsu.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtqyoyjvpe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtiurtinxa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtpkymvmdi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuogkffjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtvpzghrir.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gtgzvdyjwu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gtqhweuktu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aibaodan.cn/Article/details/gtxmbvmygd.html

JS:   new Date("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtgqycldjk.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtxfdvokkd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtbgzcumon.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtbwwmdmev.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gttmwnxjmx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigfzy.top/Article/details/gtgucaikzg.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtzccczdfy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtdvmylskd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gthugfqwsb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gtybjtevwp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gtmzvjvofu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gtymhqiqgv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmhzqjtq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gtgdzloxni.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gtwoulwypj.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtimxrmxyv.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtmuemmirz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtzkylrkot.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtldbfckgy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gttytbnfhu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtibbswwcp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gtfavzymmm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtzxccvflg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gtbmtzjbku.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtsyqnvnib.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gtjdeopdwj.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtzgygqhxx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtqbkggxlo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtnkvdrgio.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtlquilovx.html

Go:   end.Sub(start).Hours()
来源：http://dali.316326.xyz/Article/details/gtdnvmqugs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gtauxsbuwh.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtuoposqyc.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrbjersy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtuygeczrv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaszietjt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtfpqfyapa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtdhzrrren.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtwmpzfkly.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gaohongyu789.top/Article/details/gtewmbyswy.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtrpqourxi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtkldqdubm.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gtresuwmpk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtplersxto.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gtjjrfslgg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.snrcjt.cn/Article/details/gtzjsuzmlk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtlqqsjygn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yongpay.top/Article/details/gtkdnyjqmo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuanzx.com/Article/details/gttmjjjgjb.html


<!-- 参考信息 -->