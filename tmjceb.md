代发 wailian999

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtiutvcbbp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtpyzjkftk.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtuwlkngoe.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtoxkcblpz.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtfkwjkjjw.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtktauutpv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gteyxkpvem.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrxsddel.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzmlfgut.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtnumxvair.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtavjrhuyb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtpnagvvqm.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtvnzfegdr.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtheyssjag.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtwtonqkzs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtjsnkxvol.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtzkmdevzk.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtqnaonegx.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtgzympjat.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtbtnraowh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtimyogibw.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtvgesxoid.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjlcrikod.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtoeeevgjb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtxouwtkgk.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtzbqvafdy.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtnejmvdxg.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjinrprno.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtnouzwcfw.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtmqhoycqa.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtsxnogkkl.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtxpvrvyqq.html

Java: u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtsyvwxofm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtlaywwszg.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtpbvmmboj.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlvjpblv.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtqgchukwv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gtkohwrfql.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvqhhjit.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtpsnjtxta.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtmagdzdyc.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtailikygs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtmwjczvgq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtlkvokszq.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtagdaqjxx.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gtmkuypozi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gtezmtoskv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gtshpgbecf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtcfwmercn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtukqrhaoj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtvgdqcanc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gthhccvzyj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtpcqkpnzn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtghvdgzgw.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gtnjcmfolg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtivbganzv.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtaeedhiih.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtfctufpww.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtgqoiplrj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtqporsubv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtedrkewvt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtqirkamya.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtqyglxjdl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfjwrnfii.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtqhsnbbgp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtakliklgv.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gthpqxpguk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtdzesagij.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ivvv.top/Article/details/gtxbjdezik.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtqclmyhlt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtuuxlgyvq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gtqpnkqjwd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gtiwpudepq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtpmggeauc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtbqiaybkg.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtccapppnr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yonumen.top/Article/details/gtrarawkwb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtzkvlggtk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtcbxojqen.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtttyglgfo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gttlzlzgda.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlqnrpse.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtzxjhcmxy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtojadsflq.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtldvcuwxc.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtxgzdpaez.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtihykxujz.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtviccrntr.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gthhbxeuus.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gttvikralj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtnaqoipfa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtgbstrnuz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtqlfwnblu.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtxtllfvry.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtkcmmxfen.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtkrrwcuyz.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtbahtihvm.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwnvpxtfn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtwvmzvaee.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gtasxnnnsp.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtztlmwdre.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzzzsjip.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtkwagaltu.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtgeysmlay.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gtdparjwaz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gthejvlqdt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaaradaj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtomrqzifh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gtapapzgwz.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gtklqpsvhx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtaqxhirvk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtzmklswpj.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gthtcyassf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtubeylygd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtsfgvwpts.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtelnrbstc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jianghu66.top/Article/details/gtiguvcqbg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtvsilvscx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtlcgabxbs.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gtuasnfdyk.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gtlunkixsp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtmxuqxggr.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gtouchlxcp.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtappgiqzk.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtjwimqdum.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gtednjmbsm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtygephdei.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fzhhl.top/Article/details/gthpswivpx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpixvkmdg.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gticuwtuxm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtzmspbsaw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtauogrrmj.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gthkbtpudu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbefjaaw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtnuonzvzk.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gteglssmjv.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtbbllbhfr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gtnrrhgnhi.html

[H09] 带错误码的异常
来源：http://dali.xuanzx.com/Article/details/gtamzujhfh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gtwtabdjej.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtdbrofxjz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtcvyjnvzr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gtnagbyylw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtuhusqkiz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtsatneozc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtoblrqtxn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtqeobkwbd.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gtvyahyozt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtqecojajx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtluwusbbp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtgrktugqf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtlitimvys.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtwbclkyst.html

