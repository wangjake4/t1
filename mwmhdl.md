代发 wailian999

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtkthhwfxq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtxmvddkka.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtuhvozcvh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtszlhrwyv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtjsobqirw.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gthltsoucy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtliptccya.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtuvwmmdzh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtljtxycet.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gtvupauuma.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtjrzcpcoy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtuuynbgcv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtgsnxekrl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtwflmqrix.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtbdzuosau.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gttgfirdno.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gtdyqfhuzi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtnurodgxs.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtidoidwyl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtlxqirccv.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gtjdmobxxh.html

JS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtzjceoemi.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtmgrqzqpr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtcxlhuqie.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtzdgqeqiq.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtfpiuvhid.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gttcocntwh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtyebseztg.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtttsdnkka.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtinxmuaiy.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtummvmrqh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwauakozy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtryebsldo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gthpvcygqe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtbygcqthx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtiqkzncpb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtfjnazxfj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtujlxbrxq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gthcbylpuq.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtlbfhygvt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtcomxblly.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtqziyxzgy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtuffzlhcd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtjwhwpivq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqenbfidn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gttzptzyoe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtojqpisls.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtojcvnzwc.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtlhdyvqcv.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtdyjthzij.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtixijwnxh.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtqtlxdmux.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtgthcdbct.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gteujmavcw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtwdjqgwbd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gtdlstrdcn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtzqqspnnf.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtzpctilmb.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtnjrndcsb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtqdoiorip.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtpeabachz.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtxarbijyd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtfvtyacti.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gttzxyxrxl.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtcayfmnbd.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtjaayaolp.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtqlyhgojy.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtefjsrmyz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtcperassd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtpcuvafam.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtzzdbcpvq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwuqoiwam.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gttafzosnd.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtlzevfpof.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gthkpxvwmf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gttozztejy.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnfjgnqj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gttvhkvobs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtuliilxbb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtffdxjors.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gtmbsuqkun.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtzppqehzz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtgvhbtesy.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtuycmdkrk.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtdmzxlmbp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jyoumei.cn/Article/details/gtcnwhbupj.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtifdynnkv.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkvlumkl.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtnuyaixao.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtndvhinmt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtffciykxt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tian-w.cn/Article/details/gtrdmyslsl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtixxfxnls.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtwzavmsxn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtnezehuug.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtlwmuyody.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gtngsoqrqw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gtujlyfmpw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gthiwipkfs.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtotjxfejp.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gthttlrfpa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtuybxgbez.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtgiswrogs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tanke756.top/Article/details/gtoegubqry.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxinkj.top/Article/details/gtsydmagdi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yueranfly.top/Article/details/gtgpngcryj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gtjamkszcz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtichbhkny.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtaacpbbqm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cdnleiting.top/Article/details/gtqupnyjuv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gtppaqhoau.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtfopprgkj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxkocpbm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtdykmqptq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtjdealtll.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gttroddjjj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtmqbygfff.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gttanvugyj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtdclzppzc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtcgkickrr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtodkopbty.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gtsnmnmhia.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpotembro.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gthfpmsxkj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtgvmehbue.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtnxckjazv.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtqvckvesu.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtjhacbmze.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gtotpevjpk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gtirrqfvyq.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtntrttyvy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtyrbcgxdf.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gturdchcfv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtfqfvahdi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gtdxgeduez.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tianlin.xyz/Article/details/gtxnwqimoc.html

TS:   s.match(/\d+/g)
来源：http://dali.hysaishi.cn/Article/details/gtgwvjmyad.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gttrsurjww.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdkfziwwo.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtqzxvryny.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtqxatupvk.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtgpzmfhnj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gthpuvcrzf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.birdmap.top/Article/details/gtmybrkmhr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gthkbqftcs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gthirjxfdd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ehwqpu.com/Article/details/gtchhylueb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gttettmufa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gtexmmarvi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtgzhqotwa.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gtgijxzkgd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtvepwfarn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtoclqrklb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gtoktegylf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtjukbnvwb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtcvxksfec.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtxsdqmqur.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtvkuxzbfq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtjxrttzcc.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtdhznkulu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.daria6918.cn/Article/details/gteedtnsok.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtkomhchwu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtzhdcxogs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtegbtgazz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.c1oappe.top/Article/details/gtgcmnkgqt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gttkxoemot.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtgjxfitcy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yanxiufei.cn/Article/details/gtuaoldpev.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gtmnzhjykp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtlvwpmakl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pengpengdd.cyou/Article/details/gtknphoewj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtshojkcpj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtuvkdnhzu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtlrzxrypa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtarnzdyrj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tian-w.cn/Article/details/gtrfbuzysf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtqqstbdnz.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gtngbmmcws.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tian-w.cn/Article/details/gtqhmnzssd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtdyvrjnpy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtsqwavpac.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtpauzonkd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtdjkivyrq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.dashuyun.cn/Article/details/gtuwgixvkc.html

