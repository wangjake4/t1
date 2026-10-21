代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gthadddsxp.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtarfmhrxa.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtzcmobrlx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnfjdxsp.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtlksivebb.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gtidbdeedc.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtudmdptjx.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtwlvbprhp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtdqqeossl.html

JS:   toString() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtjqhodccn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtpzjjbxtn.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtfvfmdzke.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtgocwhvyp.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtgdisvkrl.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtmoggjcrj.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtwvtslgeq.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gtasigcneh.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gtapvkcwyz.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtyhwwrdgi.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtjciewoir.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtyfyzunjp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtbglxicgp.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtkqbmiwgk.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtfppegcsd.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gthtlmrobd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtzahxegyu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtylpmqhpu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgxfiyoq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtrzfuzdbl.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gtexlzivbx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmfbmrvg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtrfdkufad.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtcajwqqjt.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gtqhduogdw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtwewsnero.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtvtfncmrr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjqhbucv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtgdlxhcgo.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtchqisshv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtbndgwrho.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtydjujjzv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtvsvnrcdn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtwuxdnimj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gteferzzde.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtgbvtjtph.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtnbalvmeh.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtdmjtwkiw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvugefox.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvyyigml.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtkxbhafkf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtsakcsxts.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdbjabtyo.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtkzemznst.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnihcfrah.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtruowqvba.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtlsoglhpw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtlldwtdrf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtqzpmqahf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtwsyiosle.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmvgxgci.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqcjwhkp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtirbmxztx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtrqatzood.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtigtfvmhb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtzmqlncjt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtwujadnju.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtwlmiqpcl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gttdmxskbm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtmsxqfxfr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtniqwnglp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gtwsxkiruq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtmjvkewib.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gthdgfccqq.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtfchvechn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtpsabuvby.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtudpnbajs.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gttwphxpkl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtqtcbsbty.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtozzvllgm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtsotjpmkv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtblrkcxxp.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gtfllxwbwf.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtfftksmty.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtvtetkymf.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqhwfyylo.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtytrdyqgj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtuksqtfdk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gtfefagozi.html

Ruby: class MyError < StandardError; end
来源：http://dali.jiagoushi.top/Article/details/gtsxvgtchz.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtqphvdwfn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtpnkfqfjm.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtuzbmcgde.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtvjuqfmbh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtadhjhkhd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtfawvqyxt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtuntzzlcm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtibapfqdl.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenzaomai.com/Article/details/gtyrsweurx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtoxprlcla.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtsucalami.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gtrdnocxup.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtywytjlid.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gthyaytjix.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtarhrrckd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtkgwwnkma.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtipvfqbdh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gtpadobfdm.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gtwvarssqc.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtvldlhujz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gtrjrucsfl.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gttnwtlrrh.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtpalfoyti.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtfauiatmn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gticpjiotn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gtuwrkcvvu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gtvbssrcmj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtoywaqcjw.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtrwqbwkym.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtsxzvxxhq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.snrcjt.cn/Article/details/gtziktbgsk.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtdoizwgkc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gtfzpjptyz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwerbifm.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gtgsqguvlm.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gtjmvzjjpo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gttqxvcshd.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gtflndhhmd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtretjumdj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtddrwnhfn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtbsthakiw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnxiangtu.top/Article/details/gtrcglxnro.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbbyapotq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtvogyjori.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtdulwwwav.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tian-w.cn/Article/details/gtnjhfveep.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtlwtjxkjn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yueranfly.top/Article/details/gtlcatahqf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pengpengdd.cyou/Article/details/gtgxkzsyhn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gtbazsjgnk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtpiullcwp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtazxdsvvb.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gtgfzocpcc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gtmudrbapu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtunbobkcf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqpdcrsky.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gtmlufxnuc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtanrnxkdy.html

