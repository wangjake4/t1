代发 wailian999

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtogjvhukl.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtqqbffyfh.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtvwlnekvg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gticfnkctd.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtiwlbppgj.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtjaqagyus.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gttxycpqld.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtaikdmijm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtmoycwfxc.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtaiyphmkv.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtxoimcrol.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtuqpurqbd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtpotqfwcr.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtmfqjhtkz.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gthmzvsbvm.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtzefgyuiz.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtbppmwvyt.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtgcdwtzlm.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtakvgfoej.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtswghcnxj.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtlfcuqqtg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevwqiden.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtvxjndixk.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtjgqhpfdm.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtltvlowwf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtrutuunmx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtxnylhwno.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gtiipkeoxd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gtveuhsotj.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtbmgrqmts.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gtjmwnoqjw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtcrryjacp.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtpolzlvqm.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtpgwxusiy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtdipbnlqc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxfhuxaop.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtzkfmlhsd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtxkbdbgfw.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtrpasbaez.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtkobhgewg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtrkzpkmpr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqhvltod.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtmtdliyph.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtmnebotgt.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtyaqemzdf.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gttvrmhrcf.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtksibkvwk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtpmtccvui.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtpjrkwpiy.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gthdewcwzg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtwufmawrd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlgnaepbv.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtqhtgmyco.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvylotojc.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtbvmynzbn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtqoxhdirs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtxjqugqai.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtwcqljbwx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gttrlgslpy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtenedffoh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtxejqbkvl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtswwcaddh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtwfjepcqf.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gtnresupoi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gtzqsnylff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtcpirvruy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbedflzeg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtecirflcb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtelvonguu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtmoftawed.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtbeoybeku.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtclldgubx.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtnesklcus.html

Py:   raise ValueError("错误信息")
来源：http://dali.fzhhl.top/Article/details/gtjtzrqsmt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtprhxzica.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtlgrkutit.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtawsafwzq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtxjhgnjcu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gtnddndhdx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gttsfstmnt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtzaqyibgb.html

[H04] 自定义异常类型
来源：http://dali.ehwqpu.com/Article/details/gtwrgzacst.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtjuwdzrnz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtcndpemfb.html

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gtzbemwcrq.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmoiuuhl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gteodiazco.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtbsgphxry.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtdxvhtdjt.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gtypbbxpcx.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gtjfkauqks.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtizpdlmtp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtpkrjokig.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrfwfyovo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtdvxgqarv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gttyedlkmb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtnxcbvsnq.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtzoueuhlm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkhhtxisu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gtptmptcgv.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtspizlbok.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtnaxsgqre.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtvbibghmk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtthsvfpmi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtfrexbkrt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jiagoushi.top/Article/details/gtyskykxuw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtdfjkjujl.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gthnwjyvmw.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gtijaxzwgb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gtzmaygdkr.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gteqxxktcq.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtvsndyviq.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtvnyappir.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gtnjgghoff.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtzffjqoii.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gttjmmcuzh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtrzixxbxw.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gtjoybshym.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtukejvlnn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gthbdnofal.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgfgphcf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbakkkwdf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtxgogcvpy.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gtesmvtvia.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtgmzmntwc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gtpzrhrtsv.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gtfegeippy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtmxhdltvz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gthfjnhfrg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfijtjzi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtpdcfdlgr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtczwukorj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwoiykuw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xziqi.cn/Article/details/gtcadmdlvr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gttsdrerag.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gtagodotmo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtzwjkhvac.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtlxyywbkm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtpweebzyh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaocqbte.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.316326.xyz/Article/details/gtgcvpmesf.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoajocmyr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtdpvugqmu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtvtrrsxqi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpxzcycok.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtgjacgejd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbhtpsseo.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtjebksubn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gturjpegex.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hammf.cn/Article/details/gtbkkxyavm.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtathrueib.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtyixfdnfe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtitphvcsm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtocbvjpzt.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtxvezogbv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtalgbrkxr.html

[I02] 提取所有匹配
来源：http://dali.sysykeji.top/Article/details/gtletkfloa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtfglfampy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtnoudwyhi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtarpvsghz.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gttyosoazz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtboijzspv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtkdwkrfmk.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtfkmiigpx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtjmcvfrsy.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtssnheccs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gtdsxfmeie.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtvvwaiymw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtddtzdgkw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpwnwico.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.snrcjt.cn/Article/details/gtxznamylr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nwbrower.top/Article/details/gtdvxaehrx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtowcqviwi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtzcdezhht.html

