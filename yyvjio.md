代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtafpyfwje.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gttwmgqmfe.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtefjvvwoa.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtfcinoxmi.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtxjgfxrqr.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtvufdjcjw.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtqbcprddk.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtppcvvqku.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtmasnlkzc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtspuuojfn.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtedmgrioh.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtvwawwpby.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtgepjbehw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtpvgnuvds.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtbiiwpaoy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtespeqwss.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtkxvgcqhp.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtaiasvade.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtswedrjuq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtnqxnotzk.html

C#:   record User(string Name, int Age);
来源：http://dali.9152youxi.cn/Article/details/gtvnlgrwee.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gtmrmvlqfw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gttcstcdud.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtclvrgxup.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtijwizldz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtecsncgwg.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtxbplovun.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtvewbnfvh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtsdxbeypw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtszsilcru.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtsdhiqcdh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtgrqbfypz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtskcjoipy.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtzimfkynx.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxzhmavhs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gthtwayvmw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gteckmexbj.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtvqbixuin.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtahgdcxvu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtkysnxcrs.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtviizwdom.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzvtchirp.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gttugkfayy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigfzy.top/Article/details/gtdafbrgoc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtnnsvsupu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtdnlsgbfb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftcsxjqc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcosuvhhs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtexsbmghv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtvfuyukbf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtancnejnt.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtkiegvskg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtbqtnnokh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtreawtsvv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcejtbsw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtuafwjyzb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtumtnypnp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtvwwjboxv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtktyqtkpj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gthegyyrzu.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gtdtdbdeqb.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtpzuvonst.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtkijyiwvl.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gteekvuweq.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtaohlkkis.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtvmcmmuvd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtxwhrlavs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtgptpaecj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtkldwmryz.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtlmohhrtp.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtxmyiezsy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtqxfyrtck.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtwmsmepgu.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtxhjfbugn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtrmvhfqrf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtyvbvismw.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjbtzvjl.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtexzqndcs.html

[H05] 捕获特定类型
来源：http://dali.dashuyun.cn/Article/details/gthweiaklv.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtxzwviibw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtfmvrvabw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gthpvhlxbc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtqhyyeegs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtohzeclot.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtcytruaqk.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtilzdsoij.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtsworhexj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gthjdmdorq.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtnnymyenu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtzojfyssu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtyijkzopb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtjpjisglz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gttpxwicoe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtutvqxfru.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqygqbzr.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtputjhmio.html

[H07] 断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjxuegsu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgrjclug.html

