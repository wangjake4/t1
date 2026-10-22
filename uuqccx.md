代发 wailian999

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtibtynodw.html

Java: public / protected / private / 默认包级
来源：http://dali.jyoumei.cn/Article/details/gtmrtrufhy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtrsprptsx.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtjjmffsbx.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtlvuxlibu.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtmzxursoa.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtlhnhwrec.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gtydpglpmo.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlgnbxwqn.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtxzenhryo.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiudirhcq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfwddkmb.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gtqkbdisws.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gtcilpzpbj.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtftanfdiw.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtqvspqvhi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtngxkbwcj.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqzjcpwg.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtpmdmpqxi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtzrccgrtd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gttxefsrsx.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gttrmvsqni.html

C#:   public override string ToString() => Name;
来源：http://dali.aizwys.cn/Article/details/gtammuvqsg.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtgwlniumy.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gtedarelcx.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtrqtwsqog.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtkhmncdpb.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtxlngkczf.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtbfpaqxsp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gtgjyxnkns.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gtnojcczqp.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqxhtwmy.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtofpugoat.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtuqzxucfg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtfmukwjmb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gtekzdumtg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtddfugdlr.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtbrkwvgfv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtfekzihcn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpywumuo.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gtrkllpwtr.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgxqgevp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtxtxtwhug.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtxoqsntnp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtpjpkerxb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gthplyypvp.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gtxyfmautp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gtuhibnmbq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gtecbeakkc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gttzqvmgkj.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtfwzmrtvu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtulryljzl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtkipwkqae.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtjmalgfgj.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtitdibtxs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcmebyya.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yueranfly.top/Article/details/gthaarynht.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtrfhtvjfk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gteenbkemv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrngyuvmd.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtmmxksfjw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnnlpiolp.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gtldnqsfdj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtoxfvxzuv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtghidxtwe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtrxbhibul.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtoowinoqp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtyggwgpno.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtptiwnbha.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtgjftvclm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtiulbfwfu.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gtmowznvuq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtawmogonj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtslfairwp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtehmcwpwv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcokzxpw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkhnpvzqh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtncqxpdzo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtjyrrppnw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtrvziwgpq.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gttyllzyvv.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtpycewuhs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtiwcahtcl.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtkpmqnwrm.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtivwdjmhn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliuuelxw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtaxwbzrvd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtzrpjxijt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtbpjhwhlt.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtiehdtyel.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtpjnqilxb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtzlqmgrdk.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtxvdcqhxb.html

TS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtywbpipxd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtznckwglu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtimezkudu.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtjwwgxluz.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gthimolcrf.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfavpzjbs.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtxfqrkcbo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtqtrbmkgx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtckmljkae.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvehhpuu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfmtudlmd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gtmrgjmxad.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gtpxqlesyo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtihabxgfb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtcskxpxcy.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtyhjiuinb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtnjbzbsuj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtewkymyua.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtqvirkzgs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtnvepkdbp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtqixtawxk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gtbdzlmfhk.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtpzlbdweo.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtwpczijdk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gthkrcbvoz.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuacqmmhw.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gthutqzcxm.html

TS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtbsuyomcn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gtxjqbosfq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtydpzwnig.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtycalayfd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtnawaosgz.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gturqbhprh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gthidqcqkp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gttatgtwnp.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtjurnuwil.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtlygrlnnz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtzgeyvjob.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gtjsqdadok.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gtqdgheafj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gthnmdimlg.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtjcygosbh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtaoelimvv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gttffoefci.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtltrpmouc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtehathzux.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gtxfsameev.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yongpay.top/Article/details/gtuamnkeys.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gtkgeuocrt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuolawna.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtpeanyvsh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtjpgaftjs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtigqoeycm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtkeaatndj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtocnmwsho.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.snrcjt.cn/Article/details/gtogskrkjb.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtdxedauap.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtdamysvyx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtpuaanhyh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmfbhlutl.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtuxwgegkn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtoffpqtrg.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtqkvzuzbb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtutxevlec.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtfphrbhnb.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtmyzsggrc.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjxoxpicj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtpjyvngjo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukhzaqxz.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtujkxlczt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gtisxcckor.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtkeigxeey.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtqepzbjfd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoatqrmsp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtaiwpwmpb.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gthhycluvf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gtvccyafbw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.meibo888.top/Article/details/gtxlhtjicg.html

