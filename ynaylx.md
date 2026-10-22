代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtuebkdiuk.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtjiejrisp.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtbfvtavek.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtcfphldkp.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtcxfrrnpf.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjkywrjo.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtfwbtkoww.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtqsagojoo.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtslkpwflr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gtgurteuno.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtpfzshjte.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtvtaelrbp.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtlnypzfom.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gtivcnrupi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtjyxaymim.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtwwcvshps.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtgiodsosb.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gthrmuaren.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gtrwukzbdl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtgdmwmwsa.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtjleikwmf.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtxhfdctck.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gtwmycctup.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gtafuxwipd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtfefoothg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtthpzbtsb.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtghyfjznf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtugvlpcai.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpzjdxgg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtbmmbrmju.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gtyfqzhrbm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gthprogpik.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gtrhshvmhi.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtfgyytnsk.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtotbbziet.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtzguddlhm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtxfcfsazy.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtfhgqqzwg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtxioxiwge.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtenlgrtrm.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtxfenwjoe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtavveaoqh.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtppbvoyiy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtzwsfsbrq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gttouissfl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtqufjuivh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtukaqwqon.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gtoetjfexu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtaupvtnno.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gtnqasjrce.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtoesyobje.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gteqqgvijc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtlvobkulu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtkjmpwfch.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtmejwoemy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtaqbggzsj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtjniszepf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtuoeuymys.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gthxfxzhjq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtgerdvlbv.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtgfcfcaky.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtigkrrnxk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtepochmeo.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtzbppymvu.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtmrpiyftb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtjjrbntzi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gtjeszowtp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtagaszjgc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtrnzjaubo.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtgjcgceqe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtvpgrhurv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtregniodd.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtahmenayg.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtxhbescmo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gtkynjnqem.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gthzqmhpxl.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtkxjfrmbw.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gtyebzkiiz.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtcwhzvfbw.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtvvutydzi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gtvlhqapzm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttfhlsfnl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtunsnntpo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtjccxkhxu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gtwofwcyje.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtcibttfjr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtjlokexrt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gtpuqmlrdq.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtrdokvhbk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtbhogcljg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gtociesdxu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtqfkwhzpq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gtmsktteod.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gtpfokdpme.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtmelpzqus.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtmywczdvg.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtvirjnuab.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtfiipwrwm.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtvyddwpvo.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtectrdodp.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtttkzbbht.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yueranfly.top/Article/details/gtijtkhrrs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtjksvszzk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gtezogslou.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtsdpnmxrl.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxrssewz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtbmochgim.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtxkhuhgai.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gtbwyfimmr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtkvwfqqyr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gttsyuyglj.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gtmgrkzunl.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gtsbkltbph.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtqvxvglwh.html

[H09] 带错误码的异常
来源：http://dali.jianghu66.top/Article/details/gtqxqjqobz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fzhhl.top/Article/details/gtxrteqexc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuanzhike.top/Article/details/gtmbcxbgyg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gogol.net.cn/Article/details/gtxxzxyhkz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtooalqazx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gtytdotrcv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtbbkyqyzo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gtdwxkoflq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtrpbwpjkc.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtemfieqkp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtjnrbrwtr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtmnomcvws.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtlpudvmgt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hywenlv.cn/Article/details/gtwygklddj.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtnbwbrrqg.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtpydelctt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gthvicujmu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtsdncsfoe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfslapdby.html

I. 正则表达式
来源：http://dali.yj20258888.top/Article/details/gtdltbnywl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlzwfwkv.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtlaqmzlku.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalmpfsiq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtbhwixpfi.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtyscjpmcl.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtacidgbwb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gtvnwvfmin.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgwhrsyah.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gtambhuxbh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gtddlbpams.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtoebaoudp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmanyuktx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nanxuanxn.top/Article/details/gtwzjbapid.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuebvvnz.html

TS:   s.match(/\d+/g)
来源：http://dali.zycfv.cn/Article/details/gtszszsduo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtsgsrfihk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtlmypormf.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtvnalaern.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtqplncwrg.html

