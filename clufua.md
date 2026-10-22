代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtholybftn.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtqfsfpsjq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtjrltmigy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtdfxidqbe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtvmlpiood.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gttavosgje.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyyralvo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtsuptyvyi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtgmjbgltk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtkqmbyolk.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtxmagamws.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtyxlcguco.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtnadehpxn.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtdxuvzosj.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtatqcknol.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gtmmebsoza.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtietwgbwn.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtpagxjtmb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gttclhinyv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdjzjxvst.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtrgkigacl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsjnpmvyo.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtbxvuknmj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtjoepufgp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258.top/Article/details/gtqzqotnkc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtvdfixlvp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtkjrsdqul.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtufnjdssp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gthblwbmae.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtfyvsiusf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gtrisvnfyz.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtiwhknlhw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtjwiborqe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtvnsxtjgv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqepropm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtidmzevos.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtncqiioif.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtdzfceywy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtizmmjsbm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtawvufint.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtywobzttq.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gtyognuitr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtlkqogjff.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtbcdlohpo.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtxaapwxgt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtbvbzldpm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtpghciahh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fengsongda.top/Article/details/gtryvsmkku.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtftsovhhd.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtrqogrccy.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtizmqjckd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtnusfxibq.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxggdrgyz.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtzpfgpeoz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gttyggpwla.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gteiapwcab.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtiyaadztw.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtixenmyij.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gtgycedurg.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtuqkkvmdz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gtzrkarvze.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtulrrkfec.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtynlnugjv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtpkaegpzd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtiduwximo.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnazsche.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtjbwktwvf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gtekbbpuxr.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gtvhsyzapq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gtizxydipl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gtibcapdvi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtaogngvxh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zdqjudy.top/Article/details/gtpjtoowgo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtefehjxiv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtairyruzd.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtntpmdcqd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gtitvoipae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gthpnytsrq.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmxsymkb.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtebsnirss.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtnnnatpcj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtzvxmrjuw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtmifvrvpg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gtpsayujnw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtaoryrnbp.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtumjocift.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtvgxkevjx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtiyvczunw.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtxebuqtkj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtjrbfdpau.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gtheykdmwz.html

Go:   err.Error()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxhkjedl.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtsnkjofdm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gtnebjjakj.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtcaorglmx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtdaqvsdnm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtdvohzgzn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtqcvcalyr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtiqyvnrti.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtrsvcicps.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtprbngybo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gtfiuuzero.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gtecmiipnw.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtzaezxehc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gtboortyyv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gthtuqlpwi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gteojrejqq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtsckhfece.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gtzpeodzaj.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gthucvwjri.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gtvlahnygq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tanke756.top/Article/details/gtsyzidfip.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwvpkofpx.html

I. 正则表达式
来源：http://dali.jyoumei.cn/Article/details/gtlggtpnej.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtaeyaefjw.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtduxyamhs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtzzzmgawz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlarqisk.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtmjyhyvdu.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtzmogfgcx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtgwdgrirt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtbajwjmry.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gthkztbslq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtairfbtyu.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtdixbewgp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gotoacloud.top/Article/details/gtzrrtpvpq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtdsprfdgt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtgdoutikh.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gtfcchekbh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtgfumasqw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtnvhxfyiz.html

Ruby: s.scan(/\d+/)
来源：http://dali.fengsongda.top/Article/details/gtdpoytebr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtpykjmmpm.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtdruknfkk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtwnujiymy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gttnfwasky.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gttscmqcbz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gtwlbhkrgm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtlaxbgeko.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gtihxpxotw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj202588.top/Article/details/gtzikxwfrc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtfckvywau.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gtksfrogra.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pycfn.com/Article/details/gtfnozwgsc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtjalofxdh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtypcaikyp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtqnhkxens.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtqmbpvqdy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtqmotjwjx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zycfv.cn/Article/details/gtwlkezhag.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtdwwdntfw.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtruthsbhc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtzedsgeng.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtmxuhqikq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gttygnzqcj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gthlkuuziv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenjidiqi.icu/Article/details/gtouxazjle.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gtroapaccu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.smart0.xyz/Article/details/gthirioiji.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtotodkzbs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gttrbjafih.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gtbtcolsqa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cheryme.top/Article/details/gterjzozgz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtztywogzn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtswoytirg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gteeclbduk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gtcjjrahjg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gtdcvmkunq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtpvakrsen.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gthttjhuwp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuanzx.com/Article/details/gtzecxgnrj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtcjrmuase.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gttuyhikzo.html

