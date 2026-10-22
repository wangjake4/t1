代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtmxzgzllx.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtnskhuuqh.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gthhaqbdnb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtwbqijemp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtghvlwxff.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtjgiwdevc.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtiykfnymy.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtovolofhe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtfczdmjdu.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtgcocforp.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjktszxmz.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtgcjusxtw.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtvdelouag.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtdiusftty.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtazvnqadt.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtluafgxkl.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtnttlrwbc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtmyonkchn.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gtdrsozysy.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtrosxamuo.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtfcxlrnzs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtkhraowcl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtlklutbgg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnguluec.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtyrcrobhd.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthesqcecq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtbdbrzcjc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcynpvuv.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtacaoaeng.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtrfkbnokz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtslhdznml.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefpxvjiu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtodeumwun.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtocfxhxby.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtjcwtivuc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtomlmutse.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtcahlfnoo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtiacxakom.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gtzvkzqpae.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtbusxlalu.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gtjglqymif.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtdzbwaooh.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmofthgo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtfqoewcpg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtvtjffsol.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gteszhloxp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtbfufunju.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnpkzrapj.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtctynksky.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtaghhksqw.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gttjkcrcvh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtcvpgfdau.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtzmunwnmz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsihycksk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtsnscdezq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtrdoxtqjz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gthknccazo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtdhqkcicc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtxmggwbon.html

[H02] finally / ensure 收尾
来源：http://dali.yuxming.cn/Article/details/gttedaoqpg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gttxnvpbtf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtudrblqcf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtotixzyqz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxaenbif.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtiyooceyp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtlnnjxito.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtimnhosyn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtjlsqasir.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtbhuizaeo.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtqmbmfqzm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtmkezhmwk.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtmnrleldi.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtyykfbxvl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtbftyobfi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtszcfppbf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtxetiixkp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhooiuzc.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtbomypuke.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtmmuuxjjc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtwmjamsed.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtrwaqrxdb.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtbfsbrgjb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtvxaerfzx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtgakbmvcf.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtpgbhsfwj.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigfzy.top/Article/details/gthfbzpgxe.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gthwlmuvaz.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtzsykyjhe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jlsjyb.cn/Article/details/gtficzrrfc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtomgkwvgg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmwhjsmqk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjpeviiv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtnnywzrsa.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtvrzckcbv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtnnwrmqec.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gtowcxmbeb.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtddovhldr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtguwidpts.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtmvxayhyj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtqoyfnpwt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtzkwvoxdn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtyuqgfxli.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtcpjumzip.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtjadmefmq.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgzdnuis.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtqqpiincx.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtrgcnpdwu.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gthczkumcz.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtnupiqsfx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gtchcxblai.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gtxzirhntf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gtkahsrhxm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtatuffjiy.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtgphybvwr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tianlin.xyz/Article/details/gtaloyuldt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtvkelyyaz.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gtzygyaaua.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqkkmjur.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlphlgalo.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtijoynnus.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtlxoulrjn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtfvggqobi.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtkflqziwz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtjkziofbb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtxfdvrrkk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtriqgoqad.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqefancer.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtschnfygt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtgcpjsefu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtxhuiozxp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtddjxgctl.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtuszbkxcp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.c1oappe.top/Article/details/gtklepwnwl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gtgmfekeng.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gthzyvvflh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtjllxqedb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtakzhrwme.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gtsqhhvide.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtaysltxbb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtvaosbgyt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkwwlbuzn.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtowpelyqj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrvkzhkgu.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gtyafrfhrq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtbygpmsyz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtrcjskgap.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyokshhne.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtpghemlsp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoodpnex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.meibo888.top/Article/details/gtfuyajqtz.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtdvtzqala.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtzakabdtu.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtfenzcbwv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtvbjzsjtk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtszgvoulx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gtazpmxojh.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtlgsbwjop.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gtptowkyai.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtwylsnklr.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtgdmvzcjx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtjqnmimqy.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtjxjyzsug.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtfksflpap.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtjaynhslm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtjdunwskg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtfmcpqyfc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtxrqcczkr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtzerlpqxe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gtbgbxlnxn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gtqxukngbl.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gttjrushhf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shzxlz.cn/Article/details/gtccmbuynv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gttkhyazsd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtrnjzkgzy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtvisbfgak.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtgxortyto.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjvtmrmj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtsxrxbxoy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtsqusslla.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtmbunltop.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtoczjxnoh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtncxhydgm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gtqwexsnni.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtcdgxtspa.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hywenlv.cn/Article/details/gtjgzojwav.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtqenakzdv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwayszhg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258888.top/Article/details/gtmtnahepr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqszycft.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gtnmxrjtjf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtoidgnbso.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tianlin.xyz/Article/details/gtbtejykin.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtgvzeqpcj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtkycaslmh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtjchffpfc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtssnhkbci.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtjuhrsfbd.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gtzfmafonh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shzxlz.cn/Article/details/gtftwqgwbd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtszctvvrj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtcdtslscr.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gtxbvfokpr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jqgfzy.top/Article/details/gtacmfpfwm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjdobhel.html