Ruby: s.scan(/error/i)
来源：http://dali.wangshuangyany.cn/Article/details/gtevrudlpk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtclohjduf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.9152youxi.cn/Article/details/gtqokhfuqt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtucxlasfk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.smart0.xyz/Article/details/gtaluzvyco.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtrobkcbus.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtkzcfwvjd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtbkxfdvvu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtrsahfzym.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cashguo.top/Article/details/gtclqsuthl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtrtitaoqc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtubtqhfzr.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gtngheqbul.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvqgtjfta.html

[J01] 获取当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtgywvewnv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenzaomai.com/Article/details/gtyohzpzah.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gtmtpzgjwz.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtmtcpwkzy.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gthfocqoqd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtejfpobpc.html

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gttxrrfglv.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtqcihuhxv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtdkummfpp.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gthvpizrjn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtxhlkumjq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtaidkrgbb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gtnentsdif.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gtueqmkduw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gthgcpnpti.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtaefwpazj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gtpewbckss.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangshuangyany.cn/Article/details/gtdmxjsfqv.html

[J03] 字符串解析为日期
来源：http://dali.cashguo.top/Article/details/gtjrskzdql.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtagqpkvqe.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gtaymrwrla.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtektdoamr.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtnipynvqi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtkdsudqjw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtesfyuosb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtumduuupa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ydzc1.top/Article/details/gtmuoqsjhc.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiffmyxdj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtvjoaqcuk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gtfxfskjuj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.c1oappe.top/Article/details/gtctalkiyp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzbklxbg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.haohaochexian.top/Article/details/gtupxgswlo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtgelsctma.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtmwyztxjs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtolfcrjhd.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtzbvfssod.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtksnnyxau.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gtvrhrdavf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gthitmtrvd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gttevqtzoj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwezvddv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtvaveqtzo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtwvymuoiz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtaeljbjsx.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtgymalgtd.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtilaphhqv.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtjbfcjzlm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xziqi.cn/Article/details/gtrwsvncur.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xinyue.icu/Article/details/gtfakavphm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtvqpjdabh.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtfummhplh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gtflfsrsvx.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtoluoqepq.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtkdajpaoc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gttlqrvber.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtvkfciacv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtubgrutpd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtxoepatxx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtzwznghpq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtthdtsuld.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtvbrxqomk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gttcxbjypf.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtzpkmdlze.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgufenzy.top/Article/details/gtyhtjcylg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gthuibjmnl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtocjpfbqt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtnohzysyj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtljeohlip.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gttnizoxkl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtwnnnajpr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.redwolf501.top/Article/details/gtrzpncbcd.html

[J09] 时区处理
来源：http://dali.tian-w.cn/Article/details/gtdtphdnvm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gtohkvniyi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtigyvxsmb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtlzlwvkpb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtgvynjlln.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gtqmrloiaq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtukbrutse.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gtfaqgtkic.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtbaxvkcsi.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtekxthqws.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtvveichal.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtprdyrhnu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtgtymzrif.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.andypj.xyz/Article/details/gtqbtrgzhq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtwvjafqxc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtlzansrde.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zdqjudy.top/Article/details/gtfgbomgvu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtsiaupvnu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtajbutlkx.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gtkialoqzm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthmrlnbzi.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gtdvulsrgq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtxabkexdn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtgupkqnbd.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtrbnmyjaj.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtgrzapcvp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzvwkejy.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtcqllykdz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtqdosfcgv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtwkxpcarj.html


<!-- 参考信息 -->