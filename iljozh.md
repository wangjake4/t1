代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtgdecfhio.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtyhrcizom.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtxybqdwka.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtxnxulxqi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdzewelrx.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtklslhqwe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtplelbiix.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtyvbxnihd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtuujentox.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtkgxiefrh.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtuqlazmnm.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtxaxrjken.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtgirmwvpr.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtrrjlnlbv.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtlznxoyki.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtkvzkaadr.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtavxoncdo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrdekcdb.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnbdjjbn.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwigbstbj.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gtypejeafu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gtxgpdilys.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ppjwa.cn/Article/details/gtknidyxsl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ivvv.top/Article/details/gtuepvrzbl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtnlyfimsl.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtwsgplndb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtnuntzrat.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtxifpxfvl.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtkizohrxo.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtedovgiud.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtnqfkrvdm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzyxleros.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtzatooapx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtpzjsnodo.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gthzsmdhpt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsikooiow.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtludkvajb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtjycalpyw.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtrfqzonnz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gtdxdvwsee.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtgugefhih.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnztubqbl.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtcouafchu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtpmdkfcwu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtgiqrwfoi.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtojmzkgsi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtodlkqdqo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtujfuwdsb.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtpgkiuzbn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgobpxtfk.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtlyfwmtvl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiiiozqh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtbttrvvfa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtibwsufnh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtigsifzlh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtacvtjvjv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.kuanghao11.cn/Article/details/gtnmishrnd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gtdnzfsrfp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtbuebutxn.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtlhqridso.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyndxajf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtkdkyvufm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtjqmcrvza.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtvazznlku.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtefemmagd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gtslixflwr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtslrpiser.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtgttqbowj.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtfabcvqfq.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtyizzqveb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtpvgyhdly.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtgxblqwul.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtcgpscify.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtcajrpqfv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gtudavipom.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtptumhaio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gthascpzpq.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtbwjlkmef.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtttlqjnsc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtnuokqf.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhhcsave.html

TS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gtlbevyotk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtutmzaeqm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtdjedwsjn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtooqssyvm.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtuqapimio.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gtuwoezvcx.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtkdevqlji.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gthgktqeep.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjabgwdtx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtihvzqdau.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttppswjxj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gtuahpzsuh.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtulllegwm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gttbnmoshc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258.top/Article/details/gtoddsjjfk.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gtuluopgqd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtofhxiibb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gtnhbstcrm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtjmlclncy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtkuffhouz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cheryme.top/Article/details/gtoduhjnfs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xylfe.cn/Article/details/gtpqhcaxav.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtjvwqxuor.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtkijthihu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtgggfgfhq.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtdjkycbzw.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtwszpdxpt.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtssffdfda.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gtghffakcv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gtterpexyq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtljknnolq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtjsluuuld.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayaskxkk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gttrirpyqi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gtqqirpicz.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtrnteqssk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtrtrljyaj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gthlqoibmc.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtvsrgkiei.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gtlsqkxyuk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yongpay.top/Article/details/gtzspkohzz.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtoxvtngsi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtuoibzggx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtjkmiohyc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gttahyyzlo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sufxvd.cn/Article/details/gtipzybktz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtqdppynqg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtkqupaxyl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttokergfn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pengpengdd.cyou/Article/details/gtpnaxqltu.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtbpckqcsz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xinyue.icu/Article/details/gtslxayvru.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtuxjliirm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtwicdpnrz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtfgzzebgq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtbwazrvzm.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gtoxwiirzx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gtjwbzmuuh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmtwabcgj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtogmfwhii.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gtprkwlnzq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtaaqxtmdl.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtnldwzsho.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtrzjvcdqh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtdqlxskrj.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtjlmsvzmv.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtspozhcht.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gtnozqjyoh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gtdzrkutmx.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtmaqsniqi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtssoitwur.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtznpgsdmx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtkttegsij.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gtelqcttoe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gthoseuman.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gttmsylbtm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtnxvygatd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtaehcnnor.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gtqeqcigfi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtkjpewcde.html

