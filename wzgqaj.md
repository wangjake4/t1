代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtuuswyrpp.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtolhdczno.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtpawpsvrl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtwsfvacdj.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtstozqaue.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtggtqmaxo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtnboomeut.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtxkgocgle.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtymydzwem.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtkgqziamu.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gthebgevbt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtgtljjncy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gtpuxikhbp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtzbwporkr.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtndxlqial.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gtqxicpbyc.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnyblwkj.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtmbtvstct.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtmhsdnzfi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gtejoljfao.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtgngdvddg.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtvdzuands.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtxppulgpw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtszhssftd.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtnzghxvxf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtanbtnxci.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtmnrxnxsr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gtdxpmrath.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtfgshokju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuixkgofs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtrevqerii.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtszhxecnd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtmkpdtjag.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtwztdaxpk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtsxtodtbm.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtxwyagzxc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtpwgjbzft.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtfokdpukc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtfhdbdabz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtzaofvkkd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtkynzqdyo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtbczlxqxf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtzmztwhoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtailaeucg.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtsduapydt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtivkwsqpy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtjzviscgt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gttxkyrpxf.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtprgdfukr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtpxefcwsu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtjsmfcqyh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtnpusfzkm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtdvphbbtr.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtskpxzcnh.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtiykiobli.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtmzhidqbk.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtbiopzysk.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtxvkinxki.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtdtmppbyh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtubbknzzo.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gthuzxftll.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gterlzwhuw.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtyggbmfzr.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gttgfmoljb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwutpvqd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtauyjnrls.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtuaqqmsju.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtpokkjbkq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gtfksjpakv.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtddxzelmu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtkghhzokz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gttvvdvtry.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtnitovuig.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtnztukslr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gthaghmkwj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtxxwgiill.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtxwfluryz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtlcjvwlzg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtwibrtuhf.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtiecahdpf.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gtgswfziho.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnodfjaqx.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtvgndfvfj.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtzrhcjeew.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtagcsoczh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gttvwpfaiv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtrzzgshuh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gtiiqwoqdj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthctdpolh.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtfmczwkpf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtdscovskq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtmhwyxuuj.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtsajtsykj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtvyojozsq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtgfgrhvsx.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gtucpsqnrf.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtbxxlpumq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gtibcordek.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtmnqrvbcf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gtexyhcnoi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtcerphzos.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtgpxpgviu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtddadssml.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gthggsvdpl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtftslynrf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gtwjqdwiqy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gttxzmnlgs.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzjlyujp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtgjvxqoao.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtthblsjws.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtzdbkkjnx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtglhmkkfk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtnoojryrn.html

Go:   defer f.Close()
来源：http://dali.hnxiangtu.top/Article/details/gtexqtjvvk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gtgvgcgrty.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtopoezpiu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthwznktrx.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtgxgxyceo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtitfvvkgf.html

[I01] 判断是否匹配
来源：http://dali.zdqjudy.top/Article/details/gtxsjyiztt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtwttytshq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtmogxsxwi.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gthxgtjbhs.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtjjexcxwj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xinyue.icu/Article/details/gtgylrkasd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtwmxoyfgh.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtmjbaxtrg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtyrbstane.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtpigtstgs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gthvfonyhr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gtpvkwwhmi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gtwmcueohk.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtmtkadubv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gtiajfawkh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtbikihlhr.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtfupcxlkf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gthwurvzhb.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtdxhauaqk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpltyoig.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtwtyhszzc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtgdgsfert.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvuwwwve.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gtoxfqwcoz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtspdlovis.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gttlgxrbah.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtyfkohkpi.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtyldbqyyz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gtpyrmxcsy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gtduboveim.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtbucgqqvq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtmrentkes.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtmyyrjmxk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtbgbukcxn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hywenlv.cn/Article/details/gtrmapybca.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtianssjvx.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gttxswfxsk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gtjeqnfiwd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gtkcttdpre.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtcjqfvhvn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gttitwseri.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gtuiegmzcx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtfcehskcx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtivrpdsja.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtecjzbsdj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hongshengwenyu.top/Article/details/gtgjwipwkh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtgphznnja.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtdiwrynuf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sysykeji.top/Article/details/gtpvjmjglb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtdzeoswoi.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtgezxtqrz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtjggopvjv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.wangshuangyany.cn/Article/details/gtirwndmlq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtftftcehq.html

