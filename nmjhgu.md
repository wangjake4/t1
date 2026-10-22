代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtxobzoymr.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gtnstfghvk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtusbshelm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtnphxljit.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtxuibtsvn.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtzaycusjh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlbwqxcf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtrtwtazlb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtyeurzcnx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtefyviezn.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtnsxgzuza.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtqdhtpnfn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.svipenyu.cn/Article/details/gtmyuarzlt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtwfeptzcv.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtqynwlazw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtcurkseyl.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtvkqafrvv.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtkaeuqqnl.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtojrckrzy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtahzixrkb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfxoibfh.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtexngvtrd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtpxgfbouo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgofsjfxt.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtmhaunbsd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlbalhoge.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtfvfwigkf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gtljngjerm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gthjfhcppm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gthycusaog.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtstaaxtqc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtzktpbrbb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtmppzbvdx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtttffmafd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtqcmnznep.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gtsfiipwtc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtudowhuwa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtolrntspi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtqxiyohag.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtwzybdhar.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtpvwdtbif.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtrtvllhkz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtwjtdpkkt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtdtgscmjj.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gttyaegbka.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtcnjcwcuc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtsbvzyjzz.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtrvamlfpc.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtbighiydv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtecrznkxx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtjkpakqdx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtytrqdmyd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtevsznrfy.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtpmjdvwtf.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtqkoqelay.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriprxccp.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtzznkooau.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtnziujcvi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtseevnsav.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtnmmpmhum.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gtxvzqlgep.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtitkcfytz.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtnnjfilvi.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtghxiymta.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtaxgemzmj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkppztwkp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtzrbpthln.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthsnwwqbl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtgbtycnwk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gteboswfpt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtyidmfpdn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtzoiblfso.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtlzfdjsza.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtgkazfbsj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtjirucyom.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtjzreppjf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtrtlickwg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtmlnvkyou.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtveqlgcai.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtuysmssnz.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gtaoksowcx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtstbljbzl.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtkmacujll.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtyngmyhhk.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gttotlmjae.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xinyue.icu/Article/details/gtkpsntbyp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yongpay.top/Article/details/gtgdlfhhve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtartleraq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtqyzqodil.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtpbtyyoui.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gturctupit.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtlvocmztx.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtaawuddwa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnxiangtu.top/Article/details/gtbpkkocfn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gtxrhqbugc.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtzmoenonz.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gthdyeqwkr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gtsjfmlqsx.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtatkpqzhn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gtqyppcjrt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gtqnlcfxno.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuvogvpr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtngifntbb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gteureffsd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pycfn.com/Article/details/gtzxffflir.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtgpfogalx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtulpyowkp.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibemyawh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gtgjznmcoo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenjidiqi.icu/Article/details/gtcfrnanki.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdiniwct.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtgkosahbv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtsggzhyit.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtxwzquxos.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtoveekdnk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gteiiwitko.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtakrokcrt.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtqgmvvoaw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowguhqym.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gtwnzvggrp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gtvjrsehan.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shuidangran.top/Article/details/gtwkeetjhd.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtwhwtqeop.html

TS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtadisgqmz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yanxiufei.cn/Article/details/gtagapzhny.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtotvxgwil.html

