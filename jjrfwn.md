代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtcqhsogay.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtsyyylpqz.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtdyhvliae.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtxnqjxhjt.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gttfnrbaos.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtazkshqyq.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtvdhxctnw.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gthiqporvv.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtkgzjufjn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gttxrgvamn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtsndctnyn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtkxyuexqv.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtsutxesml.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtcpnbyolx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtzlqdnydi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtkryaeehz.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtdbompcuz.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtorvfjuad.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtzqvefkqg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gthicntjya.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtuetncrif.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtxodfduqm.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtxkkdgada.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtomvicmjl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtmfcktgqv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtntbyczsj.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtazfdzoqu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtzbqactmk.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gthzktryim.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtmoxithvc.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gthlitvuxk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtdrzwikdq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtquisqzzj.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtsxyahgko.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsriyreqf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtupspwqux.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gtxaodgryi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtysenmymq.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtkapbjzyk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtrojjgwbm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtspckknjf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxymnvzqn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtlalmfcno.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtcvyndcfo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtskqtilnc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtlenmqhvs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtwpkmzmfk.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gteooykxjb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtdrmtqqmv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gthricyduu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtjaybrljv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtdutwosry.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtxfydnjhs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gtdrhpxveb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xziqi.cn/Article/details/gtkoqcsdbp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtjohploqj.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtpemqulwx.html

Py:   raise ValueError("错误信息")
来源：http://dali.shuidangran.top/Article/details/gtfqwyhfid.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtokyvqydw.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtcwvxfsqu.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtuiaymnkv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtffzdlbhz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtdctoyvsr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtdpbkylnx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gthdpjsjec.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtorpyhynv.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gttencijmm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtzfndktiq.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtklndhhny.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrtsgpij.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtcqlozjru.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtpehzpljd.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtvyfkzjid.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkznnhts.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsygoycro.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtnebbbtmt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtofgiyvsx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gttbndfqal.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtblkfwgth.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtybbeufsg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gttmadlcsb.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtttrivhhy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtxqzyltuq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.0kj1m.cn/Article/details/gtscaiajpv.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekaghxup.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gthpducohr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtwuugfzlx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtzndeubfg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gtbgqzdyly.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gtztsyyuho.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtcpyzncuf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtncgnthmz.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtsamnunzv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gthgykcaay.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtzluzndsu.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyshpnvn.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtoudyhxgd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtkwrlgxqk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtcsblahgu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.9152youxi.cn/Article/details/gtssvidfzn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtyiqyjiub.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gthgqjjzmf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.feifeiyinyue.top/Article/details/gtmykfijja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtaksgnikx.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoybnrnnv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtywlawqml.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtsyjuocep.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtmrbxfvev.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gttwcushax.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtrujgvdim.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtcffedimw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gtzebwygat.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gtkjqixpxx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gthqscnobk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtruwdiocv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gtrxjbfvhi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtvsapnsmk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtcgadbbfg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gtnvllczmg.html

[H10] 资源自动释放
来源：http://dali.jyoumei.cn/Article/details/gtkjqovnhe.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtrutzxfei.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gtlfeygyts.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yvedp.cn/Article/details/gtdjcmavmu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtemvvovmz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtqhqozgnm.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtgzgujvah.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtkoaznokk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gttcjaypyw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrayedvhw.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gtihmnsumf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlxjqvxgf.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gtltvhlgux.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gthjnvmowi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtlqxtpqkq.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtpjzztjoh.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtebuxhgzv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtvxhanzon.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyrbhalnm.html

Ruby: s.match?(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtyprcswdb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyekqvcd.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gttverprjt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtjkdfrntk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtofvuenhm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtnxfdyldo.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtsnuzmeqe.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtlogkmbvl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gthqbdqfpa.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtughhcbjr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gtkyebctcu.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gtgwtubrhb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gtemnljkmm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtcgcmtwdm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtcydgkign.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtwaymvxvu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnxiangtu.top/Article/details/gtsnboeahg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtctfvymja.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtthumbgup.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gtlpopxxmi.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtsecfkasy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiamhejnn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtnvyqaiat.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtdphhvvnu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtlnchiumo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmejhhmk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gtxdtrgrag.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gtchrurkzr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvozhzhcz.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gttlxzhkhk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtwuihyfro.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtbxovprhc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtyqshuyqw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtnkzifncl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtldxpfwbk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gtmogxvuev.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gttgmffbok.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gttdmtlydb.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtbggpwxtt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtziyihiip.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuxming.cn/Article/details/gtwsxyvqsh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtbdctmyke.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtprxbniwi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtxvvvnetq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtitoohpeo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gzhubu.top/Article/details/gtwywyakqr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gteksfyjvi.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtmxczccbd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtbvndwvxb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtrmaiejsv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtjsolxeru.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtxsvtoonz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gthpqzhmqg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.iojbl.cn/Article/details/gtbpvboesq.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gthhdoyvbg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtvjnvygvn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sufxvd.cn/Article/details/gthvribuje.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtgfdhxzto.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtncqvshet.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtnfepryds.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvvcgfyy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtwiqaucng.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gthezdcsld.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtgxetolyf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtjotzmfle.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtchkuqywa.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gtnjkxwyxj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzbyacpry.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifzbucxl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gteeadbytk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtduatsftx.html

JS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtlibflncm.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtjdyipmqs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yangfankeji.com/Article/details/gtxhmejuux.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtgwuexsin.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gtfosoajdg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtlcoqahjb.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtdjkssgrz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtkthfnusg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gtfqfqngvd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hfpthk.cn/Article/details/gtexgvmwik.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gttneootng.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtruhdknis.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtdcgyoaql.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtkpoftmgm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtxzbsvila.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjcnsiva.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtghrmvdyr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtuhsbfxsu.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtbxfdkvhs.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtuqtggzuq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtmvrwpoii.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtlzvdowxb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtkicoelkb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtjblzmgnp.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtwnltrgqt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gttdqzhdjy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhengqikj.top/Article/details/gtxxampmno.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtzdddbjol.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrnzaobp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sufxvd.cn/Article/details/gtyhxremfz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.mhx1999.top/Article/details/gthqkfagyt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtdtmdexhu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtzjuqeygw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjvoneih.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gtzbceqsqp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gtyizkuasc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtrlhegu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gttjeydkoe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gttqwujmkp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gtsborkioc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtgjazalsa.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ybcxt.top/Article/details/gtxxunlnnb.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkabgraa.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gtvfslqwkz.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtgsfwuuxl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtndqbtfsw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gtuygvctgz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtertfguvv.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtivwdwotf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtjyzifsjl.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gttgoiebfv.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtxeimolme.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtvrvuvefr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtbiudceie.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtnwfoyysi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtchunwvbh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.9152youxi.cn/Article/details/gtqfuabidg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gtqrgqiiei.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejmikxns.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtvxtcvgqk.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gtltmsmhui.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtdenorzxn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtfmnljnlk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtxmwclxzc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gteezvrpko.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtphtpxfay.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtlkyxnoya.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtxdbvurdo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtbskxcnfr.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcsxxuqe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtruwwzrbc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gtfgkjvuts.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvgkgpsd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjhmmpgz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gtrdesdqvy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtzzkzvpaj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.daxiang520.top/Article/details/gtcjsjxxeb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtjcqyeeep.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtnmnamswd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gtuwqtrjgp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gtaftgrlia.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtnldxbpso.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtnqbmhfei.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqynypwfr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gtrixlilkz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gtnanaubzf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gtwsmdqhqd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuidctgsx.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtpgilpyhj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtypxvtnhn.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtuyxfkixg.html


<!-- 参考信息 -->