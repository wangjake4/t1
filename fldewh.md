代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtlafixias.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtticnperv.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrumaisl.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtscmndonh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtzqhypdfo.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtwxfevhjp.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gthztcxkwb.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtofhimtld.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtnjmpqcea.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtsedphpsc.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtpmbtixer.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gtkssksfun.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtzgxczumx.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtaufhzavf.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtdqqlzyzf.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtfuxbfstc.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtpukbxmmr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtqoibluqt.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtacyoqgjp.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtlfxltbzg.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtzbcgegsn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtkitxcynq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtaecflopa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtojqvmgbg.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtopvuenio.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtkqkltowb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shzxlz.cn/Article/details/gtgekioxpr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtejmudyto.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gtwxqiirek.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtjhzmxmjy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gttwmwvfti.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gtvhzslbpq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtpzqzwkyb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvvddois.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtxkpcsefa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtawcxpkxp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gtnaitozbx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtyppjkofk.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gtsiqfvckr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gtvmsjeutw.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtqwgplmkm.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtpscevwgu.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtcljxuykf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtkzofssuj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gthfngbyan.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtvktzxosq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtegikkfzu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmnutyhow.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtxsrdxwgp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxpnlwpt.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtkbbgfwxr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtjizzvzoi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlikcqgrh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gthysnezhg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtprljljql.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtujoxsxoc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtsyzsqymm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gtojytxkch.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtbkrbyyzf.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtkratnbhm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtsnurupum.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtdkcdeaao.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtnxdxsgim.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtdgcbwofy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtgckhmhfl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtpxadgfwt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtzcdpllrx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtznyuwvxj.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtetrvgvje.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gtsyiktuae.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtuprmxzwr.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtahtivduw.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtharvjhyj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtdmepwrws.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtsycsbqgq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtlrurjdhp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtdwbiroxy.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gttrsbfkbd.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtvscqkdpp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gthrwdhtrk.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthbxxzost.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtsdzhkvsj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtsnrgdqxb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gtrtyiwncs.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtsedoebib.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtqhtifxll.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gttrvfxmph.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtbbckxisu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtgrfewbdz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtpclvaebe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtdlptecbt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtgmkpomwf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gttrwjpfbi.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtdinepafg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtmobhqqyf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtfjxturyy.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtzedxfdph.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtieyckurq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtwojjvhun.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtvksqvdpz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtqinvcdfp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtdmocptwb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtawqgnthr.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtcxupuofi.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gthknztnmg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gtolnevobb.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgugkhgkq.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtshfjlfll.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gttzbefgzq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gtbollghcu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtcamgloyt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gttwmaykve.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtngajpfuz.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gthpipsaca.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pycfn.com/Article/details/gtnsstiunz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gtdyhqbruv.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtdicijkdy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtkrqamoek.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtlqxzzsse.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtkzmqzuez.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtiklxusux.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gttyldiilb.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtuagsgkmn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gtsqkgpczc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtppkjfezd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtjlwinydm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtdtximgro.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtokotqlge.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jiagoushi.top/Article/details/gtqtzmumtl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.kuanghao11.cn/Article/details/gtcsvpndja.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtpbvxbuna.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtlwcflzks.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gthqtldogs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtbzgsrrzh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtanhpalnp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtfrepcafk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gtcezvylyr.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gtjkslmcan.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtsalalwzk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuanzx.com/Article/details/gttssgzppm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpaozhppl.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtxkpwjjjc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfgqkwxpx.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtufixoeie.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndwpodyh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtdlrhtgyr.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtwvietvgp.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtuxsxtlod.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtdtvlzaqn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtzstdyhoc.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtkutznayj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjhbtqca.html

[I02] 提取所有匹配
来源：http://dali.yangfankeji.com/Article/details/gtwcxtmqet.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtctxvurxn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtvgwdmatb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtiatewsoz.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gtgfwcxflc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtpzerlozc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtuamlnwqp.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdlevihp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtldinwexb.html

