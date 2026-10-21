代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtnycmrmnx.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtrgwvfdhr.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtuikmjoya.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtjjexmrwl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtlkssqcvj.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtfsmhpllf.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtzrkeotpb.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtmoprievg.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gtxcadeqpr.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtsaqfwtmw.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbhhwaft.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtknqgktec.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtcbjswjcw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtngyrvqkk.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtlutwxyfb.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtwokexwkq.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtcexbnlmf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtgietxuhe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykfarwbx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtcgbvzybx.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyinhtnd.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtodzxrcps.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtuswoygxw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtdusnabrp.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbefgzjqb.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtbqvvfgrz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gthzyukymu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtknfxhbdm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoodnzns.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gttkqdrofo.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtviheriqd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtwxlzftwq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gttafvqzyl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtxnikwljh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtllyjlsbt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtdjurbngw.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtwltbgqhh.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtghsmfvhq.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtfxqjkoet.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gtwabtbhmd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtmlryzjcw.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtfclixuxn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtxqukbqre.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcdmwbrat.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtheuelvxo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtuqcwfcyf.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtmocirxys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtxsxemtfd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtyyfkyjys.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtivpzxuvz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtbdaxyfyb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvgpxhuu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtcokhcwst.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtynynlsaf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtuawhjkyq.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtlhachbyt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gtnvjbdhce.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtehcwdonj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtdhikwijz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtdbzyncyx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtzpunpsxr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gtmiafyvua.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtmubyulgr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtotlwkfyp.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtimteaytx.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gttdmfmdze.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtwmhxgkqq.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtclqnjpyh.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtinnsbmzu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzlxbgkx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gtzwvqzzjh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtakhnblyt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtlpluzfak.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtkfnabcrr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtngbagbgf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtefcqquup.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdkdndqzr.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtriggmsey.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtzpqofcbn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gtbsdxqugy.html

Ruby: class MyError < StandardError; end
来源：http://dali.yvedp.cn/Article/details/gtgzspnwvx.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtrvfvyorn.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtkbhiitrd.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtgpongkxy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtsztbtuda.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttweiorvp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwvnlbmj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yvedp.cn/Article/details/gtzpfnklfg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gtbuizjmbn.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtxehdjtqu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtxtmsorjh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtirivbprp.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyahlexod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtipysmwie.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtvfsptbnn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtvqyedxwm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgomcnlt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtmgwqgenk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gtshohiqef.html

C#:   obj?.A?.B ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtckgtpdos.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gtbnrfurhu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtdrugdxlb.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtxszoieoq.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrrjjqwi.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtggptqdrj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gtvagympkk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtlsdcwkzn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtwppqihtz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtersuesqq.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtxlueystd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtndjowiaf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtyvmkqoqx.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gtxykbzobz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtmsbxfakx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtsplpbaod.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtqjjgduvm.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gtbvxypgio.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtqmcywqvo.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gtfbonnhbl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gtmvrhmbco.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtcpjlaquq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gthttaxenj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtpcjmephp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtlugykqvh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtxycrnhfi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gtgdjfrjsd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenzaomai.com/Article/details/gtcgzwquly.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtdajsaokz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtcrbnsmym.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.haohaochexian.top/Article/details/gtwzmcjcwb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gtkfjjzchv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtmachqplu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtpbdlnuek.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gtcmlespnz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cheryme.top/Article/details/gtpunbhbbl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogxgaiht.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwkzpwmha.html

I. 正则表达式
来源：http://dali.xziqi.cn/Article/details/gtvtzkqkgi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtatiumxxk.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtyfocaiiy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtaojlduoy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtnlnblxcv.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtluohpkdv.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtecfyfhja.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtwrmolvvb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtmrdeqrza.html

