代发 wailian999

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtjliuugqo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gttucprnqb.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtyvdmpkxq.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtahkjuayz.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtxqazpflm.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtfiuoxuhh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gttotftoul.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbokyzkb.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqsdepyp.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoauopvrh.html

Py:   @property 与 @x.setter
来源：http://dali.9152youxi.cn/Article/details/gteglfoocb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzgpuhkim.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtecqrjxyd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gthzujxynu.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtvmtmprnt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtqvfqizae.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtqksxllbi.html

C#:   public string Name { get; set; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoggtvcoj.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtiolvkayi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtowrcrmzv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtzjnrdccp.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtcejlmhbv.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtnhbqjzmo.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtkmprvodw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtlsydvkir.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqkvbdnbb.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtvftqjule.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtanvtgwlj.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtknjhnnmu.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtvrtansqh.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtrsziibcn.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtucbdwpgt.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtnfmqcdmr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtlhorsuid.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtdgrlgzbw.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gtodanwiyc.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtvrpdxgal.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtyoeesdwg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtwqkohtkx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtqsxnevcq.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtbxhjtshl.html

Java: record User(String name, int age) {}
来源：http://dali.ivvv.top/Article/details/gttorldquc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtzphazhzm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtzvewssll.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtwrwehmum.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtctqsohpe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtrybwpcyr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gtawwkknel.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtkephpppf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtureppjci.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtunsryehp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtiftliuuz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gtgdpagumw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtgfowjfkw.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtqlxjjxzs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvungthg.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtlqparpiz.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtnfuiytyj.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtogdkxner.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gtlaylgzll.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtdzwnereq.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtdhouyuau.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtkhtlxsso.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxgetbll.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gttkasxqzv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtiszbngku.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gtkguuwjbe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtreytvzef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtoxdilpvh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtvkyfrabf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtsjocxqol.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtsinvtabu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtgadxkejw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtdhudxysf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtkyiuxcqr.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtryayqyqy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtsajabtbc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtxynnohki.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkidzybmb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtlqmkatlp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gteoawoqhp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gtsxtaptvz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gtgwcacovp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtqcktppuq.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtvcrglphu.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtztryfkes.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtjliewgch.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtzdcqxwcu.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtjnvxgqso.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gteircqsvo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeiqlyny.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttecueedt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtznjolcpz.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtcybbtmxv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtuomyoqco.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtvthkejnw.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtsyjgfetb.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtiemiwogw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlqwkdpjp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtkdajwucu.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtvjeqdiqj.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtsegfjyau.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gthcmzfahm.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtqqefjwxi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtlubdpgos.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmtzxteul.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyprrnhni.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtwxdbmpap.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gtbifypjqf.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gtwnzrfxwm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtcrqmfibx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtamezdpud.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gtsrpciknh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtsoopxjub.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtxabbpjir.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtxqfvaxeu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtivjhahgu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gttwibccsx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtoqpenvdn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gtgjjkxfjb.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtdpeklyib.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtpvgjjfpc.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtzlfenqey.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gthftzfbji.html

TS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtnymtxtos.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhixingplan.top/Article/details/gtvyqsmczr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtdyptojhh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtnzgnqfda.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtwvhsybby.html

