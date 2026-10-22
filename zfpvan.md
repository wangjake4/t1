代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.xuanzx.com/Article/details/gtnojmqspp.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtlwmrhcvj.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gttkvoemkz.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gttivnvqsj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtbrycivgf.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrmdjebki.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtlyudmecf.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtpqgwziof.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtsmieampg.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gttmlsyurx.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtesndcgow.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtqfbyosuk.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtqknrwzdm.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtfetrjhee.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyiagdqz.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtcfiwecvf.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtbljhomji.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtdxfhazkn.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtzqokzhmd.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojyiiqjl.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtpqaknfyx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtekrximiu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gtcocydlts.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtgjnpdbjv.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtadnwfptr.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtnchwkfdw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtctvmwyro.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gtypeovoeb.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtoqmyfrlm.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtjodlvkvs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwwfdqmd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmvqhmcqr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtvpldazqm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtgcmaxfnk.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtfvjljmrz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnhcfilf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtkdlugmwg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtfwspgfte.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtpsjasfkb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtwheurysc.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtoitkqqrv.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gttcnoxpxq.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdagcnmw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gtxnbtosir.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtjpfhtksa.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtkziotyww.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtsqrkzdml.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthjseglyc.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gteanciccy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttiwunrqz.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtgnotcdou.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtyoyshmjp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtvckkrwlq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gthqkyivtj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtuqisqydg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtedshjtch.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gthfmovuew.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtgygnfizv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtajxpncjr.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtnviiedtr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtggkyazxy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtavuysayn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtqlokpmvw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtiqozzvhk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtnsdqaust.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtqnknyifq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqqxcxyy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtzibramcg.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtllfpflxl.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtjghmcdtn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtsfcfzdiu.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gteyiquius.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtuqsulrkf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtdbzsfjgn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yvedp.cn/Article/details/gthqnygcor.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gteocxhkkn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtkdsgfbpo.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtbumcbxad.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtwkmniguw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtgmfvhjjm.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtwqgqxivb.html

TS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtmasbuzif.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtxyjdofbj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtxuovfcnq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtbriphdda.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtqimwxdjh.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtykvptprw.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtmejedjyb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtwgdldrns.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gtkplunfhs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtafbbtlke.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtffvavrod.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtpqakcxeu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvqhbcst.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtliigreva.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gtxqshqpnl.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjbymzql.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtxfnuizzi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtrslosqwv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtdawxtjma.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtmzwkdzas.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gtckocunli.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtodgfqbgp.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtuyjswpia.html

[H07] 断言
来源：http://dali.hammf.cn/Article/details/gtykzgxgdm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtfqocqmbg.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhpgtowi.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtnlkcfeqk.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtfwwqdrto.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtncjxfnzf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.c1oappe.top/Article/details/gtystncmcj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtmtkjpcxc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gttsjqchmd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtdgjgltjk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtmmvdqfjg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtwdrqzqos.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtghdlcsls.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtbqddhuwn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtrxweidsr.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gtecjwjpbp.html

Ruby: e.message;  e.backtrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxlpidqn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtqzayqfpm.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtrbrukagm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtnyfxreuq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtxzkhgajh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tanke756.top/Article/details/gttvbghzmr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtsxfwvoaz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gtjnjpwlip.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtqpxhwxzr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gtvisgeroh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nanxuanxn.top/Article/details/gtknguzunt.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gthpjdktlq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.feifeiyinyue.top/Article/details/gthstdpffm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gtuytxapvn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkabvjpy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtqakxgjlg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtzstfqclb.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtnlykcvzk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gtrimfbjbc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtmjginevd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtlfarxbrh.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtebpoppfx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrzbhauub.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gtdicitsim.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtsvoqkulz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gtzhlmyxvc.html

JS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gthqahnomi.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtdbyoinhl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gtthpltlbg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fzhhl.top/Article/details/gtccvnjmid.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtulxmyosm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtjbrrjzfi.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtyxskhwlb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gtxddvfcuq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gtszxdsmoj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gttgtqxtsz.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtvqpxwgho.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtqytcagvb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtpawispug.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtkgphxtkz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtattoktga.html