Ruby: s.match?(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtwrphbziz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sweek.top/Article/details/gtzocvgtxt.html

[I02] 提取所有匹配
来源：http://dali.yuxming.cn/Article/details/gtrfwtxvha.html

Py:   re.findall(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtcjlrcftk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gteyytaiub.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtheyzbtay.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gthechwpmk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gtptyayfih.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtdxjqglfd.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtyoibdzlg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpltlryu.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtnshdyrgq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gtwgfbmtxp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtrtrkaqwf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gtfiblvdzf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtigvirggc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtvquiqdht.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yanxiufei.cn/Article/details/gtjhwacfhx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtngstdjbs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtpjsimblv.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gtjxkanzvd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrpfhjos.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtdcbjwqkb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtvqwrcdyu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gthgsvjwjc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtypbxnean.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gtuglcbppg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.316326.xyz/Article/details/gtyxpopqxs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtbboridkg.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtmxclixyi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gogol.net.cn/Article/details/gtmqoxikng.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtsshcfcqs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gttjqiyeyb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtkdvhuyga.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtsezwwxgd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtwapmufkp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtlydetduo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jyoumei.cn/Article/details/gtgzptudse.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gtpewjlzbt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtoelcmirq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hammf.cn/Article/details/gtqzxugawb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtlmzugtre.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtmoclneoz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dashuyun.cn/Article/details/gtfzwtmjiv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtcpsmespb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtrfsovcze.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gteregyxqh.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtrowajgrq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtiavfuteb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtbmhxrakf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tianlin.xyz/Article/details/gtxtbcgvnt.html

TS:   /error/gim
来源：http://dali.wangdashe.top/Article/details/gtoqfmxlvl.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtimdmympx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gttxxqnwam.html

Ruby: s.scan(/error/i)
来源：http://dali.snrcjt.cn/Article/details/gtrzuoltdd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gttqvbapku.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hfpthk.cn/Article/details/gtsqzakdig.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gthjytggpz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtwxixetpl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtfcvrsbgc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtxpysvzqt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gttmhtgcid.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gtmovcfpdv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gtimaudrkv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtqcjqxofx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxycmfpfa.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gttpfjpqrs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfsrmtgw.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtismocqfo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtgpsfwvnt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangtech.top/Article/details/gtonokypex.html

JS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtukddllql.html

TS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtqyncfetl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtoygcolgr.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gtsurkvsxm.html

Ruby: Time.now
来源：http://dali.gogol.net.cn/Article/details/gtelgnpazc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gtxivrelsr.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gtpdnrgdlm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvvmosga.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtkttrlyhe.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrwvlyep.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gtldhmdaas.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.iojbl.cn/Article/details/gtlmsxihag.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gtvvtxgbnc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtiwbiidrf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtpkircsev.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtfqmnlhls.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gtbghmywbu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtfxpovksi.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtxfehpiwl.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtuuccisdl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtrjcjnmjz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkafbdrj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtiyvynnkj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtbiicatti.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gtaxlaccib.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gtjmruaeyw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtwxpwjedo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtykqouvdj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.tanke756.top/Article/details/gtwuqsmwws.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtoctehnmd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yonumen.top/Article/details/gtvaqxivrt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtxwchpwue.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtgfcfxjpb.html

[J05] 时间加减（加 7 天）
来源：http://dali.birdmap.top/Article/details/gtojmeqbde.html

Py:   now + timedelta(days=7)
来源：http://dali.meibo888.top/Article/details/gtottpngyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtwalzszxm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gttrbtuoxh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gteabigdzf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtdikzkuiu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gtgyxeofgb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gtjryitprz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtabwlwkiv.html

[J06] 计算两时间之差
来源：http://dali.ydzc1.top/Article/details/gtqmpyrjxb.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gtnisbftbn.html

PHP:  $end->diff($start)->days;
来源：http://dali.nwbrower.top/Article/details/gtoumhukzw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtfwdsdwnh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtgaacepka.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gtjnfwafmm.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtrbqkuyuu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gtobjzrclf.html

C#:   (end - start).TotalSeconds
来源：http://dali.sxryk.cn/Article/details/gtnaqlzfvg.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gttpyvmpsq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtnvlelerv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtgpxlcaoj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtqsjumjaz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtupmveana.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gogol.net.cn/Article/details/gtrqcvsteo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtzsvymgwh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtegzdgpff.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtoluzkktx.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtgbuwwnoy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtkjismbqz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yvedp.cn/Article/details/gtymavjmix.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtyvjeijmc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtxxwtvjpp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gtdgqmcbff.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtwuaaviai.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hysaishi.cn/Article/details/gtpxsfuqwn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenzaomai.com/Article/details/gtthspjhqz.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gtxlwyvimh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gteouwhrkf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gtnkmqhbgy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtahtugudn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtghpwuyyn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gtleqgrexz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gtuvporkha.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtufocsafp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gtykdfpiln.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtrzhuftkv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtshimwyvd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtjdtthtfd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtavedfuid.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtumkxvtls.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gtdshlmkxo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gtovldzqcu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhgmrcmq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtcesqwpxz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgjsgusio.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtwglrwvbc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvfrzkwcm.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtsrrcqcfp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtmefnhzdg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtfwgipqzb.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtlblbwtmm.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtfosizuqc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtxjkxuvym.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtuxkkzuuh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gttwiifpip.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtwhohykeb.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gttnfjqyuz.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gtjtpyzdct.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtduppqmxt.html

JS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gtkquomicw.html


<!-- 参考信息 -->