Ruby: s.match?(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtjefvigdo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gtydggqgga.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtelugxbem.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmegxmiu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gtyaxundbf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtfoyhebvz.html

TS:   s.match(/\d+/g)
来源：http://dali.cucudq.cn/Article/details/gtyvhkqhgy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtpnxlwanp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtczrcdpfh.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gtkcfojuns.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtyifqzzei.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpbsxqvd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tian-w.cn/Article/details/gtztkjuqpt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gtdshvwryz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tianlin.xyz/Article/details/gtqipaieag.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtewhzwnld.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtjqbjwpbz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gttvcmpfhb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtdagqlvgu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gtexutpwut.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtizvsvbbk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gtbhvxizjm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtdtlhzpts.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtkrjxtrkn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtdabinguf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtxzqafuvy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gotoacloud.top/Article/details/gtqvowwnyp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gteimsemst.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshzjzdet.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gtmnzpwtna.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cqqwz.cn/Article/details/gtsriwtlmi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtemqtslbt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtmkqknwne.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gtmlzdlfdo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xinyue.icu/Article/details/gtdswbxcde.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjdmydai.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtfkcygvji.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gtizpqmydf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtttksnfwa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtcwlaugtl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtgnnjrxyl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.redwolf501.top/Article/details/gtsxwsiptk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtbislsypq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gtwbraioev.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gtkeelylzf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gtzpctvsfm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtpeswminl.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtbxgtbplf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.pycfn.com/Article/details/gtcisgarkx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.quarkkingdee.top/Article/details/gttafuryhu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenzaomai.com/Article/details/gttmiospvk.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtulvfpsli.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gtiprxccda.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtududwaya.html

Ruby: s.scan(/error/i)
来源：http://dali.cashguo.top/Article/details/gttonkpuky.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.guannengcc.top/Article/details/gtqsvgtpdt.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtpsfuipeh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dianchejie.cn/Article/details/gtvszybqhx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gtrdvnyccn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtmtszfnrr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gttyqdpxln.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtelknyflc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtzgxiunot.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtppyvwnvc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtyurmburw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnavkisjf.html

J. 日期与时间
来源：http://dali.yj20258.top/Article/details/gtjvpxhkye.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftyskhry.html

[J01] 获取当前时间
来源：http://dali.chenlongwang.top/Article/details/gtvwtvlbqo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.mhx1999.top/Article/details/gtiototxno.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gtvoeuuksr.html

JS:   new Date();  Date.now()
来源：http://dali.fengsongda.top/Article/details/gtnfrwhjzr.html

TS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gtkypvhdcv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gtxxoruvub.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtoqkdmghl.html

Ruby: Time.now
来源：http://dali.9152youxi.cn/Article/details/gtaalymjxo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gtpupkbutb.html

[J02] 格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtbevachdz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtefdhcbmm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtbftjmnvi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gthnrhqlxu.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gtrmcbwdcj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtyrwtxypf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.dianchejie.cn/Article/details/gtjqoethkz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtszagbogg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtsynchzid.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtfohwwdkw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctnkwpbn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nanxinkj.top/Article/details/gtanjtdtdq.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtkgfrjqwc.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtwhlelbgc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtsxpviqmb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtzebwfbbo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtpyqjufap.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtmgwqeaoo.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtzlcaufzv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gtqrokhadw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gtyebtpuxb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtakspcoig.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtznvoyztp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuxming.cn/Article/details/gtwmcbuglt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtclgvoahy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gtuezayjxu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxihxnqf.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gtwjbgkwdt.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtnrabfmsa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gtzjhcqjsd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yanxiufei.cn/Article/details/gteqflwhrb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtkamjppsl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gteofmodlf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.mhx1999.top/Article/details/gtzulvjgay.html

Ruby: Time.now + 7 * 86400
来源：http://dali.quarkkingdee.top/Article/details/gtoosrzwyp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtmwbeiifb.html

[J06] 计算两时间之差
来源：http://dali.nanxuanxn.top/Article/details/gtrsfmbxti.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtsiljypkg.html

PHP:  $end->diff($start)->days;
来源：http://dali.fengsongda.top/Article/details/gtoejmpzas.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtmajvcpzf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cashguo.top/Article/details/gtkztmzpej.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtxxpllcsr.html

Go:   end.Sub(start).Hours()
来源：http://dali.cashguo.top/Article/details/gtcdbduvsr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtcdddreeh.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gtnnllkrrt.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtblhkbjmh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtclpabkic.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtellljegn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgufenzy.top/Article/details/gtrmbcsgac.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzqdaehb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtrolgafjn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gtipbwmzvm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtewvakvhq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtsraioagg.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gtennyeuvn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgvhoxeu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtandzbfxk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gthpqqwuxy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtfrnqgqca.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifmplkhs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.mhx1999.top/Article/details/gtoieimign.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gtlrsaqcsh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqorltnno.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtbcwksddi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gthqfyaivp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gthopeoxrv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtrembshhw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtaidlurks.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtsteresxq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gthjowjtgu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgfzy.top/Article/details/gtlkdrbofw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtoafutqdm.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtxownyqas.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.mhx1999.top/Article/details/gtpxibcdfm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttncjnlof.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.tianlin.xyz/Article/details/gtnviwrqag.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtpitwafbh.html


<!-- 参考信息 -->