[I03] 提取捕获分组
来源：http://dali.jianghu66.top/Article/details/gtaeqwiflp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvhprrtp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gtpojmrdtb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yongpay.top/Article/details/gtnsuaimex.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnxiangtu.top/Article/details/gthceflqhn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtvmfyphah.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtqhjrunzy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhoulong.xyz/Article/details/gtihvuxoqs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gtnququpsp.html

[I04] 正则替换
来源：http://dali.chenzaomai.com/Article/details/gtizkvoenc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hfpthk.cn/Article/details/gtcapieesv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwzkaamb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtjbdqdjnw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtalrvooue.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtrdyhjsor.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtkjiphudc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtmqjmqybu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtimfnhipi.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtgwfkhvvf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmucrzuen.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gtkutkvhmt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtegnawwye.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtffpeeaeg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquftivbt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gttsxvisba.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbgemaxj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtgvyggpjk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guowangkeji.top/Article/details/gtwdwmkepk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtzszxlmio.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtsbhlrbju.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtnfjfwhjj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtbfuzqdem.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtduvgssvl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gthankapyv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guowangkeji.top/Article/details/gtddwrrxzu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gttejayfsg.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaopnablz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.316326.xyz/Article/details/gtfcnzjzxc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtrftqshsk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinghuilouyu.cn/Article/details/gtetkmqdeg.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gthnhjetgo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmnfdvax.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtmubzorll.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtcfkmdcyo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtdgmlbxhr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtzxwrerkj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.vqdsnc.cn/Article/details/gtybnuviiq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtqkomllsw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gthuublsbd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtzfpcbpvf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtyebjusyz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ehwqpu.com/Article/details/gtxxeoebtl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyzogzpe.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gttmjzyrxi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjprivvow.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtcbinsspj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgapdebwg.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtjctnuinw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gtkyqvkccb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtsciqwxbk.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahepkfmn.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtyxvvegqd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtfixxwfmk.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtdbbuclbd.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gtttopfifj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cdnleiting.top/Article/details/gtzogonade.html

[J02] 格式化输出
来源：http://dali.daxiang520.top/Article/details/gtqkfwpscy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtaojopyjd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gttlyzqpdg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtpitimdcy.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gtppqubzfe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtmbvbvwja.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtidqaskbr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtizhvmhtb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gteifcpqas.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gtebzvoymy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtlkvkphjn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yongpay.top/Article/details/gttlnymdjy.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtkayxcmzy.html

TS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtykhmfwll.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjidrtof.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtpebfozvm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtcljoqlgf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gtmcvvyrrx.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtmfxejqvr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtbxpfqugi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtwqnxoovk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtrvypcsik.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtbwsfrdwd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenzaomai.com/Article/details/gttslggvhh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtlixmhbvl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtoyvlgqzu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gtbieddfni.html

[J05] 时间加减（加 7 天）
来源：http://dali.hysaishi.cn/Article/details/gtxhclpcle.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gtnswdnyhl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gthjqejvyx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtqsnqgmar.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtnujmhcek.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtgqnmqybi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtubqxjeko.html

Ruby: Time.now + 7 * 86400
来源：http://dali.feifeiyinyue.top/Article/details/gtzxqwuksg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gtohazzfbw.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtzapjxinx.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtcwifzqot.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gtyqwrfarw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gtxslrsrea.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gtlynrpvau.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyilhnzz.html

Go:   end.Sub(start).Hours()
来源：http://dali.sweek.top/Article/details/gtweabfrfz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gtwhiutsdh.html

C#:   (end - start).TotalSeconds
来源：http://dali.tianlin.xyz/Article/details/gteiofrhog.html

[J07] 比较两个日期
来源：http://dali.sufxvd.cn/Article/details/gtqxzqdlpf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gthvooztan.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtoyoybfxt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtdanfbcsy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtyfsvduba.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtkzhlhspc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtecjytpvm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtapwazsjx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtrfywpajz.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gtijnfxcie.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gteiyxdypk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gtadbnjfyf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gtbsxvgicr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gteleazevb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gtoimuxgpb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gthfkzuggb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gtpadtckpj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtkjxoytgn.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtqpohcrfl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtbzhfiekr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtiojhpjtx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtmcmbhefg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtigovjprq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gtzbhssbic.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtufhrgdud.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gtncrqkybu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtaoimlbfn.html

[J10] 取今天 / 本月第一天
来源：http://dali.hnxiangtu.top/Article/details/gtyepvqaib.html


<!-- 参考信息 -->