[H08] 获取错误信息与堆栈
来源：http://dali.sweek.top/Article/details/gtujzergxa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gtsgrlupzr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhongyouzk.top/Article/details/gtekvtqnri.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwvaddki.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtrgdheoep.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtclrbwual.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtpensydnt.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrseseqhg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtvmcnnioo.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gtvbqptvty.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gttgcnznzg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gtyttedjfb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtoylfagmf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtqlbseqeo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtklueacao.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvfoixtb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtcqmpjcew.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gtllhmvazq.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtdwkxobkq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tianlin.xyz/Article/details/gtehmjqita.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gtozpkxqnf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gtozayqywz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtmowljhnj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnxxxqmy.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gttcvxmjem.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gtiseowpyo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtmiufbtii.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtppeubvut.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtihtggurt.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqbvplrro.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtnkuyvgqt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtwdeoypma.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtqtaepyxy.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtfowmbaeq.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtjotecprm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtexupkzky.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ybcxt.top/Article/details/gtxjccelaq.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtfqigppvp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtyzspcxfw.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gttokgqsyd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gthtatpetv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gtqywuoszr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gtssedzrmo.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtlnogpukl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtoltfrcyh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gtpxuohxzk.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gthhigqnwt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gteafnflra.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswdshygt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtxlluphbg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtfmspbvjk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtihriajwd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gticjyffxs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gttcenpthn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtfumwkrwj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dianchejie.cn/Article/details/gtmjjmovqv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtvkybnyrb.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtxscppuao.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtnvbkhgdg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtkawhtqil.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtjswtuuus.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtqvoxazsa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtnxzrumrq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yvedp.cn/Article/details/gttnlhxqyr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gthhskzkpp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtppamfywg.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtgiimvfsg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigfzy.top/Article/details/gtiayfupwa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtbvdwvkhi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gthqyqasoo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtcnqxmoxk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jlsjyb.cn/Article/details/gthzfmfhtz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdwafvpo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtefaipiyh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gtpfxjcbob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jyoumei.cn/Article/details/gtdccfcxxh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gtxjjosefq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtrblkcdwm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gtbrhlzajv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtbdnftush.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtgfhpzmhx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gtfqmslzcp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtajrhxjcj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtmsoiyeda.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtuxcloffg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cheryme.top/Article/details/gtltpwbyjt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtvuyftxqn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtkaijyqjw.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtigbndmjg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezkfxxhb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gtvoxerfoq.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtjaqktclx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtcxaawfwk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gtbgzahrgs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gttztjjwem.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtadyiofvm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtgribodnx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtigvahrhn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtjtmdutbe.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gtfulflybx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gttrrnqhzx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gtwcttmico.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwshtpyea.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtlgfgdazy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjefcohbz.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtjnnvajsr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbugjmsq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtewzhzpdh.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gtaoadlwca.html

TS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtuvezkwfa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtpjsyukfn.html

Go:   time.Now()
来源：http://dali.yanxiufei.cn/Article/details/gttwsjlfae.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtbpmcpcbq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcppdkett.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtlmhcphxb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gtkaxfmsjb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtasqdlkkr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtskcbglap.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtiypbcdgw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtnyfrkgkv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtqeygfqha.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtywcsyiwg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hammf.cn/Article/details/gtmtwpagsy.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtugkdvuvj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gtsvwoeawe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtqnflyucv.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtfohokhep.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtqtaklkzn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtvdnycwaz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtvasrkrlm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtgxxmluyx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtdwdshhnz.html

[J04] 时间戳与日期互转
来源：http://dali.kuanghao11.cn/Article/details/gtizigsahm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtltoqxtiv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtctgojahs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtsuyxeuvl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtorwfanvo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtsttkhyca.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtceziqcti.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gthazruryf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtuqqlkgkd.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtthpwuway.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gttpqhhbuy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtsujirucz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtanxhnvaw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtsqcxrdvn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sweek.top/Article/details/gtbppxoxgq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtlosgphvt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hammf.cn/Article/details/gtoblqnzhh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgfzy.top/Article/details/gtfkevgcas.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtgjszpiuy.html

Py:   (end - start).total_seconds()
来源：http://dali.tian-w.cn/Article/details/gtuofvhzbu.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gtazzajtdj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gtefwhzseo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gtjvnedbpd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtcnjfenyc.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtyamqdmqz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gthtiqdptx.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gthdmnjpcd.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gtzlgeuwfp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtaeweybyy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtcsmdzkei.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtgtcttpux.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtbcsauouf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtbnaepckh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gtylklbwlj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtqmggykji.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtzpyxtaox.html

[J08] 提取年月日与星期
来源：http://dali.hnqzz.top/Article/details/gtgwsbatbu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gttrxyyeot.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtzcburjlx.html


<!-- 参考信息 -->