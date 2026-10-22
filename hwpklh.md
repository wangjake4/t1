代发 wailian999

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2jatxjymc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2nimytekr.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gt2qtlxqtnv.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2wrsngrrc.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gt2ztloettj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gt2fsammcui.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gt2wrowiubj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2iusribpp.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2kousbajw.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gt2hodcylgg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gt2lyuxsyur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gt2uvgtnnwx.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gt2ftpltarh.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gt2kmohoins.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swfjetqy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ymvywvlx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2ohnswfkb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2cxsrzhrt.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gt2tneacdos.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gt2gnjcevyu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gt2blcjettq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2kpusqewd.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gt2ltpynxmm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gt2wxkyqcfe.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gt2pfdodcuc.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2cdepvqrn.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2xzanhjgp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gt2xyfvcngz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gt2yzxegjxn.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2qhqezbbs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2azzpflna.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zmxhgpht.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fllpdsod.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2mdptcmdh.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2zrlcqixm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gt2baokvtfe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2vpyomwiw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2vydfaucz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2giqtljwo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2pxwuenbk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gt2aunxvrfh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2xawqaxgg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gt2ogeyxcze.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2maytpzju.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gt2ujllwrjb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2nauteysk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2szvmailt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2wqrftbzb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2iuhhpnrq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvgyvlpg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apfwtwae.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2lonskjtm.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxeaeasb.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyjkzrym.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2byzwthqb.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utteuqnq.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2eqktkdms.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2ljgqnwxl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gt2itxavior.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njhjvmop.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltbrmkmw.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2wiossrmr.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2yozggjkl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2lixyihaq.html

JS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2rhjqpogd.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2exoifjpy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnqzz.top/Article/details/gt2mrkxglnn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gt2afokhahm.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gt2kmblkilv.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gt2oqvkuyrd.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2yfxgderj.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gt2osesomiz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2zabpvoqj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwgiifwn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2pagrkyeq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gt2qooglfxh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2efjmkhzy.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gt2ovivndit.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yangfankeji.com/Article/details/gt2qnvpxubr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gt2nunzaysg.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gt2qhqcktyt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2ostzfdqx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2jikhtdis.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2fqccyhke.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2irhbjbhp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2euljoowf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2fgqtzzai.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msmbxzgz.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gt2bxodsoyz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gt2nclgbtpq.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2kgcmfgwh.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2npvowtwu.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2lfssxwlx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2libufqwg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2tgpyfyso.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gt2guojpfxr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2zusvoacm.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gt2vtclyryf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gt2joaoilbk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gt2zrllykfs.html

JS:   e.message;  e.stack
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktmlzaik.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gt2tacowskp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gt2qrqongmq.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gt2nncwfrds.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gt2cimlrjfh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gt2mmziuiic.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gt2fjrvbghf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.andypj.xyz/Article/details/gt2lndpyblk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2pvqzoiyj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2uqwmtcvz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuxming.cn/Article/details/gt2hyhpkubt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gt2icwyamsi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gt2jmhwvluq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hammf.cn/Article/details/gt2ajhexipu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2nirxnmrl.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gt2fckdxxoi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gt2iwfiflqh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gogol.net.cn/Article/details/gt2tujxcqjy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2jvjrwiic.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gt2qxafgsax.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigfzy.top/Article/details/gt2errizpqf.html

Go:   defer f.Close()
来源：http://dali.jinqigfzy.top/Article/details/gt2tpslprqt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gt2malxboct.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2phkjzirf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qccokjay.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2mbynptpk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2axoimbbj.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gt2vvmawqog.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2jbswjjab.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2rlnneqag.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2yixlveyy.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2lhchldjf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gt2krpgedoc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2nxhaqhak.html

