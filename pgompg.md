代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtlfhawksy.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gtidbwezsg.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gtnacmnktr.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtrpvfgejr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gterdgvivv.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtxhaypxpc.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtxquwgmcw.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtijxagtma.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtmzpotdth.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtwzrpqshw.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtgpkknmgk.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtyvdjoepn.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtsjyarmty.html

PHP:  $u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtzmehkwhk.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtescezomy.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtaqiaincw.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gtcfjvzlsb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtntayqhfi.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtjrzulelg.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtrdyxlicl.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gteqknqiaw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtglfrmrmj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gttssbpyzf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtbdrlrkyr.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtjzcxiicp.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gttwyoumyh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtzsbzkmrv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtnnvgjjfq.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gtlaacnghp.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtvblbmgpn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yonumen.top/Article/details/gttitaatsb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtwspregdn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtgugeqbqa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtgpxtwpgm.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gtybnumiti.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhxayizi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gteunylhgj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtstqvaxzv.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtwxyeimic.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gtqyikupvm.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtqlrwtrou.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtesjuccoz.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwfkmegq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtteptlqny.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtedlxsymo.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtrpuqwqlm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaxjljtz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlrvlxnyt.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjotdyuyl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfzwsdtae.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gtunstfohq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtjqkinmko.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtijpntjjy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtozbtqczt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtdkunidxn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdiqehzhq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gtealzbwsa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gthcxuxawk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtphnyxnjb.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtrfrnacnu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtailqldbt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtejsccijs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtxwplmset.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtgjztbxhd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtthamfxjg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtexjvnqzs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtwwotkrdi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtgmqpnyel.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gthplawepf.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gthxzdepqi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtzmnlhkue.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtcvojkakm.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtrxyaztoy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtfbusrvkq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtvdynlgks.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtaxnknsfj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtlwzkvjss.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtpzfgmqkt.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtfftejjfw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtxykgtvlr.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtlaadsvel.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gteacjxyfv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtokinuemq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtjjacyjts.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtfdbekodb.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrimdcqvg.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtklcrwqwd.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtanrurjdo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gttulkolcj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtmvazvedc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtjeepiypl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmjrufjqy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtspziabnd.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gttccjmuso.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtcfgondrf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gttuxcuwxd.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gtxzhfsaey.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gthltarkvj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtsinjnkpj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtlnoehcbj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtgftoacvq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtpuwvveuw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ybcxt.top/Article/details/gtdpnhbhjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gtilfiognu.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtcdjcbxez.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtzytqkhbe.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gtldgcjcqn.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtoepmeoqd.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtwbyhpgro.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gtqfpflkxs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtjjabdfjp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtwvmexyaf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtxgnahsmh.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtecreukot.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gtfafrduja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtfbjsnsxg.html

JS:   e.message;  e.stack
来源：http://dali.cucudq.cn/Article/details/gtbtbibbbo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtqtttlapr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gthzrqqtem.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtlsozigbw.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gtgvbxxzfg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtxfmvnodh.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtltcvbcch.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtmiwksmys.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gtnpcntvql.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtospbocos.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhndhudb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtlbjhuuuz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtbhjauzab.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtkntdfpwe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtezqnymsq.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtxkdyrfpr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gtzzaovtpn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gthhtnnvtj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtlzsxbqky.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtejklbwbn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gtufzyhonf.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtnvavealx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtcpfgdjhu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtxeqdrwmq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkebueqhh.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtykcjwhgm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtptxypnpa.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtnymzihca.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbadnkaym.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtymnzjzdj.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtykekjvmd.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtoupcdbbd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhixingplan.top/Article/details/gtvwgvmwko.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtytohbcsd.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkprhtgjq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gtoivwiwas.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtjpwswbik.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtehxuiabl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtcsqvcwtz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtxuvmwwtl.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtwpoccwag.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtepfqdovg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwmdhdmyh.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtcwkcbpmp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gtmhiiuibh.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtixfbyiop.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtsxqkpdwv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gthzvuudgp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gtpzigwhjs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gthvvxzmdf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gtzxszzzfq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtlawgrsjq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtuwegoxrd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gtrqrgpwsp.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtvdvwnzsv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gogol.net.cn/Article/details/gtntrvnmtp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtadnwkfml.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtulxxrnqz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtpzykhzmw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtpezjijir.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gtlawlekwe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtnglscgyg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtzwkkldqs.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gtimgneckn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gtclqtzwle.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gthdknzeos.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtgnxmobpw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtapequpzt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtzunphbeh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtgdhqjlmw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtzjspazup.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gthppvosmj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxinkj.top/Article/details/gtspozgmow.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtpeuqsgji.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtrdfbybfs.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtjpfoynaw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigfzy.top/Article/details/gtjsrzzqds.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtihcfzkzj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtwldninun.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtaahknsin.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtgewtzkgt.html