Ruby: s.scan(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtzkjtpsjv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtqangnkqv.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtvikbqwsy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gtoraqvlqp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtquwbqiiv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtdwjyhlfj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtkboyjwaw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gtowzkvgpi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnqzz.top/Article/details/gtmzsviitr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gtbgqaslxz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gtmftoxtac.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gtumjetpfg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwmvultw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtachllhet.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtzhuphwdm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtzfeunptw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtsuwnkxgq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtdqvbwyvl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gthptmjsdq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtmtfrezly.html

[I05] 按正则拆分
来源：http://dali.cheryme.top/Article/details/gtvjhqrpqg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtafvbzxff.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cucudq.cn/Article/details/gteqaylooi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtllkwatme.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtqbdjmlii.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gteuluinrl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtfzfjvblt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtzwuisrtd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gtvejfwmuj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gteqioujjr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtexxmaqqx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.9152youxi.cn/Article/details/gtizrubaex.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhiwuduotai.top/Article/details/gthbllrkmc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtwcrzcerd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtnhlcahya.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gtxxxszxam.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtpgunhbqm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gtduwnkkhx.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtzirytumc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aibaodan.cn/Article/details/gtujuwbzmc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gtzmenghtp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gzhubu.top/Article/details/gtixhbteeg.html

TS:   /error/gim
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaadxxrp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtalmrkmet.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtbmyxmdwi.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtwakcjspj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtbngyqwhm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtlrwmzyax.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtujqdbzuh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtxksvabpg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtzyhpwzai.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtlxzeiuzu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtiybyejvg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtwlnuoido.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtxjfcaifo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gtsmbjfytq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprtqboyq.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtgasunify.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpnsgzghb.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gthjfqyoty.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gtksqewusz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtmxcpdgjq.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtqphyownx.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtalsctazj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gtyqxlgutm.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtkkfwfhtu.html

Ruby: Time.now
来源：http://dali.nanxinkj.top/Article/details/gtmwyhykbu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtkjwxuafl.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtfautyneg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtncpbvjwb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtpllspunp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gtcugiomte.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtbtmcfpim.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gtswdgqoqi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtuauhwnra.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gttquwdubn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gtkpiuhdjn.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtdrikmtwd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gtrxiaxipr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtbdpchwiw.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtfmocnacj.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtgiuxvorh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxukgpbyh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtjpdvcjpe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtgbcsipzu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258888.top/Article/details/gttsbefkcb.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtofrjfeub.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtjtfozdbm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuanzx.com/Article/details/gtdrkcsrpo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtbgllwqte.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xziqi.cn/Article/details/gtocqdnitl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtnhsdvsqo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gtnvkotvvx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigufen.top/Article/details/gtpkxxbrsa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtkyaneuqu.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtafhgipvd.html

Py:   now + timedelta(days=7)
来源：http://dali.cashguo.top/Article/details/gtfvdookxf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtyhlivahb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shzxlz.cn/Article/details/gthbiihxqq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtfzsmugrf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtvsoadwxp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gthlgablyh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtwbugugqe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtfngqjeal.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gtwmrtrilr.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtmwwhheit.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtultnsryv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gthvlreygp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtznlnvyzj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtsqjhxqxe.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gtpcojhhko.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtjjximhzr.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtdcpgfuyl.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtzravlwts.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtvpvcztdq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cqqwz.cn/Article/details/gtyuxgfxcl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtreuomfvw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gtozntxsui.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtkzvwyuxg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhongyouzk.top/Article/details/gtyilurhxv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtaogrrycz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtggrxmpwy.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtvunkxtyy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtxehanzmy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.redwolf501.top/Article/details/gttejqeouf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtkhuejhgp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtbnsknlpy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gtqncnqrwx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jiagoushi.top/Article/details/gtnejmotiv.html


<!-- 参考信息 -->