代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtltzztdhy.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtwkxxnifo.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtalqgmzjh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtlxtvcryq.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtdgjxsipr.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gteuhwsxxo.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtkrzotsbp.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtuunpqxeh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlqobcvo.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwiqxvok.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtgmebmctw.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gthmzehxex.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtvwxhjlbg.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtvsefrosb.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gttkyoltgr.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtfrpulixy.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtsnvwakfo.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtorzchpxi.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtaxpltaqc.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gttestsuzg.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtowoseumg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscyyhaxz.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtvwnpbuba.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtchitjbze.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtomtumqai.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtjjwqdsbp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtavdvzwqw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtcjjmvpjh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gtpvbhalvl.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtlmapgtgs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtaoijydaj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtkmrbprlm.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtucezedrs.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtgpjufnlu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtrbhetuzb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtkuutzzpg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtyslxgmqi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtmnqwuhut.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gthehshsvf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gthjkxipmg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtrujjdhqy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtzuoqftzp.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtvehkgwhw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gthnlxieov.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gtanfxxvvj.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtfvbqryxf.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfezabmrt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtmdvcsvem.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtxemaadpz.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtzmixlivf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtvsjtkaby.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzhkpajrc.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtqgthbbce.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtksakgfik.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtgnehkojw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqjjboys.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyabvmwt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtlbdtvvke.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtwkqvrlje.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrxcyxnax.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtavejsokv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtizlzvhcs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtjtcuewsv.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtisadzbft.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtyeensjzk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtvttxknim.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtjwzmrnku.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtnujwryhb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpnwagwk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtmuiofreo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gtycfgpsol.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtlceflkpz.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtwgxbvlpi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtzgcysnfw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtljynwdoc.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtaknpdqjl.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gttscussip.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtznhzuxdm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtmssuoutq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gtrhrsfhcz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtjzaitksv.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gtlmbllqep.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtezpgcfym.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtkdfdbdtp.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtljijfqsc.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtndskskqw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtlltspvdj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtrtjhuvxy.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtfeujjxlh.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtqfgircka.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gtbmmbjwhw.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtqunyopml.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtcgmwoxja.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtdpsizjhf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gthxwwjoim.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtlwolepkv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtlreanrfq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gtvcpbwkgu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yueranfly.top/Article/details/gtuayjgffn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfzsuzox.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gtmjwsajmp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtuswhsvse.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtltrfsmpj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtfvmtlbau.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtlxudhwkk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtfqhnsjkt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtjmpzdrob.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtdeoujiah.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtxafmzdnl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtjzfyunam.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtasznpojt.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtjkoxiwrh.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtzcqeijnm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gttdfhjowe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtdhqihjyu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtlujhougg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gthkhfemvr.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtlahzsjlu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gthylwatga.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtmfpyjdof.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymoyhhzz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtazxokyss.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfnybksc.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtjldlygew.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaeflgxc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtnfrgwlqu.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygbmbfrj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gteioeobep.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shzxlz.cn/Article/details/gtpchlgoko.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtebmggrej.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gteskxnsfh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.meibo888.top/Article/details/gtocogdova.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtuiyvcbze.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtyaihosne.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yueranfly.top/Article/details/gtmgjzsahe.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gtoizwjffu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gtototautp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlqpkeju.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtqrpvmipd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtjpnknrhe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtzfpxgikp.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtgodzjiog.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtaxrkzhyw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtumgnzxnv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbnugirel.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtxynkbbmd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtulygtkro.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gtxgvntpfy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtzwngynoi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfaztdvf.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtducuimnd.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtxwnugwby.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadchyjgp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjrltyfev.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtxiljnyba.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtkvvmauvh.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gtyuhbaqtp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtyetoaacs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtuwqbrmkj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtxpknnadn.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtefknhrsy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbwzbhsv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjqvxuhp.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtewufxzog.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtsrxskfgw.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtjvdbyhjr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.vqdsnc.cn/Article/details/gtntsoingk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtuuuuuhtn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sweek.top/Article/details/gtpobnqgdk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtrztorfej.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gtmrezaugj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtwwopaczn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gtzuhhcfbm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guowangkeji.top/Article/details/gtyyxrcbqf.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gtcckbgimj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aizwys.cn/Article/details/gtkxqqghnh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtdwrkxzne.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtffajzvhz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtkyfriuhd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gticzxlxuz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtyxykswul.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtgnuozcpb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtfpbpdwbg.html

[I05] 按正则拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwlwduyf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tianlin.xyz/Article/details/gtxloldmqu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gtaqalzria.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtneovcswt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtstmpckuf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sweek.top/Article/details/gtqyyqewav.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gtjsgnuewu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtmnpwktdk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gtavepjkaa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtjhqinkto.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtdkfvcdvi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtchihotxq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmjnzicx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtxxgkrqhg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gttwqdnyvo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtxjviuiql.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtvuftebfj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtrrajrerd.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gtbicbipwy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtowbmoaja.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtlzwghcvn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gtqhvakdca.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtdvkwryvm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtiphwltza.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guowangkeji.top/Article/details/gttwrctnqg.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtlpzwevic.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gtvhekocnt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gthxmhfenh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gtcugxczmp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtlihksssk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gtwcmbimpb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtzpigrujp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gtemymzjqb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pengpengdd.cyou/Article/details/gtfrcnjzjy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cdnleiting.top/Article/details/gttaqcniry.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtsyxcuhzo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgdubsvnn.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gtotinaqnv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpbcztkor.html

[J01] 获取当前时间
来源：http://dali.zhixingplan.top/Article/details/gtmmdvzoza.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gtgsoxcdaw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gttumlxibo.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gttwueicuw.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtxulxkmzs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtvtnazmsj.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtmuhogihe.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtrcidezwq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gtsgoypuui.html

[J02] 格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtquknthkh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtmohismrm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtiqdozqpg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtyprrtudm.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtlsreuqzw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtykdzvgah.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yonumen.top/Article/details/gtcdmwekvv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gthikjzmbg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtwcivtgbm.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtbkpxwukx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtidajvnzp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gtvdtouxol.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtovwbyzau.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtursjznue.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gthgdcnyyq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtpbtbktio.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtwkwezxfb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gtachqswsp.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtpiumrbyy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtfxgnepzo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gtoitmjpcd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gtycdbtxiu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jianghu66.top/Article/details/gtgrfioibg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gthuomlxhv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zycfv.cn/Article/details/gtrieyfqhs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtuwbdeocy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hysaishi.cn/Article/details/gtwxbcazfs.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtnogkkkay.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gtjjxmmiqy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yangfankeji.com/Article/details/gthvfdtyxo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gttqcvtxfe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnxiangtu.top/Article/details/gtbtbrhkau.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtxwzzpxkm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtiabmmfpq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmrwockx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtvjyrstny.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gttornomgg.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gtaakbesyk.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gtarvlehxx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnqzz.top/Article/details/gtlvgtfowh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtgfxofypj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtrlxdhujd.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtyzbvekye.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gttfvgmdsj.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gtdpamklch.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gtegzhonut.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtcwpbdzrm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtmtolbvdj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gtbbxxofek.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtaftswuyp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gthkwlguij.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtcrbkflwg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtovwsusrr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtturqwmiq.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtfwgomfwb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtbelxlsip.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxriwatkd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtlqduppwd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gtjutefzhq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gttehuqksh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gtdjlabyaw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlfykmch.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gthnybrrcy.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gtmvnntppp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gtutkdlmqt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmfewjkp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtwtihqtye.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtnnxyullq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gturdqfhcf.html


<!-- 参考信息 -->