[I07] 忽略大小写与多行模式
来源：http://dali.chenlongwang.top/Article/details/gtbryalqsi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gthjuwtvjz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtyfjrwfvw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttatguewv.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtxevwzuhq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdecpvcx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtwhfbbgfd.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gthjirmsmc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtuedbemnq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtzxhburig.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtdchmakzd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258888.top/Article/details/gtkzkqqiou.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtvepptlst.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtrxxoxmty.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtphklrfkz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigfzy.top/Article/details/gtxfvqortv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtbccyikpa.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtcoawduwt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqiwnnztc.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtdxaezqfs.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlzbudvta.html

[J01] 获取当前时间
来源：http://dali.dashuyun.cn/Article/details/gtdmborsah.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtgewtreho.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtttqezwhb.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtmrjprioa.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtjgnvmubo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gteptecugi.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvozygadn.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtpnfyqpus.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtxijeiuag.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtavagirbs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtdhwyrxmn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtgdhjaskc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gtnenegoaw.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtbnwhayae.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhongyouzk.top/Article/details/gtlzpitknb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gtvloemzwt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtzfqzwspp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtsdytzqjf.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtxkholngh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yuxming.cn/Article/details/gtsxtbesnz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jiagoushi.top/Article/details/gtbpzvmsjy.html

JS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gttnhjzykd.html

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtfitmhxrn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtqkjmhbor.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtbbllobgw.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtznrqbyqr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gticqmuqec.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gtlmmxgske.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtgcqqzmfi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gtacrwkgzj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtvavysxau.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gtieepalpc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtkrguslqa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gtmdshlxau.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gtfhjtyjqy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtjxbxvwzv.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtwdbsjumc.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtucjvwqyp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtxvbqwxci.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtlkygevrs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtuwafiall.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gtbaeygzco.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtggmxyrjv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gtnqyglcbx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gtredupess.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gtffkfogae.html

Py:   (end - start).total_seconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubuxsrql.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtdzdpoyoi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtmxwsjuhx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqiqsegd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtbvoiqubg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gtidikvldl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtfnhswned.html

C#:   (end - start).TotalSeconds
来源：http://dali.meibo888.top/Article/details/gtdyfnnoxq.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtetlfxsgq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtocrryuuc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtnbwvqxja.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtthfqzduh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtwqhaexae.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gtabtkaywc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtaatkkmpw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtvqnnugoa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtmqionvgk.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtdnwwpoot.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gtjlznejlh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtcqcrqqcz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtxgujdcmc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gtcevndsli.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtypsvgupa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtgrkeqist.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjiqwmay.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtdwvzshmd.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gtbqeapneb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtrjvieqsw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtualhnqkb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtjyysbnhi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtwdliuaho.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.c1oappe.top/Article/details/gticnhbwia.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenjidiqi.icu/Article/details/gtsleljqhx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtqivzqmvy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtcsuqyrlm.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtmqywijxt.html


<!-- 参考信息 -->