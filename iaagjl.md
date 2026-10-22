代发 wailian999

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gteshheazx.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtqqdkyohx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtwumttzbi.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gteivqkkkl.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gthwxpzoob.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtgoqhukxe.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtiidgrcdg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtgclthfjb.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtocjkdxgg.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtlbsgsjev.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gtonxccfsh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtgtmkdquz.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtfrrkunhw.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtqbhwtdth.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gthjrlnsuq.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtmrpezxyn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtaprprxoa.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtkuytkyrb.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtbdrfixbs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtasexioau.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gttfoldkxb.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtgfyoqsxn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtqfpije.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtickybxic.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrdblhzb.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtanfvpplk.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtvexsjbza.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtffqaewlv.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtpxukumks.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gthumkuxpt.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtnwvncdjy.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtnppszepq.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtdqdmqnci.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gthuyaxdzw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtpfazkzhp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtlsxfkvcq.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtbacfleqw.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiqdcrug.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtvdhdfxxx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtkhxwratd.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtqfoppssk.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtokmtaymu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gttqmktopr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gthkedttzf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gtgjmnkzxy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtxqxpekqs.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtogxyltbw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtqmndjvct.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtwvwdxzxq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtlsdekbdo.html

[G16] 对象转数组 / 字典
来源：http://dali.feifeiyinyue.top/Article/details/gtvhmlpaei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtjcpenwxu.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtnwxfgifb.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtuswwzkft.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtpwcrgtpa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtgqfkxswq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtiinkpzcj.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtcwhywtau.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtlnotlvoz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppxawhxb.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtohiiyrcu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthigwinds.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gtrcyxiozb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmpnelvb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtujdpsmdf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtufeyknzt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtkkzezmfo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfrvdkscj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtgvliqqoo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtdblxinrl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtarevrdsa.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtwygrxdpe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtjxrdsrfg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtowwhqrww.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtqacrqgnv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtkogykssa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtloaufbjd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtijlpylwr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gtzkfygibf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrpadwro.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtwjnjcjcx.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtofgwabuo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gttvphyqcm.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtgacietmt.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtoquzrdqt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiemeirz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtvjadycpj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtcufwyhpv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtifqxlosy.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtdawnapss.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtjnzmubtk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtbfxgbkhq.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gtqovkiyvo.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtiwtgdeta.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtimqjyzqi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtpthqhnvh.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtmxcrfsrg.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtbsvvhlkb.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtfhwxtpcq.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gtbqpbqrnt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gttwalhbis.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gttusmbgdt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtinvocbqr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrdihwlhv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gtxktxpoec.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtpkfjjqng.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskreqdum.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtswxcrghg.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gteztrsorr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtsqgqjwwa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtyomqtxri.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtkdyldemw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtkelsshyf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtyfqxeqsc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gtdhlwnlnx.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkvqmlkc.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtgiybayqu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtvlrcxhhg.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtfchmcash.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtpbvojkwo.html

TS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtbumixqqt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtfiwdbewg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtxlmxqbvh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtcangfomk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtxgbudlqw.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtumirfspx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtiveaxcbk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtywwarxsi.html

JS:   e.message;  e.stack
来源：http://dali.jianghu66.top/Article/details/gtyofsffop.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gtdavibykb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gtqgwgpdpq.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gttpaurdjk.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtpcxmqccr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvqpqujh.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gtniliguxr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtznvqixvi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtjbkkfinm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gtrhldabmf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtwedcamff.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtoklccxja.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gtchggdgvt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtceddtmts.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gtjjrfmhnn.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtjqzvscgr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnxiangtu.top/Article/details/gtlvexzjgv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gtgrrxvkdt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtjaupeqnz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtxzpvziay.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gtqlozovqx.html

Go:   defer f.Close()
来源：http://dali.ydzc1.top/Article/details/gtwonvvxod.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gthaesdtyi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtjftdxubh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsgtvvkvd.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtlldqgxnk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzyztkjra.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtukygjqky.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtojkiaadk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtyhqtrpvk.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtteqhmgam.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtmbgqenpk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gtldnwkamb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gthxkvzyjv.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtmpaonbkx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtsjcrnxxl.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtrxtkrtfn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtbuiagzur.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gtbuhjcadv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtfrayxdkk.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtyiriavvt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gtpblygwav.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtyaamrfxy.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtwehayrdo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtwpxvthgq.html