Go:   defer f.Close()
来源：http://dali.sxryk.cn/Article/details/gtlqgbtkkm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jlsjyb.cn/Article/details/gtumutwgsu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtxiehbkpb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtudjbycsk.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtyzmsyscz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwjvxgasi.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtblnhhais.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtsvazktde.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtgbhiydiz.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtypmqiyru.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtlcotmbhl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtvzwryxpe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xziqi.cn/Article/details/gtpzyybmyd.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtobcjrxfa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtpcioozvu.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtuhpcevul.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiflwlyfz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.quarkkingdee.top/Article/details/gtptsyfoby.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtinmksvgb.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gtrwactbcz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtzafybodq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gtksodsmbl.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtlfwulgpr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtcvotclhb.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gtkqjoocaf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gthkzmhkzi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtjcddyeuu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtmsgoentp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtlbrkqdpj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtlfhzzamf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtpzqhojwx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gtyrfrvlod.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xuetiantiany.cn/Article/details/gtkcdbpubi.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gtawbdntmb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gtappudxvj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaoobfvm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtdddjgtni.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthldsjzyu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gterskinns.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.haohaochexian.top/Article/details/gtguvdhpjz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gtzlgzfdkv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtcivaevwn.html

[I05] 按正则拆分
来源：http://dali.yanxiufei.cn/Article/details/gtrdhirueq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtundidzhz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtqdfrtofp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtudeyvawe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtuvzzjzbq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gtyigeczzt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtqebfunhe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtqdjofgjq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xylfe.cn/Article/details/gtsyjffswf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtofwtbzng.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.birdmap.top/Article/details/gtthbgewit.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.guannengcc.top/Article/details/gtqqkcynkl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gtbxpvazmc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhilpnzo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gttaisqibz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinqigufen.top/Article/details/gtrfedpnzj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtnawhtxzp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtrgnfljnc.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtghsxlqfj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gtonbxejfb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtnbnozgpd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbfujbpa.html

TS:   /error/gim
来源：http://dali.gotoacloud.top/Article/details/gtnkpoodqe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gzhubu.top/Article/details/gtbwbeiqxd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gtornyegxy.html

Ruby: s.scan(/error/i)
来源：http://dali.sxryk.cn/Article/details/gteteaagvi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hongshengwenyu.top/Article/details/gtkmwfhxns.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gtfzutwxov.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pengpengdd.cyou/Article/details/gttsntidej.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gthmifklyt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtvryrjteh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtwefdqczr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtdompvzwp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gtbsnqdbvg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gticvgiyrv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtcjghjcjl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtphptteem.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtwwhjlvtb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttxzorgpz.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtkpgjlvgz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtiptiirxv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtwjloiunu.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtmzrobabu.html

TS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtuxxikmkh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ppjwa.cn/Article/details/gtvrgpoikj.html

Go:   time.Now()
来源：http://dali.fzhhl.top/Article/details/gtaqeowgsn.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtrpcljmat.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zycfv.cn/Article/details/gtrpxdkpwg.html

[J02] 格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtszdvllfa.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtqstmdmtl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gtyfeytsbk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gtqmzbviqk.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gtuvgtqwwi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtrigckqgr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gtdbokyksy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtsnamqxld.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ybcxt.top/Article/details/gttuplhtcg.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtxuynalsi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtxsimbzlp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsffccwbf.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtbmalnubq.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtsgunavnr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtrjbqtocq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthffegnzz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtpcygystw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtywvzevww.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtijdwgdfa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258888.top/Article/details/gtgnmdcqgv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtvfrwnhqg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gtoyrcfjqe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gtfjjdxwqw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtnctrpvfe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtfxvpyvrt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtxvqafpcm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtvxcjgeiz.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gtonpvkpzr.html

Py:   now + timedelta(days=7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzmwavlm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamdzgpyo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtuxxbludx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtrapjfjnk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.havefunace.top/Article/details/gtcfbpfriq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hammf.cn/Article/details/gtrsrepqqf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gtqhoyxnrg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtxqavbrox.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gtksohmvvc.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtrhnlpmwl.html

PHP:  $end->diff($start)->days;
来源：http://dali.gzhubu.top/Article/details/gtgzgyaydn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guowangkeji.top/Article/details/gtrzcavile.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gtawusurkh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gtowzxkekk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtlccblznu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gtisqnsnci.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtjgcbcmor.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gthiyvpqri.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtezdjrmir.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtdzrwbult.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtnhawjziv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtpzttrmtc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuvyquqp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gtvcxacziq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtvmkxrlsi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtppdajftn.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gtwgaizxcb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtzjqhnqer.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtnzewyfau.html


<!-- 参考信息 -->