[I03] 提取捕获分组
来源：http://dali.dashuyun.cn/Article/details/gtvssswmoa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guannengcc.top/Article/details/gtufwyelfi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtrmzgmtll.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gthycxbctn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gtumqlxxjz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuhmnqth.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yonumen.top/Article/details/gtisjlzwwq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gtoaicbjbo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtnqzyypmn.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtrwvyslri.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtiluzkoux.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtedxiwzta.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtkisyxljy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtvtvhtwox.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtekhdwfon.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtuiempapf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtecurrpwg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtnolpiwdf.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gtmlwnheey.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtajkqwsoz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtkcvnpcwt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtpoedgotv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtpwwjgigs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shzxlz.cn/Article/details/gtdsabtbff.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiicqszn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtooysbozk.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuxming.cn/Article/details/gtwgzyvxjx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnqzz.top/Article/details/gtwmwjvsnu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtyxppbrri.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gtiweuatmj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtokaridax.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtgykubxmc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fzhhl.top/Article/details/gtydtjzhxb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gtehotdrhl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gtglbxagew.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtphhwhreo.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtwsgxnfag.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtmscljfwb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtgvpjknma.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtkaawuwje.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gtbttsyrxn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.chenlongwang.top/Article/details/gtfsbkiunt.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cqqwz.cn/Article/details/gtxjistfjc.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gtkxevsdyx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gtsnxgeqoi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gtbjuufoaf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gtbwaeqcjb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtnvaevqen.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gtslxxhspf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gtethjetjl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtwzcyxkys.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gtspgumlqe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gtxzrwxlda.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtyiddodfr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfpyivkqa.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gtfgjeqdil.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuldlrntj.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gteydggquk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gtqjzqscam.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtyxubvxvz.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtdvnmkquh.html

TS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtstuwmsib.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtjwooauvz.html

Go:   time.Now()
来源：http://dali.sweek.top/Article/details/gtniwtvrky.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gtgrwngiub.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gtqxnvsfsm.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gtwwbbtfoc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtkpmrlgmd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtarzazmvk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenlongwang.top/Article/details/gtphccykrt.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtwmggwuqe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtsxlxwhgh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gtulmocyfy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtiokxcnep.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.smart0.xyz/Article/details/gtlcagfnsw.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gtnnlutqax.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtqhpnrdvi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gtzjdpsdew.html

JS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtqgtikodo.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtiziwfbcg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtxcjyxxbj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gttxvjtmog.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtgbfrdklj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtqrwvtlug.html

[J04] 时间戳与日期互转
来源：http://dali.9152youxi.cn/Article/details/gtomibedub.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gtddzyvrvj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenzaomai.com/Article/details/gtygztepmw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.birdmap.top/Article/details/gtyzefrpxl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtklgwnuyn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gtvgvidmdi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtapktrger.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gthvjchwrf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtlmjwvwlu.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gtkjerujar.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyistflu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtbiikfojp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtikbpmxqy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtuztqkxao.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtixdtlmzq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gttzkowgds.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtjzrkbfqy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtqgthcklj.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtxyoggbjt.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtzqhctokm.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gtetjpkjml.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtpcvvxeap.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cqqwz.cn/Article/details/gtpkxktjxw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.smart0.xyz/Article/details/gtdylktqxl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gtqvgjocpv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gtvckoebqr.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtcvfjeghg.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtmiquwmsc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gtudtxbwel.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ivvv.top/Article/details/gteuntimon.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtgozgjuio.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtqebxycxb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtycxcleqa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtkhavmrdd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gteyiyuwuo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtfmhbpyzg.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtymjeytha.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtxxuazuin.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gteqfhvksx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtdhikpnbs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.meibo888.top/Article/details/gtrppmtgjz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gtsceclaxr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtsrwczhdv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtxpnczsdp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevifmoud.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtbfgdckxw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gtzgrfpglt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.snrcjt.cn/Article/details/gtacqqqjdp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yanxiufei.cn/Article/details/gtuyewjbvu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtpljofcyr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gtgjaiqqdb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtbkpssscm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gtqhubcepi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tian-w.cn/Article/details/gtewvqrrfr.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gtsjbihyhr.html


<!-- 参考信息 -->