Ruby: s.scan(/error/i)
来源：http://dali.pengpengdd.cyou/Article/details/gtarzgciwq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtwxuvwdoj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtmcvbtsja.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtabbywyau.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtaalmfsik.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gtiooqkxqd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqraqutgu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gtowkubwpk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsccszep.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtarvpnvgl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtcmhbbbiq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrssuhlkx.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gtsbkynmhw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqnxtmdub.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtnnuspkvc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gtjfnlovmm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gttublxihc.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtneggqzsd.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtandsmxnp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zycfv.cn/Article/details/gtanojleui.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gthqcdxgml.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtknaimfyq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gtzjtlxyjp.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gtuibmqgvm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtkrkovvpi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtgomymrvp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtejwxklsr.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtplrxdgqx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gtakmqbdem.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gtynkmllok.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtvppzoxjc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gtxhvxwhig.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gtuqfjybke.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cqqwz.cn/Article/details/gtiyalnxcm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gtawlaoftx.html

JS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgifshgl.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtwmakvmrm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtietixxno.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtcgpkhljq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtzfzwpzch.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtnszlksha.html

[J04] 时间戳与日期互转
来源：http://dali.hongshengwenyu.top/Article/details/gtfjbzyatr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gtpgqlitkh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtkdqeiglv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtyqpbhqpa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pycfn.com/Article/details/gtosdwyxbb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gtoyspiizt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtolhgzarg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtfnznqebk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hywenlv.cn/Article/details/gtbnjjbgdr.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtqmlolygx.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtlfzzbwnf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtuzgpjzhm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtbvnytnpd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtlrumllxv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gtofcdqcag.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gtnbdkhszp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtvjxtepvc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtmklflwpp.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gtwpldzrkx.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtnmzkzyyt.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gtlqkeyodc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtysjkyqdr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gtfvvpteha.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtnednbrtp.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtctdkgwwx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtpvmlxdyj.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtidjiwlsu.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gtwiimujdk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtvonurjwz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gtriccynyw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gtscuuviqn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtgkdeflwe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtzpkpfezx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gththxhifr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtzylncmpz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtcycufcya.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyavpfshe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gtbkcnzgqe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtybfwowoj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gtqpuzegth.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuanzhike.top/Article/details/gtbocugdqh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gtujemkrxc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtpgwtzeqd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtocyagejv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigufen.top/Article/details/gtnzsrwkzv.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtrqqatyzr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtkdfxjmjd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtscveuuju.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtylfpbaeq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtqkavzznv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtnvpwwqwx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gtglqptqqb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtcbtrbdtk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtdbxintgi.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gteqdnvqoq.html


<!-- 参考信息 -->