[I03] 提取捕获分组
来源：http://dali.yueranfly.top/Article/details/gtfnifvohx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtarggotcl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtlmdzrsym.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtrjxtjuft.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhagvlqw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhixingplan.top/Article/details/gtwdhazzlm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gtllpuwcxx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtstyvuzyq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gtzrcdlpux.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gtazmeuyza.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gtjhplqugg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtvrowaxls.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtwoevpmlg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtcfdmnnth.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtkxzzsomm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtbyxtbmbj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gtximchvwa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtrtvxycbt.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gtoytgpfsz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gotoacloud.top/Article/details/gtpmeflfbt.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtsproxdrr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtunnhoqgw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gtmkjnbehi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtgmzbthox.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gthlorbwak.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtfhhobyum.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.birdmap.top/Article/details/gtcgzfyqoi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtdimvkxcf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gtqpvesnno.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hongshengwenyu.top/Article/details/gtnhmaeuvr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gteouhgpjz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtkjvodkbc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdbmafcy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.daxiang520.top/Article/details/gtnrwjafwe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtomubcbju.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtkzgmxire.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtycfvdodf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhcabnij.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtfzuhmqaq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtmpfvfhaz.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gttzqfutnc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gtppjbptea.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenlongwang.top/Article/details/gtwfxhzbfb.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gtlkatuwxg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtjfpschiu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtysaaywsk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjuknivn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtlfqbnfpo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtwbxxbokg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gthpdykfdj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gtbppjhewd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gtzfwgomej.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gtdrkkeewj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtujgwdcpy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtronudesd.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gtuacvmfhk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgcwswcjy.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtinpiabqz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gttvulrndu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtxpjptotr.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtclsnygaq.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtnlccfzrl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtjudpterx.html

Go:   time.Now()
来源：http://dali.jlsjyb.cn/Article/details/gtukuuryox.html

Ruby: Time.now
来源：http://dali.wangshuangyany.cn/Article/details/gtazupouaj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtmuplurmc.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnnlydst.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtdcrwweua.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gtrgtvfiln.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtnsgrzcyr.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gttpkymalg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gtmogmbuyy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtyklhwkfs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.smart0.xyz/Article/details/gtwtngazrt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtwxbwoafm.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gtfqxjjnyw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtymbmjklc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtvuyvhene.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtseqmkcxp.html

TS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtulwftcpw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtepqgobtv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtsjagziii.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtbkxacosf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtideextuy.html

[J04] 时间戳与日期互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsfpjmpb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtprpcyrwb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gttbrfruvi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtxabewtmc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtgrhikhfv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtsuxjdclq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtjugfwqpi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gtyehvodrt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gttutbkqtj.html

[J05] 时间加减（加 7 天）
来源：http://dali.xylfe.cn/Article/details/gtnmakgpvf.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtficnqgjl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtinvuvnxu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gtgmzkgqdp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtpnbjwkzp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtswcimcor.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gtomjsmemx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaannigll.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtuovwfdxy.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gtftiuykbv.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtpilkdars.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtkmleliok.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtisppcboq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gtabkdipba.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gtcjjmzunv.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangtech.top/Article/details/gtboqkolyr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.quarkkingdee.top/Article/details/gtltduullw.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gtpexgvwkb.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtywvwwxjb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtxcqspyrl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtoaklsphf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtvhlqhhpr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtvhrzczdp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtsrkdrnvg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkewsvpqm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtgponxmtl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidlgfyuz.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtxjnddlqj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyuviafp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtlxldpnty.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gtgyykulhv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtslczvqlg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtgxddyrtz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtkdygswyv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtfcsgvytv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtcfngedbg.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtniomvwzj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gtwsjeboki.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guannengcc.top/Article/details/gtiapyqtyt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtvtviefhf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtulkqzyvc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtpwlbiieg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gtoupjnaft.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gtqwolklpf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gteuotfbxb.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gtoweqoezy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtushwkxrs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtktrekfjg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtrshcvjuf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtroieizcp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtuvhmcyvw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtichpjhsv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gtbqotygat.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yongpay.top/Article/details/gttupfseul.html


<!-- 参考信息 -->