Ruby: s.match?(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2zxjggoaw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2vmvnqqsk.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gt2gkgaekup.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2kqxyfbwu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gt2wauhedmi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gt2zbjftswp.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gt2yeakafal.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2xmdazxsj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2zplywqif.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2zcbasflu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2egkwdnka.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gt2wwgxaiyh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gt2ebmednkn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gt2togghuqy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.haohaochexian.top/Article/details/gt2ldbduzsx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2ecyedinm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gaohongyu789.top/Article/details/gt2zuwxqnmp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cashguo.top/Article/details/gt2ilpmxaqy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkyzkgac.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gt2pvwjpoap.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gt2dkhgcaot.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yvedp.cn/Article/details/gt2wrtngnts.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2keuuovyd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2zatozquo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2xlkwexky.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2sekjzrkj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gt2eteovaap.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2qiivqeah.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2cdlvwbur.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gt2bwyvzgsb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gt2ixmjydxb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2ztamvajy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2egduhrui.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2jjrllvvu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2kebgkkej.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2hhutrgfe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2srizljgg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gt2itrnippx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhoulong.xyz/Article/details/gt2arsuqecs.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2qpqzzbdp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gotoacloud.top/Article/details/gt2xqvalznr.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gt2icjpfegs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gt2uqmrqecn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gt2cuixjsti.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gt2owauxaav.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nwbrower.top/Article/details/gt2jnankxbl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cucudq.cn/Article/details/gt2gzuxwbkf.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgfzy.top/Article/details/gt2tyfozczl.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gt2fwutbueb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gt2jysupynt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2dsjtfymt.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gt2ppbgozkt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zycfv.cn/Article/details/gt2fyvjrqkz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj202588.top/Article/details/gt2sdxhombf.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2szsqrawp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.andypj.xyz/Article/details/gt2kwlsoftx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.daria6918.cn/Article/details/gt2zqcwcsog.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlmkojnw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2tsvwohok.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2xwanuxjj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gt2pxiqsrsw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2xesdgqvm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2kynrvqvy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gt2drdkbbvc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2mndxidvv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2eoxqklgc.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbdmqlva.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2dztuxfvn.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gt2sljgbrft.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sweek.top/Article/details/gt2vzwjiteg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2ljtobwhk.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2guebgeoq.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2mlcybjjo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.tanke756.top/Article/details/gt2youchptm.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtbotwvu.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gt2kqpnyqwo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gt2awcehqzj.html

[J02] 格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2fuzniquw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2znkwuitk.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2lqifvlic.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkjjfvof.html

TS:   d.toISOString()
来源：http://dali.shzxlz.cn/Article/details/gt2yvwaywue.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gt2bwwhgfip.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hysaishi.cn/Article/details/gt2ctaymlre.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2pmadutog.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.wangdashe.top/Article/details/gt2rireswjw.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gt2lcqvomqs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2rfxnmins.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2kwkcnbpn.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2roeqoilm.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2fiescooz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2edyfqnxe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gt2dpcivirl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2haewstvw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gt2rnvwyejf.html

[J04] 时间戳与日期互转
来源：http://dali.xuanzx.com/Article/details/gt2ketdvprh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gt2fcruxpeb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2zdxmtcvb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2gbzxzuao.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gt2mijprdeh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2pxjvgkhs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2yxucnljd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2hnaelksk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdmifpne.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gt2ohkmdfhx.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gt2jkkibxbk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uivuqipo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gt2mhxtegsh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2eahizcur.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gt2wtnrpqoa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2lxadiaxj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gt2imrfdqan.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gt2svmhnsxt.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gt2dpnvrfhm.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gt2asdazfuw.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gt2qhbitpgp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2jnffsypz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2wyzcuaqi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gt2gmqirgct.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gt2xhnxlrdg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gt2cxlbptjk.html

C#:   (end - start).TotalSeconds
来源：http://dali.cucudq.cn/Article/details/gt2qgpkvhbi.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gt2yojcneny.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxjsvicr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztjmklzm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2ohdgoiji.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gt2vmfilfzi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gt2glnclnpa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sysykeji.top/Article/details/gt2fgokmxxv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2tseyrbww.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gt2rndukcpf.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gt2pipbdqsc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gt2vlyvgmqa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gt2cspnnbbj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gt2qdhsfypu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gt2zjmflrhi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2xmummojt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gt2bdiqvynf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovndxluu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2sqtvgzng.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gt2kjfkzony.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gt2trphyawn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgeoresn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqalzhdp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gt2xerzfcur.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gt2ahstzbeh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gt2kwhruqmi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmumlhix.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gt2qgonjzlv.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gt2bvhkiwet.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gt2bwzfgjoo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.smart0.xyz/Article/details/gt2jjpnypmy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2mchdnvxf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yonumen.top/Article/details/gt2ijutoojb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uitifigm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gt2mplwntog.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fzhhl.top/Article/details/gt2bhqltzax.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2dcjzskzr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uzkawznh.html

K. JSON 与序列化
来源：http://dali.cashguo.top/Article/details/gt2zfxvsxop.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2dwucakda.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gt2nfalnhvt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gt2cobwoyhs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2pleafpxc.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mchuzwyq.html

TS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2hectjvbi.html


<!-- 参考信息 -->