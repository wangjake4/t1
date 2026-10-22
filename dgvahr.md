代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtkgmzttys.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmcwsloo.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtpbnakkpj.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gtwnwdsmue.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtrrvuvhjj.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtddqfftes.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrkujtoe.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtshwfiudd.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtidhrfbgo.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtwvpornll.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtjjvuyioo.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtlccwlzlv.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtoiwrzrzr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtkvxlkyym.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtizksdkui.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gtqkxomtah.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gtdkxlgxvf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtuxyjtuyv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtahjqwcbg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gtmdrwhsjy.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gteysyuxoy.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtpmuarszb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtcxvdfjvl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gtlvpvaxhs.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtmwtzifgw.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtltnzpkvv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.316326.xyz/Article/details/gtinxlslix.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtrdppwewf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtnlajhcii.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtsxohxciw.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtbjpsftqb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtehtdzuxn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gtspgvhqwo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtutfzviej.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtthcsextm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtvrhqookf.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gtgtrzpzow.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtmzwmvsmi.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtjflypyfb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gtixzzkqag.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gtvpvyouud.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gttixnkrib.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtvwuwndpr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcjmcyvcy.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpfesdrx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfcmzepoq.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtdekhnvdw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtejwlgokm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtjdvrjbhs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtmuuszwbm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtrxlbjeti.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gtfanvyajg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gteiuqvqwy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtzohplukl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtlezevajw.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtztzpeivc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtznnsagfw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtyyflmoxl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gthgzffzqq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gthkyjvoli.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gthjvanewm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.svipenyu.cn/Article/details/gtfiaoebmb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtszfmqdeo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtyqjylezx.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtpffovqhg.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkziekmk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtjqarmgkz.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtjpkqwlfv.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtlrexmjxk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtgxasavvy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtkhbfqwei.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtppmbkptr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtbjcqmvlg.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtbchsuqky.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtamiaektf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gtoztpplfx.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdtlnqgjy.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtkujxudtt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtljbgxric.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtfqnafqjw.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtoyrndunu.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtgjlzqirm.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gtmzhmrvjz.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gtfmzhnlpa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtkjelpmpz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtqwqwcszq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gttpxwkeuu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtpbtfnzil.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gtwpigikev.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtzxbzxhxd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xziqi.cn/Article/details/gtvskscpir.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gttoimsyis.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtfkrhfvzw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtzycnddmd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtdkyrkoen.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtwxuywned.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtohetdnvf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtzioxgrnu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtyhzlgtgh.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtckglcevc.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gticqtvhsf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtlfttzbgc.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtppxigcvl.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtfqpoqzws.html

TS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtbilccltx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtvkphgido.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gtzsbxwdtq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtccyyhzce.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtbxxjwgeu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtawshwppu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gogol.net.cn/Article/details/gtlvlmplkf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtqwojktnp.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtbslcddwe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtbmjtnokj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtlfaykcsw.html

Go:   err.Error()
来源：http://dali.ivvv.top/Article/details/gtxyvdztdv.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtlcsjpool.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtyerpxved.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gthdeqgkcm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gtajppiimh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtztyhdwyj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtvdnepfgx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtxvbkopxl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtxzujiihj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gtdoinnvac.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtejstncop.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtrvwwdbwu.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtvbdxknon.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtxfuydqen.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gthjlwqgma.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtgipsisux.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtrnnruykb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtfddhudjk.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtpozlnbce.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtesserx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtobnaqcwe.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnudhbkbf.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gtwvarobao.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrhpifyie.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gttrciglwb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtfcwfqhur.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtbxrqguro.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gttqylyrbz.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gthcdxbhhk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtbkgdxwgt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gtplorljwr.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtotnaoabw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtrwshreou.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtnuicofuy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gtvzvojiyx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daxiang520.top/Article/details/gthsqlfpaz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtdouuippc.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtqutaowol.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gthblirjib.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtyxymzmon.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtrbbnaknt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gteemzvbge.html

[I03] 提取捕获分组
来源：http://dali.yangfankeji.com/Article/details/gtoegpswph.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.haohaochexian.top/Article/details/gtveunmlcf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xylfe.cn/Article/details/gtlymdffxk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmzdxdmk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenjidiqi.icu/Article/details/gteshjtfsa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtygyyoviw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtjrwjaefd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtpuurdxhb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gtjdkbbajl.html

