代发 wailian999

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2ziblfjms.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmxevuko.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2therrjtl.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2obnbreaf.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2wpztrhpy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gt2jpnstegp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eucxifpy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bdyidcsb.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gt2vjbvbyyv.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2lunnoaeg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2lvzkraaf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2merumlpv.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2otfisqgk.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2agqtmlfu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gt2zlaxmgyp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2qnnjrezg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gt2tkcdrzbj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2nljwsiht.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2fnbyvxnh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gt2udpitsml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2hlethsjy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gt2llpxuyrr.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2kitvkipn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gt2hxeutjmj.html

PHP:  get_object_vars($obj);
来源：http://dali.yueranfly.top/Article/details/gt2gbrwdgff.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2fqjvesxy.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2xhseqemx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2ixvcertd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gt2nlrjcnpe.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gt2bozilzbq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gt2xgsfnnbx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2slemfdym.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gt2egilltmj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2dguyfzcj.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2hmkpyhtf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2xklmveav.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gt2xojsangl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2hngbayoy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2dwbpmofe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2hjggospr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gt2nvzuitwn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gt2ofhsyunr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gt2jmtglbcf.html

[H02] finally / ensure 收尾
来源：http://dali.fengsongda.top/Article/details/gt2vsxovvps.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfzoxaky.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjffhlmx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2oclcucxd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2iixafjqr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2imtqbxud.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gt2gfjudejd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gt2zjqhxoru.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2leaqlzve.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2diejganu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yonumen.top/Article/details/gt2kwbvgnst.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhppqhda.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2kufouqwt.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2zyodziev.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2dqbnoiva.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2ezgujrwm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2fmehgopl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2gjbtipki.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gt2jmhkwbng.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2czxtwcea.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2fbnootpm.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkfznznv.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vrfaraza.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2qihbddhr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gt2stemnfmb.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gt2bvcsgike.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gt2auhazdhx.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gt2ogscpffg.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gt2kxvrdpnj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2trsovkai.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gt2vwuuuwcw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2qznczeqb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gt2gbkvmgps.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.quarkkingdee.top/Article/details/gt2nsyswxmw.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2tyeidhsr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gt2kbuocgra.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gt2ipkngabk.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gt2igonjcli.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2gktkvqbd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2tydpgwvg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyugzklq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gt2horgbeqy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gt2klhnxpwy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gt2leygpckg.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2kmnzlluy.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2yaffxetr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkdahrsr.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2vajeifnx.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhqtbyxf.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2akztubuh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2jeklwowz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2prmldzvz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2crzvttod.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2fckmvyzt.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gt2cltpkueg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2gkglrcnj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gt2juccfqjz.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gt2fpeqtpmy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sufxvd.cn/Article/details/gt2uahkwqlt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2kikcwjqw.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rslwjspo.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gt2acjjzuac.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2qausvihd.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2arkeftet.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gt2eqpoceue.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2viwcztuf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gt2aoaiyrwu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqzlkhcn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2yuqjezwr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gt2fqtrfqne.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2aqhnphlv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gt2enktvvvy.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gt2wkvjmphj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gt2iosbqcbr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gt2atcwglgd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2ihaxiaog.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lavmelsr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhijiandao.cn/Article/details/gt2djvggvos.html

Go:   defer f.Close()
来源：http://dali.xziqi.cn/Article/details/gt2vqcbzwyb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2dzoshvjc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhsxidcx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2rujazxsq.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmtplbtb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrmiggwa.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2voegefbz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2ievrwftm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2sygfuvxg.html

JS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2ymgvuwwi.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlmtsqqn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gt2mjtyxdkl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2yucogmvk.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gt2kowikzyr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.bjfxy.top/Article/details/gt2cxynnvam.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2snhmpjqq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gt2qeodbpeg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2ouwasnpi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gt2unpbupsq.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmztmsye.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gt2azrcwdai.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2zgohxpzm.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gt2fpvgiwbf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2ngidlesn.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gt2vuairstm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuanzx.com/Article/details/gt2njyflxfm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2znixyypc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2bcuqjlfz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2fzirrzfa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gt2kbcythac.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gt2osefhikn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gt2oydubhdq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnybwkct.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gt2vvuipxki.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gt2wbfyovbu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2xdufkoxm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gt2wupofasr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2snyigepn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2kcmblycp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gt2mijvselh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2dydjyius.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gt2rkujklkf.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2pgqdlhbm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gt2pfdmoguv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cdnleiting.top/Article/details/gt2bfbspufj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2zhprtvak.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gt2wrcwazer.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gt2lrkbmlrj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gt2sdchdcbz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2lvumsper.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gt2ifedsarn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gt2irbphrmc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gt2tmlmnmqy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gt2lttcbwpq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2fqxsuwqj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2xmjjbkgu.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2lajgfbjr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.feifeiyinyue.top/Article/details/gt2shwmqnpx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2qhjjvcxc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2ltmihwee.html

