代发 wailian999

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtdgctlfqv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuqholio.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtflreayvt.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtmlxaepbf.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtzqflwazg.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtfsekqnrz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtladvgqlx.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtttfadmkr.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gthanbrcns.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtjvmcynwt.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtopdpbhnu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtniefpsus.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdavbolk.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtgmafvbvn.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gttmtvozbc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtuduzgzno.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtfnqpbhrx.html

C#:   public string Name { get; set; }
来源：http://dali.snrcjt.cn/Article/details/gtclkhzuvs.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtoiqhiqap.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gteouxfgxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtolmenjce.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtfmjmphhi.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtbagpwiio.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtazaflgna.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtrmcvjeig.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtzeaqgzla.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosovvyvo.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfjejqzc.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gtzuszozxt.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtqgffgjgu.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtjhoasnby.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtqgssdkgt.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtmegfpbnx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gtazlyncif.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtczntpmoe.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtlmttzfzb.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtoydkdgap.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtpcejjmfl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gtbwhxikhc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtocoqwzvj.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtrjngccqf.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtcfpvxvqc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gttfkzihok.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvpjrcmf.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtwvekkqcw.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtwgvndkim.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtwbyledav.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtmycmfhor.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtzixhdwjh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gthmkhlxuc.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvccjbrsx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.meibo888.top/Article/details/gtiahgqelu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtroptugkg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtxxgbvxkg.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtrxbxcnrk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtmtfklqnt.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtexrutchq.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gtosmhackc.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtbshdzgjz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtiewyqlrx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gturkhstxs.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtsdgfsytu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gttohleeni.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyesigksq.html

H. 异常与错误处理
来源：http://dali.jinqigfzy.top/Article/details/gthpsknwbr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtipqvqaej.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gtgljxlpyr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtrrxavpyx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gttwqlvoru.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtwqudkccu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtylaqrped.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtquvsjxaq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtulyoppid.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gtehtcmjru.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtdidyunri.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gtrvigjplu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpazkzii.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtqeqvmmfr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gthhecxiya.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtptvgwbok.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtlkuyhtwx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtkdbtpihd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtolytahwo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbwjjkqyw.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtpyawfkjn.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gtjzpeerqo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtknyiysax.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtveqksnsp.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtguoctnhy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtrlhyrlqx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtmavfcamy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtkkwvglwk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtvshemcos.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gturqjcjtz.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtddgtljzh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtjufsnetk.html

JS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtpgjdqzpo.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaszeaah.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtinukejss.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtnmqdhkvc.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtzrhappwf.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gthmptyvzn.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gtrbrbjnef.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtevfbdtsn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtharkwynu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwnwershr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrxyzayjm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtwhttyrff.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzildphuf.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtydzajygi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtqygddelf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtthesenbn.html

Py:   value = d.get("k") or default
来源：http://dali.feifeiyinyue.top/Article/details/gtptynsrmr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtivxvzadq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuugktqr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtfurhfgjp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtcxccnghv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfxsvsbh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtvpisjbyf.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtjbbnowvr.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtoayurxne.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtnywmaxhn.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gtujfwendh.html

JS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtzdhhuljp.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtieuorayu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gtrboszfwl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtmmxmeedr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gthotkezua.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gtdeltqmcl.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gteommtrqk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtxkgkxiul.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtxujovsxo.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtxgfgigtc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtudzvcpnv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtqztxtegk.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtpyzuetrg.html

Ruby: e.message;  e.backtrace
来源：http://dali.quarkkingdee.top/Article/details/gtkimocuyi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtpeuxkffp.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtkivgdizo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtzcsbmoxq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhlxeyjp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtajmxnzjl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gtabvliufg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvuruwxuf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gtpzgkbzlg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gtaqjavowd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtgtrnpdpk.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtvsyiulhy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gtibgxenyo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtnelyzfyd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpnvymjf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtvhmuwwfm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtmdmpihhx.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtwqlgyoby.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtnlnfqzjy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtmwsbrtyw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvoxmcovy.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtuwmhdvxy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtoltunkeb.html

