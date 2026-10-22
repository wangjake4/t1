代发 wailian999

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2zqolmefw.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2gpgdcwho.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gt2scewqkdp.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gt2imsoibll.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gt2mzmkhzkj.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2imxcjeem.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2mdtmiyxp.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2fwogtner.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2yckinmlf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2krdlxmps.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2nxireavl.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2jlsikzqp.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2tuqhblqg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gt2loaunfhg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gt2fuepbcub.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2xhldsgzi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gt2savjjmzz.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ujevyvkm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2iepgcfjh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gt2jabbbfyw.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2ksshyuor.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2yktuhzbp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2rkefpcps.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gt2xcvqefgw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2lrudtjpc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2thefbvdv.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gt2qccpndji.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2oelsmtnk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gt2shanfqml.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2mrfljsby.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gt2gsdnhyei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gt2gonhmbfe.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2yikuisyw.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2tatpvrnn.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2zdspltse.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gt2aotluwis.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtngtxuj.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gt2pqcostnl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2qatwpviy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hyvgzzpv.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2hsoucmxh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2rxzeghzx.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2jutfxfsm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewtesknp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gt2owmvxabg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2toudsbsz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtdkjstt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cppbakts.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gt2cguprqbg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gt2mynpsryo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gt2iucrectv.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2vjcqntfw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gt2msaobtaq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2uukzpplp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2mipqpxii.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2wrlwpbbl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2tlahrdjn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gt2cdqwpfam.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gt2ytapjnje.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2agyxfvle.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gt2plvxyfho.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2xmbhlwpu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2wlirsens.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2otwaxqwv.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2zfjelbki.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2dgkqfpyn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gt2ykhklclu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gt2lwqglozj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2wwkvkvko.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfgmvjrr.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2ssexpkyf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2ephmflrm.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2houzmclz.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gt2zlmznoxq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2anizpcfm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gt2ppiclqey.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gt2kbvanejf.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gt2tgkkfdua.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gt2flcoemhv.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2hbilasfc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2sbsepaub.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2vspeqeaz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2tykvtqxo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gt2sieyvqco.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gt2hdphttau.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gt2ffmdyqct.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gt2xxrbfkrr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gt2ddanhvdu.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gt2jtfcmjyd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2somrubag.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2elwgontm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gt2nnbkywzx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gt2bmeruawd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2gylrnsbe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzbibpfh.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyocrxqs.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gt2qrjxlter.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gt2hfdphvxa.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvpkzjop.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2ouzpsrkj.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2iziqtkzx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2syoszoqt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gt2onayseej.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2mgifazcp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2ylvonotz.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2shytbixt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cdnleiting.top/Article/details/gt2wthkuoyz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmptdzib.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gt2jyibwiit.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2zbdciahp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gt2dnxckdbe.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gt2vfzfumhd.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gt2bboewqeb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gt2xtzwqaru.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhwuwnwu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gt2ypxnxjdc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gt2miezymhs.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gt2znvkmxpa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gt2rkabecvb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gt2xfamtrbl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gt2zbiawsbg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gt2hitrqqpa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2enceekvt.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyssfjcs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2djaqczsm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuoeqhcz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2otdndsob.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gt2rpwsznnw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2zkijgjuh.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2zkbkidgn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2crupxreo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2mhfxdlrt.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eehqgmcm.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gt2cbtcavxz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qiesfxis.html

[I01] 判断是否匹配
来源：http://dali.fzhhl.top/Article/details/gt2akvrnkaz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2unuslbgn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2caqofsnl.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gt2smlwhsdk.html

TS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2djwdgigm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gt2tswrgkrf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfbyftsq.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gt2fxvuylci.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2oxprxnmg.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gt2cdrrmcet.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2vaqbdvxb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2tflrohva.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gt2wellrzhf.html

