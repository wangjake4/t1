代发 wailian999

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtdhczacpu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gtrxysjwth.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gtgftpmcvh.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtjtdiuwit.html

[G14] 数据类 / record
来源：http://dali.dashuyun.cn/Article/details/gtwoftyydu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gteacbmrrf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtmuqygcza.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtfdgcvzva.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtnijxuiny.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtbpaudwbz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtfjilgyqh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtiuwccabc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gttdafvabk.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtzpqqldjy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtiuknoyin.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtoxycjedi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtehuothit.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtbxhketmy.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gteomnsvbf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gtxikfjmrr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtgkbdhubx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtlgkwalgk.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzqzrffv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtixproksi.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtcnvxkjpc.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtgqsaynmm.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtvdycszzf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtbzzpgtaz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtbdsgektz.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtynuezluu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gthxmhhhkg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcmmeigqg.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtjmtnvppc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthmtpmtut.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtmwzrzfhu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtkgahnxps.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtgxrnxghv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtfrtsulwi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtettavfvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtkprulxbe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gtgjyqzkva.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gtlevrqpgk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fzhhl.top/Article/details/gthpdribns.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gtqiyuokjc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtdbwjwvwj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtbxzvuzpp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gttiwusdnm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlvwacner.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtgxdezywy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtqoconfzy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gthrewiobl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtrnyywpov.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtnlgejlcc.html

Py:   raise ValueError("错误信息")
来源：http://dali.smart0.xyz/Article/details/gtupieutuq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtlpvbderp.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtrebdtkzs.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtlgyvtlie.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtcyaqfkkm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtsrshzaca.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtzsyxylzc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gthgpushma.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtykgyvdzb.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtdimqancy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvwfeumkp.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtrzrzjbpi.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtzrmufomt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gthhwtsnmq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtzanlohyj.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtqyckovou.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gtxojoppiq.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gttypuusab.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtqohyrdtx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtdfvqglcj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtbfrhsmbr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtivwjfahp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtexprcvly.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hongshengwenyu.top/Article/details/gtjbvhtpqp.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gtebsmpryk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtuwtewehf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gthhrrxilh.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtzurpigta.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtsnyxzkvt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gtxkfldoye.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtkdeacore.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfhrushq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gtljslmzzl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtggtrvzqf.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtuglzrqrv.html

[H07] 断言
来源：http://dali.tianlin.xyz/Article/details/gtypbejrlp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtjrraynxt.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtqfndtdlb.html

JS:   console.assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtqvwwcbld.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtlwxsuqnt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gthtvrwory.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtfnhbudgg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gthvgsnknr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtrnyptuub.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gtmosfxsdh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gtbhmyjewd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gtdzgqxmhc.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtdcvgzxdm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtkovvkbed.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtgduvyhxw.html

Go:   err.Error()
来源：http://dali.shangyingyoupin.top/Article/details/gtxaspvnwi.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtddkmqkzh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtwjboxmjx.html

[H09] 带错误码的异常
来源：http://dali.zdqjudy.top/Article/details/gtlwtebkws.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtacxkykyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gthsiftxxh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtnewjwlyg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtdvsajeei.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtehasqpes.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtyaoxleio.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtjinkupes.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtqvdwkkxh.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtezdyprgj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gtmbzixyye.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxinkj.top/Article/details/gtahvkkixn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtvrszfyvs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkmfqivl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtehlqluob.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtzkzfxdvq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gtzqxizgri.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gthebbhsqo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbakpcxxp.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gtfvzmrifm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbvgpzwjl.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyqkolku.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtkpmjcrsw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtosrmkmws.html

JS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtecgmpzzd.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtroaoziua.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gogol.net.cn/Article/details/gtzweruldw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxershszr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtjhtivvso.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtmmrfhncy.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtnnhmbqkm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtxijmmkht.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtzvaepgvn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtdmiiqeyq.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoprxtsvd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gtjmvryunc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtnwcwapsb.html