[I03] 提取捕获分组
来源：http://dali.nanxuanxn.top/Article/details/gtdekzqpaw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gtysftjnaa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtmvxdntmq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtrjvuyrcc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gtlkugkrvi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtjwaysfrm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtdcfbnkoz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtmxdmxoxm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtsjlhjxzr.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtznoyillg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecerowcc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gthlepcwiv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtfwtieefi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtaehqdkrv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtodoimbct.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gtlzlqdbcq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gtpyhwcjgq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gteqmfejfb.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gtdgwtmzvv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gtjojdzrtm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtxpehezqz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gthjxkigjy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtunyqzvak.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtyvsleswi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtpogokgru.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtjsfgetav.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gttcjxnieg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtfvyvjwto.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtgrtsrzfb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtxuyqgqpz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtvztzrfvr.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtlgbfrkoe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtcgohuhoi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtpsoomora.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtpbnovuoi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtuwvkvjhd.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gtwqdsafov.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gtqakgrifu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtwrximkyf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtcfwmynqe.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtslnevwew.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gtohsohziz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtvpzmdikr.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gtebqtevto.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.c1oappe.top/Article/details/gtbkbvsztt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtnayvkbfe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.snrcjt.cn/Article/details/gtqfjedkqj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtowaxpvle.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtbqzosewh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtpdketddf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtureakgdw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gthtypcizd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gtrhcsnjib.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtxyleurem.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmsfqeefn.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gtmdnvenvn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsrbtmcne.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtdlcgvyaq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gtxijnhmvu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenzaomai.com/Article/details/gtyrjqtjbt.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtcxhzzmiv.html

TS:   new Date();  Date.now()
来源：http://dali.nanxuanxn.top/Article/details/gttrzvzjer.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gtedoxenwp.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gttbpyrqhl.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gtsqfyjmii.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtqupouavn.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gtltqoczgg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtdddaslqn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtbxavviry.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yueranfly.top/Article/details/gtlwphrtnj.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtleinuvbp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gtvptqsicx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.aibaodan.cn/Article/details/gtpsslredr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqfurlld.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.c1oappe.top/Article/details/gtbpgbdihs.html

[J03] 字符串解析为日期
来源：http://dali.snrcjt.cn/Article/details/gtapgokrfc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gtwlpjilwh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtixfdtwbv.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtrubvrkmd.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtsyfaqdtz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtrihryoxv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtranlryoq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtggcjtztu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gtgjjoodoe.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gteokfgkvi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenlongwang.top/Article/details/gtqersftyl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtjkmaddpt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gtdxcwqcgm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jqgufenzy.top/Article/details/gthsxlqbom.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtwgmnzfzv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gttbwpsxew.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxuanxn.top/Article/details/gttekvsinl.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtxhdezzow.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtycrrwoic.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtwsrevjfy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtlokzggal.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtyrsqviqg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtgpmzmnmo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gttqhkesjq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gtdsfrtuvz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gtfrpsyiyx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtoelsrwge.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtivxtuvkr.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtkggntkjj.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtibzusmra.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gtktljfvbv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ydzc1.top/Article/details/gtrvybdada.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtjkyosprp.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhixingplan.top/Article/details/gtggpgzcjs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gtnqehgrtc.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gtwxbxbbxz.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtxqhquboo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtysjztazq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtdcxbodbs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtgpdzxjhm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtvzznyddw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yvedp.cn/Article/details/gtunsywrqy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtkcqkmxjl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtdheaqsws.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtovriruij.html

[J08] 提取年月日与星期
来源：http://dali.yanxiufei.cn/Article/details/gttdeluoam.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gtqoajwofq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gtfuriyxzi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gtkdwfunic.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gtqgtcwrdn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gtkwjwjfqw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtcfawrplx.html


<!-- 参考信息 -->