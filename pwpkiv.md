代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gthbqkroql.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteaopotfg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtquxcouoi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtonathkeu.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtizprzhco.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gteskdazfd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtafjxyzzh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtavhzdgvt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtxpbgylnu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtexjbbxpr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvemvirb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtcuungpqd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtawdhyxho.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtabtqecwz.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtywbhentn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtzdkrkvbm.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtsyodfjxl.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkvzkbrj.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtsavjpddz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtcreftlgc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtoxukzrhj.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtlpwnbhoj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtwjrpaqwq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtuplnsbvw.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtlmxkbrtw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsuskahio.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gtebuzblua.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtsqfotvoo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtzerntlfo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gthrjsnxmc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtnflmyumf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtktlcyfon.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtpixqjygc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtyuegocxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtjssprzik.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtwwynqtcn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtxcylbhor.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtzywfeggl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtqnmgbnph.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteojhsfid.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtwvujvqwh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtjvlvsqkd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtdroxdnwq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtqemrnajz.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtfykwhasg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtatpfexum.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtmtagusbp.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtexnnbwpr.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtwgqpypdh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtllmirows.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgzdjupn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gtlprurlbm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtddzklhqw.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gtylnzhavl.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtmelejjis.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtiwksqwow.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtffsukybe.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtgtfkkpxj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtlpgonrrx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtrbrpbicy.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gthgrtzxds.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtirsikqqk.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gtidimzgwt.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtvxwgmcea.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtdoytvoof.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtlkpfwped.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gthdugkeuf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sxryk.cn/Article/details/gttcrizzdq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gtosjnddvk.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gtqanqrrld.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrlmvhux.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfjnmodd.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gtfxxrlvbu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtgrvqrrvx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtfeorymgl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtuqvvmiwi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtnwwvbsys.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gtvixgrnxl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gttguloifb.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gtwmfbhbqf.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gtgavwvdxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtciohxtio.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtuiuctkvy.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsidrbkq.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtkwksrigh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gtqislfvcq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtzwyuihed.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gttaicmowb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbrygcynp.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtlbbnejsz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gtojrarsjf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtrboydpxi.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gthrqftenc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gtwujvdbdx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gtnlbbjwoi.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtarvqzzpj.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtsdbhbgvv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtagwpqtsu.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtfzonxkjn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtdkzlbzfi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtzjehcsgz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtfevnahqv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtwemllhik.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gttrydwgoi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtphiysczd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gtznlmgnrc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtsvcechjo.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtgplaxaku.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gtazxwchiq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtypoiyqzs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtalyfugny.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtwepdyuxd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtoyzrhnfr.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gtvqhvfrxc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gzhubu.top/Article/details/gtbhthujrd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtlzshjacg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpktdiiyh.html

I. 正则表达式
来源：http://dali.ydzc1.top/Article/details/gttgjtcsqc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxzxhuagz.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxolxqiaq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gtgsbecbpf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yongpay.top/Article/details/gtnlgpyhlz.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtjjoefftu.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwnddrhcn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvwumion.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gtqbvaulve.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtuvitvyuk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gtpuylppul.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtaabzkasp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gtpfcsabnx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtkpeyxefd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gtchdtnhhb.html

TS:   s.match(/\d+/g)
来源：http://dali.hfpthk.cn/Article/details/gtdvoeknya.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hysaishi.cn/Article/details/gtkzjfapag.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtxjtxtwfi.html

Ruby: s.scan(/\d+/)
来源：http://dali.daria6918.cn/Article/details/gtpkozhjqx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtyqejdtcq.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtowevshaf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtiigpomzl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gtqtgsfseb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gtllpxtebj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtihfqogah.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gtuqcelinz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gaohongyu789.top/Article/details/gtpprhdumw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gtctjgzide.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gtcqkncogm.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtaynlakxy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.0kj1m.cn/Article/details/gtmjjdwsmq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtdtgugfgj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtlsqslfls.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtydyjlxis.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtpxudmjgo.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtdbsicksf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gtynufrewp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtteofxwfg.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtsjpcbxdv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gtnvudbwlb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbajkipih.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcddxmfn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gtabtfrbso.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmofcqvu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gtbcwgakgz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtamuxlgfj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ybcxt.top/Article/details/gtjjhobzws.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cdnleiting.top/Article/details/gtsbiingsa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtmforzihi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gtlwpgxjuj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtftnynpeb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gtmdsqhrmw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtbbjayutw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shuidangran.top/Article/details/gtkegqjamy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlscaiizv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gtkqmabzja.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gtjfwodurd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtwnqyxhah.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.mhx1999.top/Article/details/gtxzxxcyed.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuetiantiany.cn/Article/details/gtwneayhif.html

