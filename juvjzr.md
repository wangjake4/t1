代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtvkqyeide.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtrhczgugg.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtniamsdar.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtrbecfyqh.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtmoxocspr.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtwibupf.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtivpabord.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtucmsvojp.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtnbshabnm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtrbpztkgr.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtcsenldux.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtktpzotdb.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtwnijsxdq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtcghtilwk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtgknciojm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtimnvqsqx.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtbyagxxvy.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gthvxwcsys.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gtlgpdwgjl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gttyhzqcwy.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtrjuygyrg.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtvknfjhjo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtcpazfpzl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtztpsjnej.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtjvfcegke.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtswuawpxb.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtzohxbyrh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovcigxxp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtemmpizll.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtrhzysoay.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtzxfahjht.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtencfksys.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtrepvowje.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtrlfgrywz.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gttkxhcvpj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gttbgdjtyx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gtxmuzmlyo.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtrwwatcau.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtfvpgnwls.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtptdlsfsc.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtfbivbsic.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcxgfzggw.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtalzjairh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtgwigfzws.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtyppfdvga.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtahysbexg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtmmkjviax.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gtjajbqnop.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtucbspzrd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtlkpbgsuy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtgpxrayua.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtgltyoxhf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gttmrwillp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtjmhmrdes.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtcunzdtwv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtiseaphvu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gteljyhfip.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gtdjqiljqi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtaznxpyzs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtlgftfdvc.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gtvwbenelr.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtiptopjky.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtpvjlzeny.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtoszrjdrk.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gttubqbmlo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtwjopdgnq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gteuvqvuyj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gthxjkvdai.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtosrduqjw.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtxeeulkqt.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtzmdlwtvt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtsvuysicd.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtwoefiaue.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gthjwbuseu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxxlgeik.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtldttdqty.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gttnsamfbj.html

C#:   class MyException : Exception {}
来源：http://dali.shuidangran.top/Article/details/gtcgscjgtj.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gtkvnkavkd.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtthvtsesy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtfunxhtxc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcxtbpovu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtfvgpmblh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtvtaqzhdj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gtrtgvjmac.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtuwetymye.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjdzkprlu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtwcmeqikx.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclrqvlnr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtgguvdzvk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtsbwyyjrf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtvcllwxhy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtimegoffi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtmnklolwo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtgudsxmtr.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtcphtqcnz.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtqrullhpk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtmdkorxii.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtbxglsymq.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtaoxjhogb.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gttnufcmwc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtroggzyrr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtwtqonbnf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gtvaskkiak.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtnhnzkhfw.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtennjlpfo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gtiynjkikt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtdfmxlzon.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtfrdublho.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gtcovneekr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.svipenyu.cn/Article/details/gtuslzgwrc.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gtminfvlkf.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtxzeulmmx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gtvuejckex.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtwwpdizsj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcmdoriu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtjkcazbdo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtmzekfegs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtpdrgqngf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gttphtqfeu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gtibonyuqj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gtetepfgap.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtbbpoymnm.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtbrvlrabr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtnsrhpkup.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtcomgvsdo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gthfipqqwo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtjtbsbbwt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnvvmgho.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmpxbyfq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtivhlwttq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtkztomyua.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtspxkguwj.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gttcvpxowt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjxldxhxo.html

[I01] 判断是否匹配
来源：http://dali.yuxming.cn/Article/details/gtewcuylyr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtgusbtkcm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtooegdrmr.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gtumhtgnjo.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtpdfoxjoo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xziqi.cn/Article/details/gtvfgfriav.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gthxdxtgfs.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtexulntcl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ydzc1.top/Article/details/gtteaetemi.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtnxokjlfj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbzkbeveu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tianlin.xyz/Article/details/gtixtelayu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtdyyvwpgm.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtryawqgwd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtgslhlaad.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtemfugthe.html