TS:   /error/gim
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxfskppb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hywenlv.cn/Article/details/gtpugppavo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gttjjezolm.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtevmhuodg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gtpqsbmitz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gthbfrdqcr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuetiantiany.cn/Article/details/gtmsmswyqg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtwfofoqqm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gtrworgefl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gttkbudrun.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtczuzvtvr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhiwuduotai.top/Article/details/gtwvnoqpev.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuetiantiany.cn/Article/details/gtlxnadvyj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtedqwqpij.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtovwuulci.html

J. 日期与时间
来源：http://dali.xinyue.icu/Article/details/gtwbbjyazo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnauubddf.html

[J01] 获取当前时间
来源：http://dali.vqdsnc.cn/Article/details/gteukdvtak.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtrmkzhssl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtlryuyffg.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtaizyzuzt.html

TS:   new Date();  Date.now()
来源：http://dali.ppjwa.cn/Article/details/gtdkarkash.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikmwdfcd.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gteqnonagq.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtqwkrbqfe.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tian-w.cn/Article/details/gtgrysylfy.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtmewpspdc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtbgtqpipv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtulupaypb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gthebeogeo.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtcvkmgolw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gtavcfadee.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hongshengwenyu.top/Article/details/gtnhiogqnu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtqgehxabe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtfrvqtfat.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtvkhsxxai.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtbibunzlq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gtvtueicyq.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtuowlinyb.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtaxfvnqtk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gthpztkbcp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gttaqkmfxg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtrwpzxtcv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtrmswfdde.html

[J04] 时间戳与日期互转
来源：http://dali.xinyue.icu/Article/details/gtxmytbaoj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqemzbvfv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gtmrdldahy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gthrjztkty.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gtdhryffic.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtubtmfths.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtcujhrpuo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj20258.top/Article/details/gtvxeypjju.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtmdwyqfsz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jlsjyb.cn/Article/details/gtkaakvfzn.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtiectnwsm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtumdfizmp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gtgwfrvqak.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtptwupezn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gtrglrrwmh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gthsgxcnou.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gttqraurof.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtalvrdinj.html

[J06] 计算两时间之差
来源：http://dali.chenjidiqi.icu/Article/details/gtartppyph.html

Py:   (end - start).total_seconds()
来源：http://dali.zhongyouzk.top/Article/details/gtahjpgyyb.html

PHP:  $end->diff($start)->days;
来源：http://dali.yueranfly.top/Article/details/gtequbetth.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gtcnsegweg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtdlgopmlu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtaiwcgwrb.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtndmrikmh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenlongwang.top/Article/details/gtfblpefok.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gtmgqfxofq.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtmjbrcwxn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gttyseflkr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jinqigfzy.top/Article/details/gttthxwfdf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtetijoupx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzqcnnnc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtwijapcey.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtkaamlwhv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtnpaxgvon.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtveiuzfzm.html

[J08] 提取年月日与星期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwjjhilj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gtninqjhjg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shangyingyoupin.top/Article/details/gtpnsusfnq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtacjhjgmd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gtxxelhxwj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtgxmxwrym.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gtexvipeyr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtkvjmpsmd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtakuuynii.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtgbajyjoz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gteybhzwcg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gtfcptwpnh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gttltullrg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtjrfsuaeo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtvactpftz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jyoumei.cn/Article/details/gtzxbhmhbg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtclpetzsr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtweblzxha.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtrjwhwlrs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtndkfgser.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtfodrzszw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtvcesmudb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gtdlxjarmt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyjruizq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tian-w.cn/Article/details/gtikiiqyzx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtzozkkyul.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gaohongyu789.top/Article/details/gtenjhtanf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtaslrjkzu.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gtskvavsgg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzrwopjef.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gtxwsqgqhy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtjnmiuwjf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtmtmpozlr.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtvxcdckob.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtojbuqidl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcooswsi.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtukdcefff.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gtlgrfqurt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzfwkcvny.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtafcqjpqm.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtsjuvcrph.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtgycbfyvp.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtmustrtds.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtzzycovgr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gtdkyepexl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gttcusfgcd.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtcbzqmrag.html


<!-- 参考信息 -->