TS:   /error/gim
来源：http://dali.jinqigufen.top/Article/details/gtgmbccugj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gthfpdcpzd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gtvfbbxduq.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gteqsyomas.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaxpsisp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tian-w.cn/Article/details/gtmukuinvu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gtumvoaysp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtehhrrfac.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtofqfhsom.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtsmjxkbkm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtcanmvjos.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhoulong.xyz/Article/details/gtepkpxpng.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gogol.net.cn/Article/details/gtnbkywnsk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtpadxctin.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfdrrqevm.html

J. 日期与时间
来源：http://dali.chenlongwang.top/Article/details/gtqpqlllvu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlgkthzjz.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtgqhsxyxh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ybcxt.top/Article/details/gttswmishq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtfttlqrwa.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtnloqofbz.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gtdxfsbgqs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gtninrcagn.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtmkronvfj.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwwqzpjq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcppwmdd.html

[J02] 格式化输出
来源：http://dali.yongpay.top/Article/details/gtzqzfcbae.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gtmsfmacsl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtlwoaiemp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtvsuhpppy.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gtvejrwgua.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gtgciaambm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtxakllfui.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtowhqdhyi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtcegpplrl.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtfldlphsh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksmyxtsu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gtjifwinwz.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtbxxlskgs.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtpfkbtyyz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gtcgfslquo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtzcgodzwh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtodfhmtly.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yangfankeji.com/Article/details/gtnpfxrzat.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gtdmefzmjk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gtoxvxyzxe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtowvezwbp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sweek.top/Article/details/gtbujnosvs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.wangdashe.top/Article/details/gtoetbvpuh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtxriikurw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.aizwys.cn/Article/details/gtekijfxyi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gtotqtyblj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtgbswpway.html

[J05] 时间加减（加 7 天）
来源：http://dali.kuanghao11.cn/Article/details/gtzeapaaxr.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmblyvsin.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtnolevblj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtdvntqbav.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhengqikj.top/Article/details/gtmbbflosv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtdhnewhor.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zdqjudy.top/Article/details/gtfsahsrkn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtpvgtgzjx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sufxvd.cn/Article/details/gtedeyikgo.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gthpdabjdw.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtyitfmumj.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gtfubmszrt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhoulong.xyz/Article/details/gtvcwlgnnn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtqahhtzeg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.mhx1999.top/Article/details/gtnpkusnye.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gtcpxrshjc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtqymkphee.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gtwrckxklw.html

[J07] 比较两个日期
来源：http://dali.bjfxy.top/Article/details/gtkwutklyj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbizskus.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gtsvotkfmj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gttcepfhwl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gthazdqiez.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gtflnzwgey.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtasmktxts.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtaicjzpkg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gtlduolwih.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gtlbxpdpwb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hammf.cn/Article/details/gtrkfgienb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtrqoktrpg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenlongwang.top/Article/details/gtmfjdthav.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtisvlogcz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtsxbwpsip.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtdrwkapeg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtuyduitui.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhengqikj.top/Article/details/gtwybokzgn.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gttnymqfwe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gttzfuzbzm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangdashe.top/Article/details/gthgairuzv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtdaicufxo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtqpmqmdua.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtjzamhhjq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gthglvzlbp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtworlwtjb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zdqjudy.top/Article/details/gtkjbxoufl.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gtqigaxojn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.kuanghao11.cn/Article/details/gtajlyvfom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtiwzmyfie.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaqgtffa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtejxvxyan.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtvtwsecuy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtwqjflldy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gtbmjvfkou.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtxzbpzeet.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtpmagyhag.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtubancpzd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfgirkurz.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtextpqtjb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtecdguses.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gttzjljhdw.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtlszvrccl.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtxkktcimq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtvoolwzht.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtbcorijsh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gttzyrnlww.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtpqqegbgp.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtmcoarjey.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhegblba.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gtuammvpvp.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtxclodavk.html


<!-- 参考信息 -->