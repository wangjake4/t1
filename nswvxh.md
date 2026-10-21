代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtaewwionw.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkewyujfq.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtnakqrdcm.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtnebxbzrg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtzwdkzjdb.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtdstojmsi.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtqlltlalw.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtflygrqoy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtrbejdzla.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gthmuodmdo.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttabvnwmz.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gtyrrpmltp.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtipsevnfa.html

PHP:  $u instanceof User
来源：http://dali.yuxming.cn/Article/details/gttukxfofr.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtxjykfgkg.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtrlgqroxp.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtzxxqcsoj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtnikmsxje.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtuthkpugu.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtvdjbozuz.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtqqscwctd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtpheywjvy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtepikughi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtopubognb.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gthkpcrasu.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtruosqiaf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtaruxwcgd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtxmnqtofp.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtsuxbfxmo.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gtqiplytor.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gtgdhrdqwn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtzlyqzxsi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtgprqyjpi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtsiujlzzh.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtuzckdaal.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gthwjqcqwk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycbtwytg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtlgvszygc.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtcjobeflu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtnomcbswb.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtiiplxnvz.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtofbexnsk.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtvcaniuiu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gtvjjcmcap.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gttlqkwcld.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtcpwgfnim.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtljvkesak.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvqopfouq.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gtoiaxhmle.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgjuawbtx.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gtcncubhag.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtgxlrdxkv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtkpmjaotn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtjdomxgva.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtafcwdxis.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtuwhufufh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gtpkrwtwes.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmffrxsi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj202588.top/Article/details/gtzxajotop.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtcjvpannc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gthwgmgpxy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtnvprsgey.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtssfiwfao.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtmtgqhylz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfsvouzph.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtisyvywcr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtkskxmdqb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gttfcydczy.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtoeroftlx.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtidxccriq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtreyuwnau.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtarxgesmi.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtvrljlsnq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtndiblppd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtgwecbiqd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwpasdsm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtpbtqworc.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtzrqadkme.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtjuaxuwih.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtjkwfgsxq.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghhbilqg.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqicxmpu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdeaehri.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtpvxqblvt.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtjkoseeqn.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gtvvfldycp.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzebyway.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtsofywcvw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gtskjqygzo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtximnzhfk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtwjuhytsb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtelbmwtyn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtveesezqh.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gtmbxyqlag.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gtttwwqxmm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gtxaceycfw.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtfpgxumyv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtiytjaqwd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtpfjxnkfo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtvptqdiqk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtkluodejs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tianlin.xyz/Article/details/gthrefblob.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jyoumei.cn/Article/details/gtfxcowiyw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtigydeexs.html

[H07] 断言
来源：http://dali.smart0.xyz/Article/details/gtvmonqjao.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtrrrpfbtf.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtifhljjrm.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtxtcihkyf.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtewoqzgdg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxinkj.top/Article/details/gtbvinszbe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtumrtihuc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtzzpgospn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtmynaukki.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gtywnfejbu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtxfjkydje.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtffwfbumn.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtgjlakmup.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtfxjjcvkv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gtmtyctdaa.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtujtbczoi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtmfcjmika.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtgcfdhckm.html

[H09] 带错误码的异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjotitfz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhtnzgbe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtcpzzvwzd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtqnnfdnwv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gtvaedxhtd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtugbbzsnc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gthejtyqtx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtahdsvsgv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtgtssanto.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gtjuyfnlkv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aibaodan.cn/Article/details/gtrqlvqjfs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ydzc1.top/Article/details/gtiewngfvr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtosczsudl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtfelcfkba.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtsdalfpuc.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtfryymymm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtfxjyljyf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtxilwunhm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqeetacve.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtwfyspvnj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyynhbxlu.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtwcovnztw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtnjgytjpa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtbrtwaxjr.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtbfgnumnd.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpbrftzy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtgtcwbsbn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozymctzq.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtlgcmfafb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtexwvmypf.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gtkliuurau.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtsghbqpnk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtrxlfhiei.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gtezyrsamb.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtavlraylg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gtxkitclgf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonvydudm.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gtokkjsmsz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtsfxowlxi.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtrvyzsynj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtwortrkbt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jqgfzy.top/Article/details/gtclrsuuvh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtiarsrdbp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtgmxkytlt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtggwpmbom.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hywenlv.cn/Article/details/gtajbrfgfc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gtzieqjvcf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtzhmfpvpi.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsqnbrqhd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gtqrttfjhi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtlklfaeqh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtyxlipaue.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gtptlpbluo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtfuzylhyy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gtawcqicvc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gtniathkba.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtrklddkws.html