[I04] 正则替换
来源：http://dali.jiagoushi.top/Article/details/gtketrqbue.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnxiangtu.top/Article/details/gtywsmihse.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gthrzvdsix.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtlzlwfptr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtpkrhingn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gtlijgujbr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gtqhbfoywx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtiisnysuh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtufpavrcp.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtvbagqeux.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtmnjvygja.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtnqotpxxw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtuxqwrdze.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtzponootn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hammf.cn/Article/details/gtginqsyov.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.316326.xyz/Article/details/gtwvoigbnr.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrayrjjam.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtcvahgatq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtacjxcsnv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtyxksofua.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ehwqpu.com/Article/details/gtcchrybfn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtqjnyaivf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ppjwa.cn/Article/details/gtysgmqyve.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtcnpkrnye.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtcnimnglj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtuiguvrso.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgdobirs.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gtlxbamenh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gtswhahpge.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gthgtxyjmf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fengsongda.top/Article/details/gtlarvthct.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gtyuzpxcjt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gttiniukaj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtnrdevmyu.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtimrhojxn.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtzcbpzmuw.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtvqhyvsjh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtkgwsiwpa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtferpwqrw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtwhuijots.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtpuewsjzd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtmntrplmw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtlswphtbj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtyorzxucr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gttivzyuqd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtuftmxplo.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtfgnekrmk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtymicktqh.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gthdirnamb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yueranfly.top/Article/details/gtskmzecbd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gtjvjndpzv.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gthkiptygn.html

TS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gttwhaessz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtjgrbrpmp.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gthmuuwvku.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtkslajapc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gtwbhmjpun.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gthewexrhy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gtpahrimcq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtqexccrub.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.meibo888.top/Article/details/gtnywrsoji.html

TS:   d.toISOString()
来源：http://dali.feifeiyinyue.top/Article/details/gtoificfos.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtnocglupq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gtvoaeddzn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtfkxgxbxl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gtvanljrhu.html

[J03] 字符串解析为日期
来源：http://dali.shangyingyoupin.top/Article/details/gtecgasvno.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangshuangyany.cn/Article/details/gtdynthnut.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcuujcbp.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gthkqcjmtx.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtffdakfij.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtraemyckl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtcxecajty.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gthxdehqsm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cdnleiting.top/Article/details/gtvukdnwfj.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtdnfepioo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtllqrcbyt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gtwvgpuiwa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gthcipnxkh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtqcrcycbz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtjyuklkys.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtvdguikfx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258888.top/Article/details/gtdjsvqtti.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtfshmgubo.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gtjxaoldgx.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtppcubjfa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gtisujawte.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.andypj.xyz/Article/details/gtopbefukf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtymdorszo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmifjvjsb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tian-w.cn/Article/details/gtahpplazv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gttagwpgel.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtxmawsdlm.html

[J06] 计算两时间之差
来源：http://dali.jinqigfzy.top/Article/details/gtbagiddxk.html

Py:   (end - start).total_seconds()
来源：http://dali.tianlin.xyz/Article/details/gthpibqqxm.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtjscameak.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gtreevtzei.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtvhqvcmcs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gtbhuhfimn.html

Go:   end.Sub(start).Hours()
来源：http://dali.bjfxy.top/Article/details/gtwweonnai.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gtpsaibtkt.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtttslhmfb.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gthemnogzd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtuvmmknoa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtrwhmgctk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtpknitcrw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtfcmotuux.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yj20258888.top/Article/details/gtyrzghxjf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtzvpkdzrx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtsqikyajb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtzxruxacv.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gtaairside.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gtykgknarc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtgfzzgzwz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xylfe.cn/Article/details/gtdrmrwifj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jianghu66.top/Article/details/gtjwqddwfw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtkwyhjqnh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtvvtvggvw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtarjgspri.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gteqqllvop.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtctfrqtmw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtczqivkpe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjuxgqch.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxrmhzme.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtlqsnehna.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.0kj1m.cn/Article/details/gtedwbpsvk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gtsdhfjkkj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkfgbpbr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtfmqbbezm.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtvdmfcnww.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gtxlpeiatd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gtgtmvjchu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sysykeji.top/Article/details/gtuvdncrzt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258888.top/Article/details/gtmrgmcejm.html


<!-- 参考信息 -->