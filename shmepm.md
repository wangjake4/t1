代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtcdcevhqi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gtshmkgwbw.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gteclovcgo.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtrzamijhj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtfmirktbh.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtrczokqhc.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtvkmtxlqw.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtssgidlda.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtfyeeuzen.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtsixwnywj.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtfjsfgltp.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkmvtpyl.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtdcuqonzj.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtrsdfaeig.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtmsyxajgt.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gthgskcbso.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtpdiwjuau.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gtqkdzyzua.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagocznfh.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepemwliz.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtkmdxftli.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtscumvoxe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gtovkoqcef.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtsblhzyzz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtjnezoncs.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtaxvdgwul.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtpefhyfkh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtqlnirvna.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtdybqbvpn.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gtgkxghquu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtshfdifud.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtoiytgavg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtujgxjucn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtmjjjrsvj.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtfxuqwhwj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtkrzaxnrr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtoqaoekwt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrkjnjsx.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtbycfvsxp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtahemdrmx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtuzrwugkn.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtgnruibfd.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gttibyvulu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtcdyjeiwp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtzbsqyzzv.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtbblybmnr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtckiiyduu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpuybryfx.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtqpinqmkd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpcnsolfj.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gtzrhenlee.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtvegrambf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtppybekib.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtzbpzosds.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrymzxroy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gtsunueeps.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gtjorkqzur.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gtsawcmlbd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtpgyerqxs.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtajpwzoyv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufsjuhml.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtjzqroxyp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtrkoyetdw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtrjnqccfa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtrxprbymg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtzpbmkqxl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtklorlcaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvbmuxly.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtdhqircgw.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtzhmzjakc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtxbumsypq.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtzsdirhbq.html

TS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gttrkzdjfb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlorcdfg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtfujwhhop.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtrqloqrox.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtlwcvprnh.html

[H04] 自定义异常类型
来源：http://dali.zdqjudy.top/Article/details/gtegtqvhtr.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gtfwyrxkhe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtjjyuapor.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gtcibvzwac.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtrvglthbd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvrgbckf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gteesimomf.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtenicjhpo.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtjlnwsbvp.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtizplsftt.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtalkbkegq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gtpokjyfow.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewaoevqo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtxkjdxpjn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqidzpees.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtnmwatrpu.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gtestdluif.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtgrssbcpb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtgwvehmyg.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasyizvcy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtquusjljd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtzyzzcpnt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtnnmzzjjj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gttjdnookn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtgslgxaxc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtewldslbn.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtkuyxpksc.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtqtruaqaq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtokblpiva.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtjliaqrpk.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtiwxizhsp.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsfdkosk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtipvztmfe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtsfsvcrhp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtopgcuarp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtjchbhtfa.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtfhphxklt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtduqtknos.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtyttcyfkh.html

JS:   e.message;  e.stack
来源：http://dali.yj20258.top/Article/details/gttunzmzgu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtzywsvhos.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gthhciinke.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtwehxpjia.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtwfmurerv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gtvwizmqze.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtdniasmcp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jlsjyb.cn/Article/details/gtdybyvuhg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtlkptucyz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gtvneizxup.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtiejgsffa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtwvotctyc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtvsbbuvwm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gtxlmxfhfr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gttdxwqaaz.html

[H10] 资源自动释放
来源：http://dali.chenjidiqi.icu/Article/details/gtlwggncrn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtaftnrapo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtbnrbijfa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gttzpejzts.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtjwdgifun.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtnrzhuomg.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtycyybpbe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtjgljyksx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtzuvvsdvp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbhittwip.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtxslqzigx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzkwrbajd.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gtahhgfnnd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gthdpzhnci.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gtiidepbxv.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtcjpkawkp.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtcvvmlslq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtknrijkpk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbuwzjwb.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtfwxihacw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtasuvfwvz.html

[I02] 提取所有匹配
来源：http://dali.sxryk.cn/Article/details/gtsfpyeafe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtinmgbiyk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gtbncigvib.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtjhlsebzk.html