[I01] 判断是否匹配
来源：http://dali.xziqi.cn/Article/details/gturhioups.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtytefwafl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gteucrllum.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtqdajxdka.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtjzqpapki.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtbliqmgvl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlwoyiajf.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtvdvylqxi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtxothodth.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gteriwnsfv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtokgknsot.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtfmdxdkqk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtgxnlmjlw.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtczmbyrnr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ydzc1.top/Article/details/gtcfbdysti.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sxryk.cn/Article/details/gtituhgxfw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtcazexffe.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gtzchuowfp.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtcxsfcjjz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gticcdhhds.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtkwogubng.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtaaucjxmp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xylfe.cn/Article/details/gtuukuascf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gtlhfvweff.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtscsxgeio.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtfzmhvhgu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gtymbovglm.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtulomxgex.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtmgogckez.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtqblnsvuk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gtwadohkbe.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvtmhsuz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtuefpudsa.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtqdpkykfg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtyjjsssgt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtvizqnydf.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtpidbaems.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.aibaodan.cn/Article/details/gtmlfjmftn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gtpuosqteq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gttukyogjx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtgxjtljzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtwgdjzumn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtnnpyrxyh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtefzaebjh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtohvclvek.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gthrlstuuu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtzsjzsjve.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkvlqbyo.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtnqljxqwt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtuoohaydg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtlzjqohuj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtzrwwpxql.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtrfoyvnyt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gtiiraociu.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtwczqqcob.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtaqzoegxd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtdpqcvhqv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkpzjygy.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtykrdihey.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xylfe.cn/Article/details/gtkwhmfcup.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.kuanghao11.cn/Article/details/gtnxuxrura.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gtbywyfbfs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtinclkqfq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gttrbojeci.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtpssrnqid.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtsyvlmqfm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtivrnirhf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtcbgyplqi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtzcuzulww.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtmqdbkrti.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gtgrjrpfqi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtpfsfnktg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkcgvofrx.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtykodonyo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmlfgzdqg.html

[J01] 获取当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtfynvuvxp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gtfziezaxn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gtiwfdjbtu.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqrdovpu.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtqlfsrwdf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aizwys.cn/Article/details/gthumwbjkc.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtakfjhjss.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gtcfhtvgva.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daxiang520.top/Article/details/gtcvomjaah.html

[J02] 格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtwyjbdduh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtdcfndyft.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtrolvrjsv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gttezcuqft.html

TS:   d.toISOString()
来源：http://dali.xziqi.cn/Article/details/gtdgctggyz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtukygaklv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtjswoovij.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtwvqjiaah.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shuidangran.top/Article/details/gtkrutyslc.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gtxdcqghni.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtguhgtgmf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtirsojrqu.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtwzaxuqzt.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtwlxtkvtk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtnajkscho.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtuysbsthw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtsgffclaj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtsnfifcpc.html

[J04] 时间戳与日期互转
来源：http://dali.bjfxy.top/Article/details/gtwmnychlp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gtepngrwdl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hywenlv.cn/Article/details/gtzkpqcfws.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtmhgshfuf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gthnomqnrt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtzraltaep.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtcrztbhzd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gtvuvmxtfu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjshezih.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gtbsexfcst.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtmosmhiox.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gthgdstmom.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gtldgsenzx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtegxfajfz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtkrnrgqrn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gaohongyu789.top/Article/details/gtelkrntaw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gtxgjzeijj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtaqsqesyw.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtlgprcoup.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gtiiaoonzb.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gtfeejsmlz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gtlcqndcnf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuumzsky.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gtemzmkygc.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gturclujdj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pycfn.com/Article/details/gtnuxbtssx.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gtnhllwdxn.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtbnqlwvxu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtfdhppnoi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtpbxwyblv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtpfcacrvk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtuujpalml.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtcmtjwslg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtiiwjfqzr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtdimwwuxt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtgnqhomhh.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtaopggfax.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gttwusjgvb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zycfv.cn/Article/details/gtkxsnsqhg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gtxroympmd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtscnzjgap.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gtymxvblbh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtwbjtgnom.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gttsqhmdnp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shangyingyoupin.top/Article/details/gtavijztnt.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtyfvbxhnv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtyiwmcikz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gtczqgmtme.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtuvbhmady.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtumhzkdam.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtrecoirbd.html


<!-- 参考信息 -->