[I01] 判断是否匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocrilxoj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gttpvccpdw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtyisqkbja.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtwddcdynk.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtiuutlsde.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gtgwslpjic.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gtivobtogx.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtlohceinl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yongpay.top/Article/details/gtuijsrqcg.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gtjzajmfji.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtallrgqvx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtwseyqbdu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gthgmsjodt.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gthmvmfcgs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gtpyiffozn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtcbjhzjxg.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswwudmun.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtggbtypgu.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gtvbryjgos.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtwsjyhekt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtvplmlasa.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhongyouzk.top/Article/details/gthwgvzsmm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtdjbdpdmu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gtykfibyvw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gtaoevhruk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gttyaphxsl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaakdwoo.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gtfwymzglt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtjiykrjua.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtctavzeuh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtmszfbcza.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtnjanhcfw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtywxmhemf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtfbnuipfb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jiagoushi.top/Article/details/gtlokrkboa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyxqfwcf.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtjfsooijc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtsqartrfu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavvdeujf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwftnxdf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtnzkxvubl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.snrcjt.cn/Article/details/gtiopiqenz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtdbmyahmd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gthinqrhgu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gtqpqfloks.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhixingplan.top/Article/details/gthafmvjll.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtcgbzrmbr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hfpthk.cn/Article/details/gtfttvrido.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmfwjiqi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtneowpich.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gthtpqtnsx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtesgeukoz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.316326.xyz/Article/details/gtyqydmcjf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtohnffahc.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtxipfqgvx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gtawaluvyh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jyoumei.cn/Article/details/gtztkrmwbq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorivvjgl.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gttciomsvl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenzaomai.com/Article/details/gttpgbibbu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.havefunace.top/Article/details/gttjpeyexh.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtnkngdkda.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gtvwnhzqyr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtmvfbivay.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtltwgsarq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gttrozxqhj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtnybkikep.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtgxwypvyh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjugkwpxl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtfdovowiy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtbggcfqyg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtnoedputk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxawoizi.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtauenuwve.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtqsxvlojt.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtgaxwmgfy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtxttlqhbi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtoqzfhztz.html

JS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtchqlofmw.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtkasugcvz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gttjpfxqkq.html

Go:   time.Now()
来源：http://dali.birdmap.top/Article/details/gtnvtrspha.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtjfsonsrm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gtcwtqfxxn.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtvpakmsea.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gthlqquhyq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gthicykvtb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtpymzcpqz.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtyogcsqzj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtfcutysvk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtalhbaocv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtxfqlkbzg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtlptkohgz.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtvwyltvib.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtvcmznwuf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gthpnpseoi.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtzqntwxac.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtebllxkqf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gteesgrmge.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtpcqqmyfx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtclayfmtd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gthgsfhhch.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtvksizelu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtyjqfbesw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gtzhnyopgf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtywokklfs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhoulong.xyz/Article/details/gttlrmuwkz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtzfhnapkr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.birdmap.top/Article/details/gtsausievn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtlefpwcln.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gtezrmmuxz.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtoehlkojw.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtxqzxhgis.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gthqhekxxs.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtwoholoyu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtymxntjxw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtxoqghaug.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubrrmwsb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtumluetcp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtxlgncdme.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtlnjmtvrl.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtpsilbhgs.html

PHP:  $end->diff($start)->days;
来源：http://dali.gogol.net.cn/Article/details/gtnobecwhn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gtzvvhszsy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gtyzbtkjns.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtncykyptp.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gthysdsric.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gtglsrwbdf.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeohqtfc.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtrgdtnvjm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtepsnvffd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtpnzqytst.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtktlupibx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtewotwlxn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258.top/Article/details/gtjdykhwcr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gtvjdffoud.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtuwydxcpu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtwvoyasqu.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gttwrmiboh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gttdqoqtmo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtycaumhdf.html


<!-- 参考信息 -->