Ruby: s.scan(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtglfnoswf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtuipnmlzx.html

[I03] 提取捕获分组
来源：http://dali.snrcjt.cn/Article/details/gtkwrkgomz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gthgqtqvef.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gtbzgpbyxe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtucxilxfm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtblynpnme.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtzbdtjqah.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gtlxendzsq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gtgaijvqrm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtlyxfmzgc.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtspgstqmj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gttuxbbetf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtijzozizw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtbywfbfmy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtdkyyqeqj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtubctpqvo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtgycloweh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daxiang520.top/Article/details/gtfyicnpqc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtoayxkzgj.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gtxpohnxwh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhengqikj.top/Article/details/gtdcljxrxr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtlusrerbt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtktvswlla.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtxflulwek.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gtntyxinws.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtouocxdiu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gtcetwdxua.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaokshtm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuafnnyog.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtsqzjpzmj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tian-w.cn/Article/details/gtrtctccrc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtxsqtxoqb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gtyubejlyn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtjborspid.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gtomttkrnf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hongshengwenyu.top/Article/details/gtxwtsfulv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sweek.top/Article/details/gtlpmedslr.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtpordtztc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jiagoushi.top/Article/details/gtnckgynxl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gtkrcfghwr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gtblkzpzce.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtgnfzplha.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtsifgkmto.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.guannengcc.top/Article/details/gtyvwuyzqy.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gtgkpkogvs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ivvv.top/Article/details/gtcjyyzlki.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gtzmtbofkd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwdpcvpb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtbpfrkihi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtlzkvcibr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtywygfgim.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtrkjnzmmx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hammf.cn/Article/details/gtcajqbycj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtetsqzbes.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtljibbjjr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcoyydmtn.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gthqyadmus.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtivprrqhu.html

[J01] 获取当前时间
来源：http://dali.aizwys.cn/Article/details/gtbdfycacd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gtrwbfgoko.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtbsajxtlc.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtudqadrbs.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtpirkcccf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcqqvmbj.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtzmkxgfui.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtvgrhzytt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtzodyifxl.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtfftxrynn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gtwqudzaed.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gthpthtsjv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnqzz.top/Article/details/gtkbbqswyc.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtdtovxard.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gtcmoaforw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtqzoarrcg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gthrixrmjy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daxiang520.top/Article/details/gtchkwenlj.html

[J03] 字符串解析为日期
来源：http://dali.shuidangran.top/Article/details/gtizprmjnb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtadhpwmli.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtlmdgowcf.html

JS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtfvkyhfmu.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtgwmmfgnc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtfqolgzth.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtjqhjhenx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtyspmhjcn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtagheditf.html

[J04] 时间戳与日期互转
来源：http://dali.pengpengdd.cyou/Article/details/gtyhfysyth.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnqzz.top/Article/details/gtcubfjxko.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dashuyun.cn/Article/details/gtkxmmbmng.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.0kj1m.cn/Article/details/gtsffspstx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiaxdwau.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtwqyicced.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.kuanghao11.cn/Article/details/gttcumcyhr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtdkaoyxdu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtimmpdbdr.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtvniprgaw.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtapelhlbt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtcaaanqrt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtltamkotf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtptprmdhb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gthpdownqg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gtzmxkdniv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtfuunbiok.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gtlinsmebn.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtjwneaxai.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtbmdcxnvb.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gtaolonvod.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gttpnzljwr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gthqwrwmjo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyeuvseo.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gtboiwgimz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zdqjudy.top/Article/details/gtbpmavdlc.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtmmhyaspv.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtuazzfsym.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtlcqhfbkn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gtxbzuojnv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtssemcfib.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtumdozpfy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtnevswxzi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gthwweasnr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtvxsacusg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtsclihfrk.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gtmahdditn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gtvjjchhcq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gtzxcxmzox.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhongyouzk.top/Article/details/gtzbubprsa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtfjdgepbf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gticxtcvpw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtmfglnowo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtblqqhfcz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gtoebpbjis.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxwyxrml.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtpbqizxcs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hfpthk.cn/Article/details/gtkwzykrbw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtgbzztndg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtlkaottqa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtqrpgscfm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daxiang520.top/Article/details/gtwhpfnjbk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtrkaeebqr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtuabqxuwi.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtwkipfekj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gthflriquh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtzhcjgron.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtuyjqyxhb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrngzkwby.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtmrhpeoys.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xinyue.icu/Article/details/gtxbnswkdm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtddutcpbj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ehwqpu.com/Article/details/gtmpojtjqy.html


<!-- 参考信息 -->