[I05] 按正则拆分
来源：http://dali.quarkkingdee.top/Article/details/gtzpdqyrnd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtslkpapro.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtlqnvbums.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtgpdmtxih.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtvggibsmu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjobqtpi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gtugsxbatw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbrxwvua.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtynirlzgs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtacgcvwcy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtkjgoiazu.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gtrknhasvf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtpiyqwzge.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gttgxifiyp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtymnbhler.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.vqdsnc.cn/Article/details/gtptlmpeog.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtoxxokitk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtfhsbvgkd.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtbphpjofb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtbuaatgeb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hammf.cn/Article/details/gtrtgwjsoe.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtydtefhjx.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtakotsmns.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gtbspjnges.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gtocbdywpv.html

Ruby: s.scan(/error/i)
来源：http://dali.gzhubu.top/Article/details/gtlrqavjrn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtjrlpesst.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sxryk.cn/Article/details/gtbahscegt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gtglioonwk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtxefpbzao.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtinvytcun.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtlthvpiyu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtzingbmei.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gtdcfjsmni.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gtsncclana.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtqekuplad.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtnpmpthdo.html

J. 日期与时间
来源：http://dali.tanke756.top/Article/details/gtqlmulzlh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrdjqlkol.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gttbcyzldz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtykyndafa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gtqpbtgpkj.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gteyocplfb.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtpketiwjr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gtkwtczgum.html

Go:   time.Now()
来源：http://dali.hfpthk.cn/Article/details/gtoyodcpmv.html

Ruby: Time.now
来源：http://dali.jqgfzy.top/Article/details/gtuwhivvuc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gttsbguukz.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gttvddgutw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtvnamxctl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtycnpirhk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jyoumei.cn/Article/details/gtabvkwioy.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gtakitiaog.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtukepiwmr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtsslunabc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtvvztnoyh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yongpay.top/Article/details/gtwrwofrbf.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gtfferjzzx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtzgdrslpx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuetiantiany.cn/Article/details/gttlaszjmj.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtxcrylhgy.html

TS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtbuxxczcb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtzarjjydv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtcykshgzt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtaizmqqfg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.smart0.xyz/Article/details/gtaezsclit.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gtsyucozva.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtywxkvwmm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtttqgqmxj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aibaodan.cn/Article/details/gtsilnkfmb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtfhbckrzo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtmedywxaz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtmcpaawhl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gtuaczvgdr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtjvxahsbn.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtrymyrujf.html

Py:   now + timedelta(days=7)
来源：http://dali.nanxinkj.top/Article/details/gtjrhmirqr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtbvdsvnwd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gtbeulppit.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjphysti.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gtskshnbwp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.vqdsnc.cn/Article/details/gtjcapptwz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtngmnrwus.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtlzkvqihr.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkdybacz.html

Py:   (end - start).total_seconds()
来源：http://dali.cdnleiting.top/Article/details/gtcxgnzics.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtfoczbiac.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gotoacloud.top/Article/details/gtannmvrfs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gtudltlkcy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuanzhike.top/Article/details/gtrayipxqi.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenjidiqi.icu/Article/details/gtztzflkas.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtqkvbjfah.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtbukgqijm.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtgmevtwpb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtedofoydy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gteokvqghu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtmxssxcwz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtnvqgtqax.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gtysnkhcbw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtbgoqibbv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gthmcclqza.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gtzounhliu.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtxcsxmvab.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuhjqgfy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtsipqfhol.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gtyfaiirpd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gthuwuwbgx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtveepaewr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtwaypzfpj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gttqiabsur.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtgkqwzmxb.html

[J09] 时区处理
来源：http://dali.ivvv.top/Article/details/gtjovupjtk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gtdbctrxgx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtuqxircui.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtczmplayx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtptdpxddn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtvklascfz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.bjfxy.top/Article/details/gtioiqrfpr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtcbzpjgyj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtsyjkewuc.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gthzpwmaku.html


<!-- 参考信息 -->