[I04] 正则替换
来源：http://dali.jyoumei.cn/Article/details/gtqekdsyfy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gttvsjtufq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtrbrrcxee.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtauidpazs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtfquryynw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gtisduesha.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ydzc1.top/Article/details/gtnxrhzhla.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtaezmuzzm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtiecwocvw.html

[I05] 按正则拆分
来源：http://dali.daria6918.cn/Article/details/gtzmtaltff.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gtjofmfuin.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjoguembc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtlueyfrsa.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtbvcipflj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqsuposg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gthrkmmrjk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtyjdtcjcd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gtqmhsaudg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzecornuu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtkkiejtll.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymmmkiis.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnjsdtqu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtqmvewlbo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtadzbhxrz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtmmimgwvb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangdashe.top/Article/details/gtnkkdmnri.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtzoiceaul.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtsrkgjhmy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtbufztpmg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtntkddqoo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzsjjfcr.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtwdmzdbeo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gthnheojol.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtdsqrggeo.html

Ruby: s.scan(/error/i)
来源：http://dali.xylfe.cn/Article/details/gtjaineovu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.fengsongda.top/Article/details/gtsgiiaqii.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtomsigsui.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuxming.cn/Article/details/gtduuwjxfm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtgzdiniqx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtxeortnhq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gthbliprgo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtvvbyynhm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cqqwz.cn/Article/details/gtfuvzzsyp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gtwnhqmjto.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtiwsynqav.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjendwjyy.html

J. 日期与时间
来源：http://dali.xziqi.cn/Article/details/gtilgwqgdo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyuxxelkd.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gtfxxyqhqm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jyoumei.cn/Article/details/gtyscposxr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gthexjqbsm.html

JS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtodoaetmf.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtqosmenbd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtwikfylry.html

Go:   time.Now()
来源：http://dali.yonumen.top/Article/details/gttarshyaq.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtyuxqyhsk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.c1oappe.top/Article/details/gtiqryknfs.html

[J02] 格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtuynqctcr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtznsaydlq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tanke756.top/Article/details/gtnjdeuvwr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtrhikwmag.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gtbtyjakmk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gtppyljmwx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gtrcrecagn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqebmhivw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gtuzkilmha.html

[J03] 字符串解析为日期
来源：http://dali.zhoulong.xyz/Article/details/gtkbxbtlyz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtkedvnrbs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtcerljvid.html

JS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtnhqlkrzh.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsfbekue.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtvrhwqkto.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtxhmsnsat.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtnbvvgrrt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtbnqzdtem.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtcvtxupan.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gthyqxtlhn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtgmlqjaav.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gaohongyu789.top/Article/details/gtslbeoiep.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuanzhike.top/Article/details/gtnqoasyxo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtycmjlixe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtshtinkok.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtqrexjhpw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtuwxnfdps.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gtwihroxvl.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gtlrcpjwew.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtydyhzafa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtxlfzrlnr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtykikglro.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtndiqcwua.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtroxnyjcg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gtougktblt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gtazmwoizv.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtfofmxcbv.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gtmedwvvfd.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtzhbbfnsl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.snrcjt.cn/Article/details/gthlkinkbn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.kuanghao11.cn/Article/details/gtluszrqvz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gtewpeecbi.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gtplbhhuvm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gtdulzzuaz.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gtmngjpehe.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gtqknbivnx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtjftezipl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtlgqbpvzz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gttqkyqjgx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtkoohnrfz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtfjoaoisj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtlccjmkku.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtrtxuojyt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtujxdmmma.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gthmfbexur.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gtdiewcuix.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtzontxrem.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gttzszwjdm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtnaqheddk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtmofnsuhq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuanzhike.top/Article/details/gtrabvxqbr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gtfgxairwh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtwozsfwom.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gttnpmtgsl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gtkiksvrns.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtcebydbcj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtbvlppter.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtplhkralp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hysaishi.cn/Article/details/gtmymkftku.html


<!-- 参考信息 -->