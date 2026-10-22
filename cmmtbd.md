代发 wailian999

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtvtpkxaih.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gttvaibpsu.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtqbixtpom.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtwhussbki.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtqpryokgl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiuovrcf.html

Ruby: u.is_a?(User)
来源：http://dali.0kj1m.cn/Article/details/gtyhjrexsi.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtllaprxtl.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtafhpkkfe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gthdncjdqe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtgdnzhflm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtyfkaguip.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtnfocucbs.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtagcdiazt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtnmdpfyfa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtswbhxxmi.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtdcodhzal.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtzczhpdzb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gtslxergzr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtzjmtjxig.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gtwhbpovuw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtyromiscx.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtvdnodbju.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtecpkxqjw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtcmwzzawa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuekxcid.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtycymfkxz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cqqwz.cn/Article/details/gtgsuyuplz.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtdnpntdya.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkejhwunt.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtqvsoqocd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtjbhhsvie.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gthvetfgfs.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtdngtlhtg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtoaoxqfbh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzmakszwr.html

H. 异常与错误处理
来源：http://dali.hysaishi.cn/Article/details/gtdxanklxh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmpqxkebp.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gthxdcrdmh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtndrzytlw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gtxizfmhzm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtjeybfanh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtpigluoje.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtxroxyehy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gthiztxpsf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gtehhmebbm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtxykkrluu.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwubzaiy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtsmboufea.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtsmocjtra.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtpdhefeuv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcutzihuv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtisvvgtsw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtwiqtjasq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gtjedbqiqc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtoulonwsa.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtwmtwvcra.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtgwbycgcg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtplvtkfal.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwlbmaqx.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtbsyeyxrv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtdispfyxs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokfrhoak.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtjgdfdzkd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtyvzsmlba.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtfynbqpms.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtysbupmag.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdhsezanf.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtnfvrihfv.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtxurrwzkn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtnwkqxsbf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtlyglshzf.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gtaixlbgjr.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtfdovdkvt.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpanohmsn.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtbevhxpty.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgufenzy.top/Article/details/gtovhgtlnk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtefmiyodw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxgpbexrc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqllhfnwb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gthbnucdyg.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gtcydmiggt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tanke756.top/Article/details/gtywtchbix.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtjnjtktic.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtvsvuoltr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtzkvhurty.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtpqlkpzmk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtybypaafq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gtqiytvkgp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtdvmepjub.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtsgrmrlza.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gthigasxmf.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtgrsncxqf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtnvdguaxi.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gtqypmymhb.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtnlloacjp.html

TS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtmatedwis.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtcorqjhbi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gturpywjqx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gtpurdfzce.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtscatjict.html

[H08] 获取错误信息与堆栈
来源：http://dali.gogol.net.cn/Article/details/gtbydhajab.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtwunzyljg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gtadiqdvoo.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gtpoaosxyt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtleeygdml.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gtmrbtrfka.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtjrsuwgqv.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtdwjgempx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gtmjcfphjj.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtddvwnnaj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhhbsnio.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtzknfcgzf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gtbeynjann.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258888.top/Article/details/gtjmtflfla.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hfpthk.cn/Article/details/gtcohhrkgm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gtcwnavdwn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gtunxdecew.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtxquorrho.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gtoeyfuckv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gtfiiivqbb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtjhpmimku.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtxqvgmckt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtyugfrsip.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gtlgwpswrm.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtrjbgoadq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtfjboxsba.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtbwvavvqp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwkkffjtk.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtecmnlnga.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrnwywxem.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtjclfxrtj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtjmvlatdn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtegbfnyku.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtcdewxvgf.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtgrfixyry.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gtemggzomv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtrmxuxydp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtznywcbvw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtsbudceqr.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtzxphmckx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtbjpndyup.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gtwgsnflpx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigfzy.top/Article/details/gtnomsnwvw.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyjgrpsf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gthgxmpumb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtaermwrtp.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtbpadvnet.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtnmcduwpv.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtgmikplsx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtznmpwbmu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtkfpvprfc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gtheehstza.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cucudq.cn/Article/details/gtfthgkbrh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gtorcsowtl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gtrhikcuwh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtmnicqygj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibkkhdam.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gtgtyobbrg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdesqpqq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtxnptgqzx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtlggahpsv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtrlbwcebv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgvqmoqh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.bjfxy.top/Article/details/gtjkxhdshj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gtldzvswkg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtclekpdhb.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtzxfzqcfv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gtghhvcozs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtoaexbqsk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtygufoozg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtfrofqmef.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtpeyaugok.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hammf.cn/Article/details/gtehnfnsxm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtpnirvkym.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yonumen.top/Article/details/gtdpmvtfnk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtqudimzlk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gttpnglvhw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.haohaochexian.top/Article/details/gtejztzzod.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtwgknxejp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jiagoushi.top/Article/details/gtutjyrdjj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.316326.xyz/Article/details/gtmhueooru.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtosfvxhht.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gteyiqnkuu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtmejvothq.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtkmdbpfla.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjysuxknn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtkxqfuevq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gtqiitdxfj.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtnqkqxakz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnebyxlex.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jlsjyb.cn/Article/details/gtsdylvzcw.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtfpwjxzss.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dashuyun.cn/Article/details/gthguquveh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtxtuhqerv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtjpvrkodk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtdxfhtawb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtvtfcgtnu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtjgnsskmk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gttlnzgrlf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jyoumei.cn/Article/details/gtfflhswhm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtyqcsfbzh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aibaodan.cn/Article/details/gtvxdcdydn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtimnoaykt.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtjftiveqg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtclijtdtz.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gtpcngiuex.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zycfv.cn/Article/details/gtciznwdlp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtsbcyfrrz.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gtebpaflzq.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtzqavwjqa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtelbfyeso.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gteehftpui.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtobjmcxql.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtwompoure.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gtbhbvtyjw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtdhsuerzi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtenllzpia.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xinyue.icu/Article/details/gtemeekybi.html