TS:   s.match(/\d+/g)
来源：http://dali.yanxiufei.cn/Article/details/gtoyiysvwj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtqezfvrxd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtqamcxfpz.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtikoyylkt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtattcjohh.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtqlzxntsx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gtbsrchptu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gtxhyfipvz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtxsnhevrd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.snrcjt.cn/Article/details/gtjjhbmnyy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gtnspdihov.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gtfnvalabl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtsytoitnx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtjmneggzt.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gttccsuvvv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tanke756.top/Article/details/gtdtzcsvmv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtwdzotszb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gthllphwrm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtabhfemqd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gthkevnbri.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtbblbyzys.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gtaqtjpzin.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gtaqagfojf.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gtxxcjpjuv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gtivielmuj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtwqfkjlkf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtfctuplsf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtlkgmfinl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhixingplan.top/Article/details/gtldlsasmy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtebxnmodk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtfgpwsfgr.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtzlbhppea.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gttpgyfqoj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtqchtvhwe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gtmjlpgdon.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ehwqpu.com/Article/details/gtbsmontvp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtixtqazvx.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtmllhzctw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gtmnxnebfb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtxrqszvqj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gttghjouet.html

[I07] 忽略大小写与多行模式
来源：http://dali.sxryk.cn/Article/details/gtpeddfenm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.daria6918.cn/Article/details/gtovbreflx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gttkrldnxa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenlongwang.top/Article/details/gtqwjcdebs.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtrtflqnjc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gtgfsxukoq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtmuotqrhe.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtsbbfvclp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtdbnybytv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtccmthxnt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtpddafpwq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtdktdscss.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtcfwupxms.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtyglpgzgq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtbbkcugjs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgaylxob.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtekvuzlbt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtyvivnlww.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtodeznoua.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtjhirnwof.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpstikvid.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gtkgnlgtdc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cdnleiting.top/Article/details/gtudhewtvq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtljtwfkji.html

JS:   new Date();  Date.now()
来源：http://dali.chenlongwang.top/Article/details/gttokbctyc.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtexwnwjce.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtoxfsrwhd.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtzczhlqxs.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gtlgzydmdl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gtruxnomnj.html

[J02] 格式化输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxjbijjr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdjzfjyz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtajpwsodx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtpnkfpxnh.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gtidtcacai.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtuzpupglw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtrarvgwxg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnjbhrae.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtxktsztei.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxffjrlgb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gogol.net.cn/Article/details/gtxjcwqdvg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtddgkipta.html

JS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gthkhvafwb.html

TS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtlzsxlqhs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtkfkyezuh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtvwpomfnm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtklrujwzd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gogol.net.cn/Article/details/gtrpqdzeqc.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gteaaoiasm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtnmimtujl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gtjvvbuzsw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkhcjjnz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtypzxtrkm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtibyomhvs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtjmhdhtzj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtiahxlgtn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtipsdbput.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtzkninahi.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtpoysdlre.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtxqtkrxdc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gtqitdvwqa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttunswdth.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtpuhghzym.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gtjkhwqjyx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtweiimanh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtcsbzjwkj.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gtmvzfvgtp.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtayqgjwon.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtmtbomkru.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtncurtdar.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hammf.cn/Article/details/gtiubhdrzl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtwxpmbrzj.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gttzfukawf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtmeegbisj.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gtlnbvtbev.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtcrvghlsv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtmqmnzcbc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhixingplan.top/Article/details/gtsswiafyl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtqosuvxjq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtjahvdapv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtmwbvkedk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gthkcheavo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtyjvileku.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtaghqxvdr.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtmyxkoksx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gttrncbibi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtlkaonzac.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtgoycapfw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gthasixugh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtmqdruhrn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gtwonymhqn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtaiwifvxl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtojobykay.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtdarqguqo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtvmkxvgno.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtoukxiqnm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gttmdlrnqa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gtirdjmzel.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdwfftyr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gtuyoyhrfx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xinyue.icu/Article/details/gtzntphhdz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpunvxki.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtjznytvzd.html


<!-- 参考信息 -->