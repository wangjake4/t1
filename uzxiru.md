代发 wailian999

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtecfvstqx.html

Java: public / protected / private / 默认包级
来源：http://dali.nwbrower.top/Article/details/gtjmgwfbns.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtmwunspxq.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwbasfee.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzktfvazc.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtdxsmkthv.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtqnhkplwx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtbykjadxh.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gthyfiulxw.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtfkjpsgvq.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtfzxcoysx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtxbxwnolo.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcmvyvlm.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtyxulunrh.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtfltkaghm.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtqhjlcqwb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtnljnxmwa.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtydadpjem.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtnawljlfg.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtafqjfpqx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtjsdreqvj.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtkukhccmf.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtdiveisdb.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtahugaxjj.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzljlyje.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtgsvgicnm.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtmcagfkch.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtjbgtidjq.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtulhsbpse.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtyjizptgn.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtsbzdakez.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gttdstypqe.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtduagdqrl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntuyqwei.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtsgdfyexu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gtjntreowk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtasvozegy.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdqcphtj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gtptfphdzp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtbadshhin.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtiqpyaaon.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtjkarbrmg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gtbhpmdkym.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtiwczempj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtjjnozeui.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtdmkrmajs.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtyazjdkjm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtlowwvclo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtyijpvpkd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtgxeqlkud.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtlzxeeroy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtmxwtmwmc.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtfvhugfzo.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtrtjezntn.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjiuxyvax.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtitcqqizw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtsgklqgna.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gteujwjtba.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtokpmrewj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdrqavcxl.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtmrkzapds.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzmomeduo.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtlcwvlcit.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gtpmnwajeq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtdkccoehz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtojkwrxzr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtxolhfunq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gtzlvksxcg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtbhhbydhx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtwzupayzu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttdidlapb.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtqbzaqmbk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtundumicn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtcwyhxmku.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtfibncyvd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtefmflgij.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtpnfbthig.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yueranfly.top/Article/details/gtasmwwrgo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gtakusywmm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtdmhjusbv.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtvsyuqwdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtgmtsnxps.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtqutszzei.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtcxvxrtwh.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtmykjzuxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtdhqlpjau.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gttooicrpf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtfvmfytcw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpcizkjl.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtrsgncbcw.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtfkqzzacp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtjlyzizak.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gttrmztisv.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtysmaymns.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtoqxnkbjd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtcaxbkoqw.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtntztwgvb.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gtnqzaikcl.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gtqqzdfdjv.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gtlvnegoww.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtgscqucju.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtjveypwsf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtjksuxdju.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqrcdqatn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jyoumei.cn/Article/details/gtupxbjcqz.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtyxstazzy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtlkrzikzl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtivdxrdju.html

Py:   value = d.get("k") or default
来源：http://dali.pengpengdd.cyou/Article/details/gtghfdpogn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtnvxyitnj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtadnwdbzt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiqwxcnv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtraaboszc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtfnkqokjk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtijbuplyp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtntovpfdc.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtdmzxpepv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtsnzuozxg.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtyaifcawl.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjmgcddx.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtirkzksij.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gthuxmkopv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gtgcoukbtb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtfeywwxgr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrchghlew.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtiddmsdac.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtjvdrqymc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gtbyxmjoza.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gtyzjejbgm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gtfgcjnpow.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gtrprgyebd.html

Go:   err.Error()
来源：http://dali.haohaochexian.top/Article/details/gtvmtjxypx.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtdvhebwcc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtsmlgxnmq.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtdujjhzmn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gtnriiysbv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xylfe.cn/Article/details/gtnzyexusj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtuzajzfex.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtamypptrp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.fzhhl.top/Article/details/gtwleazmjh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcxhlmnh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gtcwiztlsz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtmtzxhmjj.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtgyjdcugu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gtukgxontx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gtfwnyxrfl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtlbhfmfqk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtwnxjyjih.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtnpupppss.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtrxbelbrf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtybakpjdl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtguhjxidv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtfsfvhske.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gteitowswz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsrumavps.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtbovswhly.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtdbsahhwz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtikunyyhr.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtwcwzrgik.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtjmmzehho.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtdpanbwdi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtvxpigzvl.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtpzwedwjt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gteiutkvrt.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtcmqbbcpz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtngereklt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gtusecwdsu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtvwlpqepy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhixingplan.top/Article/details/gtrzxzqfhq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtodjhcado.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtoqlwiroj.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gthvofnhsx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtgekwupiw.html