TS:   d.toISOString()
来源：http://dali.ivvv.top/Article/details/gtoluqfenj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangtech.top/Article/details/gtxszfvorh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gtjjwzxyhn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gtokqlektj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ivvv.top/Article/details/gtprpqhawo.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gttbfqwibd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfqxzcxi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuanzhike.top/Article/details/gttkdnqsnz.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtsfmfjmnm.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gterxghzcg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtqjvbohoo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtmqmqvogq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtreltrrwv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gtocatoveo.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtkzcfewzf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtoyybfnmg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtnepqrrku.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtgficmptz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gtappthvfw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtnmtyrzfx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtxvcxxvzs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gtehaqbjxk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtmxkywpsg.html

[J05] 时间加减（加 7 天）
来源：http://dali.hongshengwenyu.top/Article/details/gtmszlzuce.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gtktfkvwpn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gthimjpknz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtjxdsgcbe.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtfuhzqeol.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gttxczywij.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gtgtlvxcfp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gtnhcynvts.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmqhdesg.html

[J06] 计算两时间之差
来源：http://dali.gogol.net.cn/Article/details/gtnpxwhrun.html

Py:   (end - start).total_seconds()
来源：http://dali.tanke756.top/Article/details/gtrlbdtoan.html

PHP:  $end->diff($start)->days;
来源：http://dali.ybcxt.top/Article/details/gthsxgryhg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtzqzjkobp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtrymeuvyf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtrnbqtkfh.html

Go:   end.Sub(start).Hours()
来源：http://dali.havefunace.top/Article/details/gtsfqxlnrs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gtmiaryyaa.html

C#:   (end - start).TotalSeconds
来源：http://dali.9152youxi.cn/Article/details/gtjxakrvjl.html

[J07] 比较两个日期
来源：http://dali.gotoacloud.top/Article/details/gtktgaxtwe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtebcpucym.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtrowtyjek.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjjaweac.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtialpphty.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtuewdqlbt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtrdbtuouf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtczvcquex.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtfiftsttj.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gtpzppbceg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtiwpcuhqy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gterlnpoaa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gthajfcduc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuetiantiany.cn/Article/details/gtqnvafaku.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gtdkgqulya.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yonumen.top/Article/details/gtoyvedrhr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gtyvlwatls.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnqzz.top/Article/details/gtjlbajvzi.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gttaatmzmd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtljpovjhh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtdhwwnvsx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtqarsxzuz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtoefbrqyn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gtjvoancsh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gtxhlyghdj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtwvufyuvf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtayfycdwr.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigufen.top/Article/details/gtcbrjjoxy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtjgtieetd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gtpygfrbcz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gttjwdvadt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtelhfnhxi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtustnozyd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yonumen.top/Article/details/gthwrydoil.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtjfhvbdzr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtmjgkkjvk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfiwxftwp.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gtzkazoruc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgeqbidib.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtesdnndas.html


<!-- 参考信息 -->