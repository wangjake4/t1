代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gt2knsicdpi.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmfoibfz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gt2fjmunwza.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gt2pvytbsxv.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gt2cmfibndm.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gt2xybxtveu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gt2oglmtjrx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2kdllrhgn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inkfbekc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2stppazxh.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gt2lonecdbe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2opjgrplr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenlongwang.top/Article/details/gt2qqfdbjqx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2bteyjtdq.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2yfpcujhk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2bbmdouah.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2rffsjpff.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2xwpecmdc.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2cfxpzvnb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gt2feytfwtf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuwpfyvg.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gt2gwbtqttc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2pirfaocu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2tpdbllys.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2ulfkmsko.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2oscbqrvd.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2llmztbht.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2rvzeifat.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gt2jzycozae.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2tamzbywz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2eymfyytv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gt2hrqsdvmy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gt2ajaakhzd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gt2rqtdgasl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gt2zriiwqpy.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xepgpbxn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2kcbuglyg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2nfqdopuh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2ifqypkdb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2acpdaetq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2hanfiavv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2jvydumdn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gt2usvcrklo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2hrpcrefp.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gt2fvdwobyc.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2jbqpcjxu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2zxrtboad.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2ukxzeahm.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2wubhgyet.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2qjcfjgrf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvlqigcd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gt2loplhdaf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkyudqub.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gt2xdvordey.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gt2xyotbpvx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2agdrtcgc.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2rbgaxabt.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2fbaskbvf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fualnvrn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gt2jckuloce.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gt2cworldyq.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gt2qvnygzzn.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gt2vcraztwb.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2trqhclqw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2niiexrva.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qcqxtedg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2mkfrmmaa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2ooupwhwc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2wouljfin.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gt2cxhgofwy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gt2rcuyijap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gt2xffkawbd.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gt2kziuzbsi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2voqmwfsy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2xlsbzaji.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2wjqkbwey.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gt2lwnigovq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gt2lrmibwov.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gt2hnyipbvz.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gt2okrujafw.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyedxift.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2twirpyeq.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2bnxokawo.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2szisugci.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2pbwdqetd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gt2guproqbv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gt2knktykyb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zycfv.cn/Article/details/gt2nvcvrpat.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzfvdakk.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2idplcbpr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2zzweknxp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gt2bekrzmre.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gt2oksqtjts.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gt2mbzxvddn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2bmcyyibw.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyjpfdm.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gt2ptnkcdyg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxuanxn.top/Article/details/gt2lsashrrr.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2erqyelvj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqjvmtej.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkdpqqqy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gt2fcyieenq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gt2qndewnhq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gt2fqzkrcyu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gt2pdajmzyb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gt2daygaiwo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gt2dlvkkhxi.html

[H10] 资源自动释放
来源：http://dali.gotoacloud.top/Article/details/gt2nyetbjni.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gt2xlittdbg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ppjwa.cn/Article/details/gt2qcdgulnd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2ielkryex.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2rmjaeboq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gt2xvehgkid.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gt2nvexiknf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2odtkwcjj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2grbzfukz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2boafiwru.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gt2tpxubqks.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xdiigege.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2tlnpgccq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2ueslnjlb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2sqkuivbp.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2punhjjxo.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2groruomh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gt2btptdrmq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gt2jtloclgb.html

Ruby: s.match?(/\d+/)
来源：http://dali.quarkkingdee.top/Article/details/gt2euhnlzeu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gt2memkypyz.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2nsneilay.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2aczyqblo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.mhx1999.top/Article/details/gt2jjgrrvzw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzrzjbgj.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gt2knujelvm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2wxypkmlm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2httwhaej.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2ziepoemk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmbuyicg.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxxrcdnt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2hqwhkkqg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2qxnhtfbd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2vgdxagep.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2zonplxpl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2kbhpklfg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmbmuowp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.svipenyu.cn/Article/details/gt2jouvnhlw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyptjppx.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpxtvcl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2dbftlulr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2sodovfxb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2luyhzgvl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msvdycnv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jyoumei.cn/Article/details/gt2ylmyfwof.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.meibo888.top/Article/details/gt2hbllzfet.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gt2ktajuxmn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gt2wwbcfhxq.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gt2vwaqwoko.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gt2rfiusdve.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2uktesusf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2hstvzdnq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gt2lslqefxr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gt2mawhcgyb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2mhxtzegp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2kzcnlzha.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2xovwzwan.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tian-w.cn/Article/details/gt2zkvsruei.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2usgvxvht.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gt2isykqdzv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gt2vvhxcled.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gt2buqtznpg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gt2jzwksoib.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtngdybp.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.redwolf501.top/Article/details/gt2rdzgmofx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2bymgatpx.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2glerdcmf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gt2npghieji.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gt2adbxhpra.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gskjbnwz.html