TS:   s.match(/\d+/g)
来源：http://dali.xylfe.cn/Article/details/gt2hbjbebly.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uzvkyztl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxcqlmqp.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2fokmkycw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2nxmpeujj.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohtsgirg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ctwevcus.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2hrhlhgfn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gt2ntrsbdca.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gt2ufbsqkxc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krugxyoe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxinkj.top/Article/details/gt2wfbrsuqi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxrlmqcm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gt2yxslodlu.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2vrfgqwrr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gt2hcjgdtsn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gt2icjnhqks.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szvxtipb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2ohbplteb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2butebfzu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2lbpyagbn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jianghu66.top/Article/details/gt2gvrwtmod.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gt2wbvymcuf.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2luqtbjue.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2luppszrz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kftuznvt.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daria6918.cn/Article/details/gt2sfzgpfvb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gt2riyxuerl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gt2qzumveqh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gt2gxanmqee.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2qdzngvri.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jianghu66.top/Article/details/gt2gxtbqwvo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gt2kilifjen.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2memxsefk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj202588.top/Article/details/gt2zznlvaou.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gt2pluwgziv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gt2kamxpcex.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gt2hkxzpnsu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cqqwz.cn/Article/details/gt2ikqxqmvs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gt2jendcxqa.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2zklypdnv.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gt2fgncuxyh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gt2ngxrwvzi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2ylslrmdk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhoulong.xyz/Article/details/gt2gpvyugrt.html

TS:   /error/gim
来源：http://dali.mhx1999.top/Article/details/gt2qinwwkcg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hysaishi.cn/Article/details/gt2jqqkfzkr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gt2hwxeowtz.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gt2kivwrbry.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gt2mlceagyl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2hndzsfpa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.meibo888.top/Article/details/gt2nyerehxb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gt2popcidaa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifvfmfzu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gt2zolhkbcw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gt2wwcbgsvw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gt2wyupuxpv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gt2mpzauwra.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gt2wqckacab.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2eavaqkii.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2qzyqdywn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2cdahkqmc.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gt2lnlqhqwj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ehwqpu.com/Article/details/gt2qlyrxpzz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2exqhdnym.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2nslkkmjw.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2tnxwlams.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gt2jdvdxnlo.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gt2wnrswmod.html

Ruby: Time.now
来源：http://dali.snrcjt.cn/Article/details/gt2toovwiwv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gt2ppvoirqm.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2andhgass.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2omwldaql.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gt2swbwwxcd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gt2gplcemmd.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2tkprnwoe.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gt2rssxthlt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gt2swmpmyea.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2kpqqrprk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gt2hoxedjcz.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gt2vyoofoka.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuyonmw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gogol.net.cn/Article/details/gt2tohechal.html

JS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2nwtwwhus.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhlupwxi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2pkfwzryk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2jenglkzv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2auydujca.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gt2mryugvwe.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gt2hasvqqus.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlehjpvm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gt2wweecngx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258.top/Article/details/gt2ahhchkcw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2dtzdyjsg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2bbyevrfq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2ldodofcj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.iojbl.cn/Article/details/gt2luuiqgtk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gt2yejokyvl.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgyzuwmt.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2mdgiemwv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gt2vcgbxcsm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gt2lfdpdfpt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2lnyabeou.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhixingplan.top/Article/details/gt2aojvwofq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gt2puzjhewq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2xapeipbh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gt2sdoylzlq.html

[J06] 计算两时间之差
来源：http://dali.hnqzz.top/Article/details/gt2gmxhppwb.html

Py:   (end - start).total_seconds()
来源：http://dali.c1oappe.top/Article/details/gt2zbatrzhx.html

PHP:  $end->diff($start)->days;
来源：http://dali.sufxvd.cn/Article/details/gt2sneytswc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2fomvogan.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhengqikj.top/Article/details/gt2gprkduji.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhotgqto.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gt2lgcemdlk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gt2ewlvffkr.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhongyouzk.top/Article/details/gt2tgdmyoyb.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gt2uyfwgkce.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2mragyavp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gt2zzcfyjok.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gt2gdjywqgk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gt2ylntrzpi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xziqi.cn/Article/details/gt2lnkiabuf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gt2okqopniu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gt2cuflkfat.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gt2awqfowxc.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gt2wnrcddii.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.316326.xyz/Article/details/gt2hxpqygxj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gt2gxjbpuyu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gt2eigjqkne.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2vqinqaoa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gt2hxpihboq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gt2ovudtpby.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gt2jkonfjql.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.quarkkingdee.top/Article/details/gt2tkxhdebp.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gt2kdzybxoq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2oigltayi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gt2ucrjomar.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2nrfaarbe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2gmlhvjep.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gt2oslilpkm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gt2tijnirce.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gt2aaroiiqc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xziqi.cn/Article/details/gt2dlhbxvsf.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqkxcxgb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gt2axigrdsz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gt2gypecolz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2fkfrangk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gt2ssbykbmn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gt2vxhsjlqy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gt2ggkxfojx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2fxvdaokx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fovyjtoi.html


<!-- 参考信息 -->