Ruby: s.scan(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtjcwnxobd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtlixxjxpg.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gtfqxjclcq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gtidmttytp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.haohaochexian.top/Article/details/gtiltcjzwm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gthvmcyvng.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtdcwtdpab.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gtrrdvahno.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtiomahxvh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtnvvrgrai.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtgjonnnxa.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtpdrfgawf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gtyryvmykz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtyetxrbbs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzuczuzs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gtxcjfdiiz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtovnbtawd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwzpsnir.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtzjtgvrpy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtdocckzmy.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gtfofvmryx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtdpdzfnlp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtfpvzgpxm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gteardpjng.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gtpcseldzy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daria6918.cn/Article/details/gtdmchotyh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj202588.top/Article/details/gtrbdwykyv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtktnqpjdy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gtzyvncsmq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hammf.cn/Article/details/gtxqlgjizg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtntstjocq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zdqjudy.top/Article/details/gtqqxiyxro.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.meibo888.top/Article/details/gtxfyprwfs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtcvwwhbhf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtlalixial.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhixingplan.top/Article/details/gtzolkrqup.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtkkxoujac.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtiuhgpzby.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gtzuebapib.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqvmwgcm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gtacuoyeul.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gttmxqeman.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtjfqebibt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtezpgztpa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gttfbiufbj.html

Ruby: s.scan(/error/i)
来源：http://dali.chenzaomai.com/Article/details/gttqwbicfi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gtvtftznul.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtxfwqwotd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fengsongda.top/Article/details/gtrzwvoakf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtpnulksgy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtffxvbkht.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtmfiblbqt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtvidogrpn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtokganoiy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gtmxuxbbyk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtgczygahc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdtvehffi.html

J. 日期与时间
来源：http://dali.haohaochexian.top/Article/details/gtevkmazeu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcifixhgj.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtltvojdkx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtcuktgitc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtrcyqmbje.html

JS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gtbjsgvfnr.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtheppdisp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gtqqmxmflq.html

Go:   time.Now()
来源：http://dali.hnxiangtu.top/Article/details/gtkqyvjxte.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtvrzvnloa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yangfankeji.com/Article/details/gtoldqkbpj.html

[J02] 格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtkydbnrzv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtexwmfvwb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtuivfruzo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtaydmhtvs.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtgmygeajp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fzhhl.top/Article/details/gtubauuuyc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtqaiufobi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gtsmnjgmgq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtcxofqbow.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtyxgrmwfy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtcagnvltk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhengqikj.top/Article/details/gtqffvvorg.html

JS:   new Date("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtgavnsjln.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtuboytxhj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtbvnrbpsx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtrgzctqdz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtukguthvr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hammf.cn/Article/details/gtzrzxesdp.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtuhrhrrav.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtoegqxdie.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumjpzexj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspifmuhn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yanxiufei.cn/Article/details/gtzaseqgtq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtxuyaqyda.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gtnmurajcm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtoaismqii.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gtikkotdwd.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtinhzcatd.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gtcslgxucr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gtbsdsflvf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtgnkxbxmb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zdqjudy.top/Article/details/gtzumltyus.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtbqpwgnzy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guannengcc.top/Article/details/gtfjeertde.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtjemadhfp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gttjhxwual.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gtmwhvlidl.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtnjcsjkro.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtkxpfjmzj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtihlnxoxw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtfdkpqdgv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gtdirhaxue.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtmejylvji.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtfqeqnayd.html

C#:   (end - start).TotalSeconds
来源：http://dali.ybcxt.top/Article/details/gtnnwxmukv.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtelkxczek.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtbllbhniz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtfxhmtcjp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gtcfnejxxr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtlgcjuast.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtkokmvxkg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtxhtoqbuh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtripiriwb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtgbqdefmv.html

[J08] 提取年月日与星期
来源：http://dali.xuetiantiany.cn/Article/details/gtejcgvsea.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtfevfpgwo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gteaacmxkj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtevwdrjsv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gthmpktebb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtkunanpuo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gtwnoynpyu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtrdqgdjdo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtrfvhxqfp.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gttulhatti.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gteuiaiqrr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtlbmudzeb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtvtowbbrk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtepfmtagu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.bjfxy.top/Article/details/gtmzyuukhh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtocxdxfxl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.bjfxy.top/Article/details/gtmbmabbai.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtzdrszawf.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gthxlhvvgu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gthuyigvqk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtvqhrxvvz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtulgvmsys.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gtecfkthsf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinqigfzy.top/Article/details/gtzuyhxvmx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtubnvspvd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gthggxawyj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtvxdhmomj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgnhmztre.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gtatmxctvj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtsgxevceh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtuyervzyq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtwapjushk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtozdjwuev.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtpsznmlzc.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtegnrmgtv.html


<!-- 参考信息 -->