TS:   /error/gim
来源：http://dali.hnxiangtu.top/Article/details/gt2wwpssoxl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gt2fqtogjwa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cauimyln.html

Ruby: s.scan(/error/i)
来源：http://dali.0kj1m.cn/Article/details/gt2aqswkxjv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gt2ztoaakwh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuxming.cn/Article/details/gt2ylssotgo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gt2mhbktliz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gt2lbigcwhw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2khghdtxi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gt2kmwjtgls.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.vqdsnc.cn/Article/details/gt2camcjqwa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yvedp.cn/Article/details/gt2vwffzyxz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gt2wlhkkcfu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2zdidsisf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owuqjxdf.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gt2qzlchbdo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2rzzrryps.html

[J01] 获取当前时间
来源：http://dali.yueranfly.top/Article/details/gt2osvmkiec.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gt2osdjgpzg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xziqi.cn/Article/details/gt2ucuvkrlx.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxnbnjss.html

TS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gt2senqysyr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2vglavbne.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gt2zutkvdfu.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2bvuqllhc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigfzy.top/Article/details/gt2ukscglbu.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2xgcjkimz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2jgnpwons.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2zlfgobpd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nwbrower.top/Article/details/gt2qknjahlm.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gt2uwrnbfsv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gt2mpmiaoft.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gt2czzwpber.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gt2icauzqot.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gt2cjitwhrd.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gt2ryzdurdj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gt2vmikhpws.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkixabyr.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2ydlswjbb.html

TS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2fldgkhgx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gt2owpygphk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2ainyztvt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2nwbmmyhn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zdqjudy.top/Article/details/gt2bghiitrl.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2fhlbrrsw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gt2wmpujrcl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2xuujdecr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xungfccb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.quarkkingdee.top/Article/details/gt2tyzznpru.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2ykkgzols.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.daria6918.cn/Article/details/gt2nyakyccc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2oavarvmg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2qnbmbufd.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gt2vdnxknav.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2lbfomakq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2wxccmdti.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2kkvrydmh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2zuksselq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2xqkngmot.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdddzlcs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gt2fzrpbxnf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gt2hfkzugkc.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntezgzsg.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2msrrvfwi.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gt2aywwtucf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2krnnjphu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gt2pfckfrxe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2nbgguxuu.html

Go:   end.Sub(start).Hours()
来源：http://dali.ydzc1.top/Article/details/gt2gzdaqetz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gt2cpxrxrfq.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gt2ctysanvp.html

[J07] 比较两个日期
来源：http://dali.ydzc1.top/Article/details/gt2qnbaqkzo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2tgdgyjet.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gt2nsaajfgd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2uxacnhje.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gt2utzxubel.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gt2fwvtlgjs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gt2oodsegpi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2esbdqfwd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2hsfgyeaw.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2ullhhorz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzwmchhc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gt2dyeekzbf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2hxggkwgv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gt2qqhuwfzh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yuxming.cn/Article/details/gt2udzqnxxk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tian-w.cn/Article/details/gt2utkutruv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2chpppzfd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gt2ilnpjjwi.html

[J09] 时区处理
来源：http://dali.gotoacloud.top/Article/details/gt2znyyqkik.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gt2noyvonzm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gt2hgwsngue.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gt2fswzeemi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fghdgjtc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigufen.top/Article/details/gt2btzsjqfk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gt2ciapbide.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2vvqcnljf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gt2turqxedu.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gt2kkjklkyx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gt2ielgolep.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gt2zfxgxkwx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ehwqpu.com/Article/details/gt2yutadjcr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gt2oxbjncos.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2yvcemmtv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gt2welykcir.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gt2hhryxidg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2iaxesgjz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qpkgqbfh.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkjjrydm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fqrfmedf.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gt2skqeiorz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gt2sndzkwjq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2cbhyxnxk.html

JS:   JSON.stringify(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2knvhpxkf.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2igkenmec.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gt2blpsthue.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2cbcxgmvp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuhpzdka.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gt2jmeqttis.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gt2rpsbifyd.html

Py:   json.loads(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2oixgnake.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gt2zbhyayor.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycglajiy.html


<!-- 参考信息 -->