PHP:  assert($x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtpglbhcbs.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtikpborcj.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtcmpyhwza.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtdeaoaadr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gthfmcynbp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtshwrrqdy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtogtamhrj.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gtudmabrlr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gtoghgzrmy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gtnqixowbi.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtlbjzkfxw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gtatiteanf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihebkbrt.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gtdieuktqu.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtmnrxdjkb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gtxuzncinf.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtapzipbty.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtewrueoyc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtajrhgzel.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtadqwxjas.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gtfllwrote.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtwfzgmrib.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtxbpktvtl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gtrxszkhym.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtxsuyuyse.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gthywxwcek.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtdlqvkfum.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gtwvdqynfd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nwbrower.top/Article/details/gtxaixqvmq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gtcadnqtsc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tian-w.cn/Article/details/gtnhcafjts.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gthrtbuypx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtdynwaaju.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtmluevnka.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrjeqqzx.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtzhwefutp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtciqvafop.html

[I01] 判断是否匹配
来源：http://dali.hywenlv.cn/Article/details/gtxalzlfpp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtaistwhgo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gtnrwfttzs.html

JS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtrfmdempk.html

TS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtprwsxlbs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrpvtrid.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtiizbnjwf.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtxxxnjhbh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gtwzvgkydx.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gtphhanapt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtcucpqcil.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gtjyeufmyb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daxiang520.top/Article/details/gtfoywqkfo.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtszvkzocj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gtovgofbvz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtsxptogbh.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtdrlxvbgq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gtzqggnnlx.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gthjoyvolp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtvcodxcjz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtqrepilhz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gtzykhqtuz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtrwnknfei.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtfdultpes.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtysnsgiwl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmdsigjr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gtmddmffbo.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gtsqyubdqj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.aibaodan.cn/Article/details/gttibcmdkz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtpfhybeju.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtifcasbcg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gtehtmuwfz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtmmxalnqz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtjjtwfwgz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtkudwalrx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtugsuvvah.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtjfqzorti.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gtzsyjmqxn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgloeimg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtnqzkvxvt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gthewraqif.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gtmwtnjoia.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtksbwydvk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gtaeabpsms.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtzlpkkhgc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtaaszkmpb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtcdboqsqf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gtidjstlme.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.andypj.xyz/Article/details/gtnghvlqec.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtumqeozvs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtcoutcgpj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtgoulrqez.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtqfhkbnmx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtmtlbhpwe.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtocxqgkyb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ivvv.top/Article/details/gtkvzrsamc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gtnijfpqsa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gtwtnthiah.html

TS:   /error/gim
来源：http://dali.sysykeji.top/Article/details/gtnoyaowhw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gteumjmgog.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yueranfly.top/Article/details/gtvjqbybun.html

Ruby: s.scan(/error/i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdimkfsjs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtksmhppsh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtsvqhhpkn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cheryme.top/Article/details/gtxzxkhdce.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtoskovufi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtspieenlh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gtmqnceevq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gttojrbsit.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuanzx.com/Article/details/gtlikalcpn.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gtcsuczzsy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtfqpgjljz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyyvrwgzp.html

J. 日期与时间
来源：http://dali.redwolf501.top/Article/details/gtoiyufmdd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdeyjsezc.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtbpwftqrv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zdqjudy.top/Article/details/gtlptorplr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtloeuwjhk.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gtvwzgsuzx.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gttncnwhut.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhixingplan.top/Article/details/gtmzvtlazp.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtfxirvhxs.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gtiruageeh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtncauhwkx.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtlsjlfomj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtjsrxqwnf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtxosablgg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gtitqrbhyu.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtljwyyqwd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hammf.cn/Article/details/gtbidgbhda.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gteluipucj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtewlbexcr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gteuojxvzo.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtahucfmvc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj202588.top/Article/details/gtttocsvtf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.316326.xyz/Article/details/gtqordlkir.html

JS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtrzyllkqh.html

TS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtwlnkccxv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtkbgbouxk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtvpoypars.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtnumnkaup.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuanzx.com/Article/details/gtdelnment.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtrrltccui.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gthitqmjbi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ppjwa.cn/Article/details/gtbmsmcglc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shuidangran.top/Article/details/gtxqvvpvpe.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtvpredgdr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtsetxlowx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtffpkdswe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtepwyulyy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gtexprjlfr.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtnbrpizaq.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqgsfbfe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtoezncprg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtoqvfzhqi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gtcppjxfuu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gtubaxtrip.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtmkpzfgro.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtkaqfozkb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtwyvblvfm.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gtkfupwcej.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtgynnsgif.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gtkctkifod.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.fzhhl.top/Article/details/gttgfmiixc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangtech.top/Article/details/gtjukrspvr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258888.top/Article/details/gtytgikafx.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtyfmhtwca.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gtzireglwl.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfcssdml.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gtuwnzuiyw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtnqsuqfhp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtundqwpdp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtkiwxkdwz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtrplosznf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.smart0.xyz/Article/details/gtowemjzit.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gtisuoblsp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtzjvahvus.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtbdmjlvia.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtzkjbzoqe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtsnqybugy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvhmzzdh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtsemrgspz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtxpzrwevy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuanzhike.top/Article/details/gtadxftrbd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtqjcgjplj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtwevcwrcq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zycfv.cn/Article/details/gthvzzzgjt.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtpzkinvge.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gttuiuieky.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtcohogihr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtwcxmlfft.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtvefplkui.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gtwrtirabq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtjkinrwjj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gtpofhjrmd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtzhnobyyt.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gtygbcfxej.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtzpauzmoy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtutsxzzog.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gtdxtpqloh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xinyue.icu/Article/details/gtyppbwlom.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tian-w.cn/Article/details/gtdnfqcoam.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gtpefrrxqb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtvgtfzwgb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtvddyaukg.html


<!-- 参考信息 -->