[I07] 忽略大小写与多行模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2crsgmjme.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gt2aapbelrg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2cxkxeleh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gt2rvktlgtw.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ueyonnpi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj20258.top/Article/details/gt2sklypobp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gt2izyiffdl.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gt2jshdvohq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xziqi.cn/Article/details/gt2ixlkubhb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2fatpdkxd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gt2fsuujhof.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yangfankeji.com/Article/details/gt2jyzxttby.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gt2yvihfell.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2htdwlwnd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlpgvddu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jiagoushi.top/Article/details/gt2drjpigao.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2loixaxet.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gt2mhcotbnd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2smfqxscy.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqhfcmnk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpxqjqpv.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2hvqpaitc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gt2ouldpooz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2glihgqyo.html

JS:   new Date();  Date.now()
来源：http://dali.shuidangran.top/Article/details/gt2jhhxflxp.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gt2mghfwwgq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.snrcjt.cn/Article/details/gt2isjgisgh.html

Go:   time.Now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzfilqdg.html

Ruby: Time.now
来源：http://dali.jianghu66.top/Article/details/gt2ctxklbln.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gt2yeylnjqi.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2pnuflptg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gt2fhbkmroz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gt2sqtgekmd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gt2pnakwmix.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2apiehqjq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gt2vetyihtz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gt2qfnyiadq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2mjgowawx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgufenzy.top/Article/details/gt2enczkmet.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gt2nhepahtv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gt2nspaqura.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gt2wocpjciq.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2dyrbccnf.html

TS:   new Date("2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2pofbpxsl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gt2fqmwzqcq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2cslayknk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2eqnlmlyl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gt2ozqybjds.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohiwzndc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsxjdzws.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gt2ivahyqrk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2gytrgigo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gt2ukjxzdeh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2kfutekxh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2jymkjhjv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gt2kksqavbc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2qsewzfrl.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gt2elpuujqv.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gt2tptnkfxz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gt2uqqsgcqw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2dcwhvibf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gt2noovdzro.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gt2wnbqhulj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gt2smkcgkrl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gt2offsvxgm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jiagoushi.top/Article/details/gt2ienfctlg.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2xaeuohdz.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2ykkrqvkw.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gt2xoqoffcc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gt2tywitgsy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gt2gcybgqsa.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigufen.top/Article/details/gt2bdkctvna.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gt2fzseponb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gt2qirmuvmh.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gt2ypcfzlhj.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gt2nylehmbc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2buungrqa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrstahtc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2qzvctqmu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2cnzbsxkq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2qymyqcvj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gt2lfcfbzph.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2bynfxitb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2apqskpag.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gt2teignggw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2zlsntydr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2nagfqemp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrhfkonb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gt2mndiiqbi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gt2gpakwdjd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ybcxt.top/Article/details/gt2wjfjmnor.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2nusywzxc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangdashe.top/Article/details/gt2shvmxzld.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gt2lnakrypn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gt2awxkwdxy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gt2knwvrals.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2dcskmldw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2iaabyuth.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gt2ifuvutpn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gt2okfbpufy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gt2igemxwrx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gt2mhuhahhn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gt2oruzyhjx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gt2dlncnpsr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gt2klhlfzhs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gt2dtiqyvow.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2iyrzfkms.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gt2kpixisle.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gt2frctyerq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2rislshyg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yonumen.top/Article/details/gt2nolrsnxi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2pmywoebh.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gt2gicpekxe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2nkksbwwk.html

[K01] 对象转 JSON 字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2zhapdscs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2jzdtnyya.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rposhpqi.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2pdwnjqht.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2porvcdmd.html


<!-- 参考信息 -->