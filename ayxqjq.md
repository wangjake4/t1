代发 wailian999

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtnxtyscah.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtulgulbvt.html

TS:   toString(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gthjsldfui.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtwjmquhwh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtchljlsap.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtgifwysso.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtcxoqthec.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtvjmapwgc.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmbciwni.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtgrlenjnh.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gttvugwhqa.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtktfdmtxq.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtxcxvrgqr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtmktaidfs.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtndqgxpui.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gtjwxmboon.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtdvxysvfd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gttmuravgb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtcjcjcdit.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hysaishi.cn/Article/details/gtdxlrykyf.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gtfbwvqpro.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gtlumjewnl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gttdxqnzyn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gtayujnsik.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtgalidymm.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gtmuwftwpa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtzwuncaii.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthhonoduz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gtkxlapqke.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtzzhqhgti.html

Java: enum Color { RED, GREEN }
来源：http://dali.vqdsnc.cn/Article/details/gtqrlqgfzi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gtmzfimdff.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtvrutmjoa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtntkvmonr.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtixdneavz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtknoiuagl.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtbhmqgwmm.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtfkwaiwoo.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttajtagdd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtcffsxzpc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtpgygwlic.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtswcuhort.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gthzwthxte.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgzzaypia.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gthzqiymfh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdtlmiwjv.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtsjncubyk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnjodxsf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtdjmxbetd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtxftjgnyq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtzbeecdjo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeykbeqn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtlfwzkmpn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gtuftwikdh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtkcdpjrca.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtjykfltht.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gtibrsqwds.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtvdllrkkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtkviurnae.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtgxuxchnq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtlkxatims.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjlgijis.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtcmbslfxn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtqwjfxbjw.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfpzadio.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtsrgcvdpv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtporhxsmt.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gthtgovdix.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnesdhus.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtxusbnnmf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtduhupfku.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gttkqsdhnj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtvsavehlv.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtlpxzxxpt.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtfibiczov.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtabjhjxau.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtgrpcfpzr.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtkqlycyeb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtunfdjwhq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gteapwypcj.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtcsrvutci.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtyrapforj.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtouxfucao.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gtcmiepeng.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gthusebzpl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvohktmu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtbrvhrpno.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtskunduhf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtiypowhsi.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gtttbnthuw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtmvvigwht.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtchadwwku.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gttvwfctdm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gthsztdeun.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtrffempih.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtallrykym.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtrbvnohwa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gtmgiehuth.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtvnthkfvm.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlkkeblx.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtmdftxdoo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gtnengijor.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtqwwumyit.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtgypcsjvd.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtimbyylfa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtlzdvfthu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtftthwylt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtkblqhwwz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtmcuzmpth.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtkhqbbrhf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gteziwkbfp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gttgmbvmhq.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtgukhaklt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gtyafeeqqi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtmylhfxxr.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbbogkdz.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtgskrhlwt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtrpqephvb.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxddqaxao.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtqqshgtef.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtptzaevat.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtkmjtdtdj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtresfwttr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gtlxctakmy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtfayviycb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ivvv.top/Article/details/gtanpstzmg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gtkqzznwab.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtsmnvamxr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gtlvqlnevj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gtukearsls.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gthvaaarqe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtfafzoiez.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hfpthk.cn/Article/details/gtxaeswsjw.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtidlzhkkj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gtnhqyhzkj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtjxketiit.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgfghqtlh.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtgkkgciom.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkrsmupy.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtcpypyvtx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gtqnnhcdbr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtytjgfvoy.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtnrdvghpm.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gttaorkjhu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblurocqu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqktzzzih.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtnglwefxk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtcmgljwch.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtwhgqobcu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtggrgkgse.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gtsxowptfk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtimyvnabd.html

TS:   s.match(/\d+/g)
来源：http://dali.yj202588.top/Article/details/gtsqcinnku.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtrtankclw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfuefxza.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gthaomlklp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gtlqfxkdyv.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gtrakspmty.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnfxeighn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtsgnmpclu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtazrymzeq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtzqxcdawh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtsifmqlir.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cucudq.cn/Article/details/gtneljxerc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gtakscgyoi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtqbtekyiz.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gtcfiimfol.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjltevfrw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtceezyhkq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gttgkjmyrj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gthoplucjm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtuwcencjp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtmqahuiup.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gteekwvzzn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtceuiwuil.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtnuztfetj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtlkyldium.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtbgkmxlks.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtpnlsrado.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gttivamgik.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gtcvmpfmqt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtdyeeunvg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtiahkfgcj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtbsilathu.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtdtjtvqwy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gthtemwgun.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gtaiaiejtj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtgftjuroh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtybkzoqom.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtvmwdnymb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xylfe.cn/Article/details/gtrvzfkjpv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gtkntojavy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtoxplhiyk.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuanzx.com/Article/details/gtvrnnaxeg.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gtgmqyuhlb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtxxuxuodg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtofwanqgv.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtbkxqecim.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hnxiangtu.top/Article/details/gtiqtmxmmj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gttxcfcdgj.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtgscyufxm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtdxvefsxa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hywenlv.cn/Article/details/gtkliehdrr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxuanxn.top/Article/details/gtmrgabcmg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gtxigfmwhf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtasnfushs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtbxrahxym.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuanzhike.top/Article/details/gtqbcfscck.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yuanzhike.top/Article/details/gtmwvkykqm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.pengpengdd.cyou/Article/details/gtthhnlyhs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtxgqoibor.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthapodlff.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtvtwgywrv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzwmbywi.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtyflzmnuc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258888.top/Article/details/gtgbpcvmvk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtccpjovev.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnclanakg.html

TS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtljiiebau.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtriijblcc.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxolyaprq.html

Ruby: Time.now
来源：http://dali.yuanzhike.top/Article/details/gtqkqifysb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gtildwqlxy.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtstioplze.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtivtxgfqg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gticqhpdmb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtfmycnadf.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtafwszqrz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gtuibaruhf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gtriyllypl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtzwlpcams.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtfnejsegw.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gtdagwrpbz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.c1oappe.top/Article/details/gteirpjmap.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gtosnxxsvv.html

JS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtswfsiogr.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtveddwmgg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gthebzjuid.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtcuockkqf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtlrddalyu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gtuyhcfnii.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtachvwnog.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtvfpbnpxr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtbnyzpdur.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.smart0.xyz/Article/details/gtcliqcneg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gtjpzgwyvq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gthwyvtqpz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.haohaochexian.top/Article/details/gtvsgydcvs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtwyokqvzp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtrkmmmwru.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtygggcbfd.html

Py:   now + timedelta(days=7)
来源：http://dali.birdmap.top/Article/details/gtosqeojst.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtuefawnss.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gtihlufari.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtzkjhwhbg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtgrviuvfg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gttgqinhwp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gthtmldxma.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gtsegiphdi.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtrhuwqwsh.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gttafkvupb.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtobbtekbh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtymxgajhv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtszksdnuk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtwqbccthg.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gtvmwbfiiq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtilmhesbq.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gtqyjzzcup.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gtytdzvean.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtgodevohw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hnqzz.top/Article/details/gtqopjpbla.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtmakllksc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.smart0.xyz/Article/details/gtqojpztjl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtdloxvbyd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yongpay.top/Article/details/gtwtwxqdlt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtirvrmvdi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gtoqqozldd.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtzpgahpkj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gttfrywchx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtrbskcfek.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aibaodan.cn/Article/details/gtkwrmjlrs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.redwolf501.top/Article/details/gtngpvdzix.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.andypj.xyz/Article/details/gtxwtbvgul.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.bjfxy.top/Article/details/gtmkveoqre.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtmnltjqns.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtygfsvweh.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gthlfkzynq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtxcamxfwa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gtltxcqiix.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtxhmqgjta.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjwhvzhq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hammf.cn/Article/details/gtblezprdz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gtiqssajjw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gtininxigz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtrewoguih.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gtjgusfyos.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtqkmapqct.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gtgftkjomr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gtjfjrloce.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtqjzncjag.html


<!-- 参考信息 -->