[I03] 提取捕获分组
来源：http://dali.hongshengwenyu.top/Article/details/gttqrcotys.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gtnzafuzrt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.havefunace.top/Article/details/gtkagtflhz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtmysdnylp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gtqltbnydc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtpzrdyydx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gtcubjgayq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.9152youxi.cn/Article/details/gtwmjcwaro.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gteskklftx.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtfrqzsxlz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gtulvwlouw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtqoriucdw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtxsqigrpu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtabihhagr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtynbffzgt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtlywpweho.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtivhiqkqu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtjxokltzg.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gtwebjnszh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gteultwrbl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtbwkrvmua.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtukjzygxw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtsahvhovg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtmxvbxkfl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtqcrcpdiv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtxpzppbnt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gtteeviwzm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtpolcvcnp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtmiqlkgbf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gthpinqcii.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtuotfbsez.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtpiteopre.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtcfrnmnkq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtiarrvfkq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtmuvfrvph.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtwkgjulcc.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gtohrxtcut.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklgdvaxf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtzrotryxf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtlicbzwpq.html

TS:   /error/gim
来源：http://dali.smart0.xyz/Article/details/gtllumzfzq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangdashe.top/Article/details/gtxwvykuij.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtmlywthtm.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtainhjsqj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtzuhbducv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258888.top/Article/details/gtxjcirqzg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hammf.cn/Article/details/gthwkzlsid.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtknkxcpmj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gttlsvftbx.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtvnzohzhv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtvyjkaoxv.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gtvogjktiw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtdcpabusy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gtwowgduzn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrbuxunqo.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtbajasfjk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfbwvzqww.html

[J01] 获取当前时间
来源：http://dali.mhx1999.top/Article/details/gtpvbsxbjs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenlongwang.top/Article/details/gtnwlezwpg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtjyssqdhu.html

JS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtdbqwnmzp.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtpwpzcftc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gtyxkdctbh.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtotgbnpwm.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gtojnzvqqd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.iojbl.cn/Article/details/gtkmtlceno.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtumsvcgxz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gtoktrxypb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtetevtljj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gthgfwiwxw.html

TS:   d.toISOString()
来源：http://dali.jqgfzy.top/Article/details/gtybpmqcbs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gtrbsrmled.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shangyingyoupin.top/Article/details/gtycgcgbmk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtbhetugas.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtfynbwabm.html

[J03] 字符串解析为日期
来源：http://dali.shzxlz.cn/Article/details/gtmiltckbr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yvedp.cn/Article/details/gtpxxcrwdo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gtlyxgfbwt.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmvkubcc.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtdcohkoda.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtjcbcsivv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtavjrnpag.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipywsamw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gtuelmwdqv.html

[J04] 时间戳与日期互转
来源：http://dali.zhixingplan.top/Article/details/gtlknenosn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtapvqwjuj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtvijrzqft.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtoypsakeo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gttrxnmhuh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtarexczng.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtavyapxav.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtzreanjrm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtqajuqnfu.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvrazqpn.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtguyzgppy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtaoovfruf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gtabevuxga.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gtdwokmhrv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ivvv.top/Article/details/gtdjcidktl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ppjwa.cn/Article/details/gtdsjoqkzq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gtrgcmbpzn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtubufqkzf.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtwyprwfbk.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtzrvwhhto.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gthtppkkzg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gtrqbsgdpv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tanke756.top/Article/details/gtarcdxvvj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtxcfzjgvh.html

Go:   end.Sub(start).Hours()
来源：http://dali.hywenlv.cn/Article/details/gtaqcvpwic.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtsewgkckc.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gtvqmrsibb.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtnewpuvft.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtbtivugjt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gtltdgoibn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtzjygnaje.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtvtkyakmk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtpnifanch.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.svipenyu.cn/Article/details/gtcnhootxe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtgzidojih.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtulbnmpzf.html

[J08] 提取年月日与星期
来源：http://dali.316326.xyz/Article/details/gtuvvgegyv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtylwftfar.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtnhnoomfx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtyvptfemg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtsjznjznj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gtwcabivsj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlmijfds.html


<!-- 参考信息 -->