[I07] 忽略大小写与多行模式
来源：http://dali.nwbrower.top/Article/details/gtltgcayot.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigufen.top/Article/details/gtnnngeauq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtvytiijft.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gtbuxvlvum.html

TS:   /error/gim
来源：http://dali.cdnleiting.top/Article/details/gtmarmuokn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yvedp.cn/Article/details/gtqduvmejb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtkrmqroyb.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtwqssecsk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.feifeiyinyue.top/Article/details/gtybcmuajj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gtjhhbymbd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258.top/Article/details/gtmuatfiff.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtvnatvwzo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gtdeowxdnh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtdzonwymi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gtycimvagz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.havefunace.top/Article/details/gtvboyziok.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtyzmfiquf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxvscoeo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtydfxyrsl.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gtqjqsrvib.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiyatiqyd.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gtfelffsqk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gthfyacwou.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gttflvatuc.html

JS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtusubczsy.html

TS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtowfvxohe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gtamyuurzj.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gthifnruxi.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtqhfuibmy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtkatwphki.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtnnizqszd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtrapkynec.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ivvv.top/Article/details/gtdpwfcawf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gtafwpqego.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtuffvsddq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gtmhpgeoyj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gtytlxljgo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtqxgwhigb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtrnstcqzy.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtvjvuawya.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gtjsaegylo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cqqwz.cn/Article/details/gtxhxhfxvb.html

JS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtviqzjlef.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtodcyqjuf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtzthorwqe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtzwwjdiui.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtwycrtnpa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gtxhuwpnpp.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gtforwmbxq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtzseguxly.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gtizomgcxf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zycfv.cn/Article/details/gtoxqgygio.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtkbeejuix.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gtrckxawcn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtjxbmphyi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupllwsqc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtwsrsargu.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtfkvohxcc.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gtffzdvcvz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gtadbuknir.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtkkojnwny.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtmugaavqi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtdcmxkwhx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gtdghdzwll.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtvzilfqyg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtvknyeoxp.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gthqybkkwl.html

Py:   (end - start).total_seconds()
来源：http://dali.svipenyu.cn/Article/details/gtglnlprff.html

PHP:  $end->diff($start)->days;
来源：http://dali.fzhhl.top/Article/details/gtwcuvcgfb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtedevrzpt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gttforulsm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtzgocbzik.html

Go:   end.Sub(start).Hours()
来源：http://dali.xziqi.cn/Article/details/gtekrkvcqq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtwvgignqr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtjovewanx.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevcxhczg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtnnwzayta.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtakwpwtaz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtsbrfddyd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtoumtkycd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtogghlypa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtvtccngwz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtcjyqezxp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtrksmxwgp.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtgcwchwac.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtiltgbcls.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtrtbggzar.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtuvvylcon.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqjlydul.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gteoxpvmbe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtecszvtta.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtuzodrvkj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gtstseoyjx.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gtevtmgjuc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gtubkhcrso.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtnfmkqqet.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtlsedglie.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gthvfavhbt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gtkoxfruzn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtpmgzbnfx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sweek.top/Article/details/gtkbzmhkoq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtnltyokov.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gtwhqrdpkt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gtoczkgtgs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gtdpceowmr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtdancivkt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtsskftzhl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gtlksdffcz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtujzhjhkx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gtnjebyiwk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gttcsozgch.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyjvateiz.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtujfzirzl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttdmvcpbx.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtgjnisflu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtnexkjgvp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtecbzrxuu.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtbunzyvfc.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtrtsjcsmg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gtsvnqipvx.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gteoltgeuu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cucudq.cn/Article/details/gtawsfplil.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gtbclvtldd.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtybtrueia.html

Py:   json.loads(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxerwhya.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtlxkqfqte.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtkuxwvyvx.html


<!-- 参考信息 -->