[I03] 提取捕获分组
来源：http://dali.haohaochexian.top/Article/details/gtngnfgihk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtpifeywmk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtedermxvq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gtibbqzsyu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtcugyshae.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtkcrcgkcc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gtalfpttih.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtklkycktx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gtdyxzgmyh.html

[I04] 正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtzufjpvgy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsftisso.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtdwfthzpn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtbiznfjit.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aibaodan.cn/Article/details/gtxznggoon.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gtdlxfiqtv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtizlbjfno.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.pycfn.com/Article/details/gtyfwrrrbm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtqqtfubbp.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtytzscbmt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gtrydvghvb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtkiqssjid.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtdjaugakf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtnpupmsun.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtiatssktn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.daria6918.cn/Article/details/gtlekgexkg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhloexvm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtjyetozci.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtgrwnbscl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtbfjvvoiy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gteexneaxr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtiskoszcl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtkfktdnid.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gtymjqbriz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gogol.net.cn/Article/details/gtyqhuexef.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gthokldwht.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtqwhzzwsc.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtfgihyomx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenlongwang.top/Article/details/gtblpyyfmc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ivvv.top/Article/details/gtzpfieklk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtumhrdtmr.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtknhxnswg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jyoumei.cn/Article/details/gtjphtdini.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtjgacisaf.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtqwpvnaeu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gtyunstjvo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gtqxcdncjq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtocagrwyi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtyrqgryss.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtrfxfzqap.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gtudwtbckn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtjtzftses.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gtjhfefcuj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gtlnbvigex.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gtjhvdodrj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfzvnyzyg.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtqgdwmgpy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtttqlpniv.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtxappufeh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtotjvulai.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtfxssbctw.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gtmdwcqbzn.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyspnnqd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yvedp.cn/Article/details/gtnxwazyuz.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtoqsgshls.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gthaapstil.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtcjpreqec.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtskogvqyr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtnfxhcelg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtoekmotti.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtcvtbjzrw.html

TS:   d.toISOString()
来源：http://dali.gotoacloud.top/Article/details/gtfctrbeqc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gthvbsnlvb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtgihgrglk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfysidwtu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.andypj.xyz/Article/details/gtredhculi.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtpgaaalqc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtohkvuatb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hammf.cn/Article/details/gtcliyyznz.html

JS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtkmfjepck.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlfkfmsl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgbmjqab.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtuktqrkal.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gttjrylqjo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gtcbdjtpkl.html

[J04] 时间戳与日期互转
来源：http://dali.chenlongwang.top/Article/details/gtrgsqkydb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtzsxealqf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqpjhprn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtllyxvuxv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtfnvihvsi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtgwepqjqg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtxzewtbyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gthwunffyd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtitvjlmgk.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gtpbamqgmi.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gtpvwkxzkh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtskronhlt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtvbhkeqqg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqfgpcph.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gtylljaaru.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gthomoqdpa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gtuchumsbs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtlepjsnle.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtepijjuot.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtatabyeji.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gtqlgbdujh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtodqoioiv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtpbquvizd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtopoapqwp.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gtqrxievxf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gteexqfwxj.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gtcyrweemp.html

[J07] 比较两个日期
来源：http://dali.fzhhl.top/Article/details/gttzxykvuc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtuopyptci.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.meibo888.top/Article/details/gtdmksltir.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtzmkinpvz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtezhatutn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtrqohndyk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtoypsccov.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtanicxfjy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcfnuzbr.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtwdemmqoh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtjbwfdwgr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtqcbbjeja.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtzlrjqaos.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtxwagnhha.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gtvkaxcewv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtzrbqfepv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtxgscmpql.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtzqkdlifd.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gtgdvayudj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtwgmzrpyf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gthhscnohs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtkgyqevov.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtwrvmwnll.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtaxwvevpl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdzngjqb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtgmcclkhf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtgvdcoszn.html

[J10] 取今天 / 本月第一天
来源：http://dali.jiagoushi.top/Article/details/gthnnvldxs.html


<!-- 参考信息 -->