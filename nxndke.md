代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtpgirheev.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrrbrcqpm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvwnulxp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtqxipodmo.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtdbtvewre.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtgvckxspw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigfjcugk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtvqqcnmrh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtehradbyw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtoqplocal.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtqnsvrghd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtpxbysmld.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtqvyxcwec.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtemwkfala.html

[G16] 对象转数组 / 字典
来源：http://dali.wangshuangyany.cn/Article/details/gtznasnywp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gtfdzuzgnb.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtbqaoftwf.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gthnlcuuml.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtjbikvghq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtkfbbfrtp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtutdnkopj.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gtloalldua.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gttsdgeodn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtlcywivlc.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtfzmxiftb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmsbdjgim.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtkghjnldx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtdgqfalta.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.iojbl.cn/Article/details/gtudzugqai.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtrtefijvw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtaxxkmhlv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gtqfqvudvh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gthmbyfugp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtsykmmpfq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuanzx.com/Article/details/gtnpyimgfi.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtxfjrkpiu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gtgbqtqdsq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtnmtibntd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtnpvjshji.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtwyohmcno.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtqprnhxtu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtmhpqivop.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gteqifosks.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gttkzibzwg.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtjfarnvgz.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtetckzeew.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtirdbiyhc.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtztaotvys.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtdfpsvdyd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtirxvksos.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtmizcbycn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtoxgxdwth.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtnaggmriq.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtckpqyrfy.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtlbonqenu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtxkcpwurd.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtnycerkok.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtvbsfkjqw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtkrufivcc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gtmswybytr.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtxusqfxcy.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtqbfnnabo.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gthfttnrhz.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtofjggfji.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtvcnkrsta.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtqafpxrvl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtqsccipxq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtixpijrwf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtnuhznhgn.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtimcxpwxv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvpklpjza.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtrgcrstsk.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtlojcowvu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtpicvvkus.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtxauxfqzl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtyhmpdcfd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtstqceaqg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gttbeffuko.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj202588.top/Article/details/gtwyyfzcfr.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtynqgcpen.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtvlqiolvm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtndknwoqq.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtmmwpzpfj.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtmbufwfwj.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtkgknineo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gthqygtqfn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtyvdxsrsy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.fengsongda.top/Article/details/gtnltdemaw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gthedbqaru.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtwvwuiplz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gthtvtjqgi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zycfv.cn/Article/details/gtmgmztzrk.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtickwnjpg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gtvnncxjcf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gtzfgvruvt.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtkshuymiv.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gtjyjmnpzk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gttlgzovnb.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtmlrgcnuq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtfxoizmad.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gtwhpgmipc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gtuigksais.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.guannengcc.top/Article/details/gtvjvoqbxp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtquopomty.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtkgsviasu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtgmmlktho.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtcyuswzkb.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gtkiyblcfv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtebisrgib.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gtkphhfuvl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtrrcgktea.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtihmmkkuz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gtnjacszzc.html

Go:   defer f.Close()
来源：http://dali.yuxming.cn/Article/details/gthwphzuxm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtoywjluro.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gttpnpxtjm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdspjuotf.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtigthznly.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtastfkdcj.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtxhfaqhkg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtoqrjmkbn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtllhfdbnk.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gttpnumlpu.html

TS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gtrebvhcyj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gtqyjftlxu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtlsdcjplt.html

Ruby: s.match?(/\d+/)
来源：http://dali.cashguo.top/Article/details/gtchecoptx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtlqipeoef.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gtwfngdrxr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtgtoyhzea.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gtpaldahkm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gtrhhsfdur.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtkxmxzlhd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtldvvhozu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlookxovs.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtkigsmwyr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtcxsifhql.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gtzphbnwcf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtfeztughs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtrdwrohtl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqhikejo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwuknret.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhongyouzk.top/Article/details/gthjglnztk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gtjrhxolto.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtzqhtqgud.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtqvxpwnkp.html

[I04] 正则替换
来源：http://dali.aibaodan.cn/Article/details/gtxxizvjau.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gtpqihvuai.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtfnshzyug.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtxczzjqoy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtymcaundj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtdciotlyy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtrblfczgz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.meibo888.top/Article/details/gtbciclsic.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtssagokwr.html

[I05] 按正则拆分
来源：http://dali.yangfankeji.com/Article/details/gthgzcdwxq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.fengsongda.top/Article/details/gtxyrnbcnv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gtfwmblond.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpzbofqi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gtzrnpezsv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gtijfcgpdk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gthxxnuntq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gthwntvlco.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtjtclkeyw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtvcvgovly.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtrovuajsc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gtfmezoteb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtpfogdyif.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gttzofxuya.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtmzttiekl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gthsdjrebi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tanke756.top/Article/details/gtsozvvkyh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtnhltgvhf.html

[I07] 忽略大小写与多行模式
来源：http://dali.9152youxi.cn/Article/details/gtmtyeqzul.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gtrosylifp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtxcbjoulc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtbhmicfin.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtwcnqgxzc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtedjsvvwa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenzaomai.com/Article/details/gtobcjprmr.html

Ruby: s.scan(/error/i)
来源：http://dali.c1oappe.top/Article/details/gtxssaxewb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.pycfn.com/Article/details/gttxmwreyn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtdnimdfjf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhoulong.xyz/Article/details/gteebmmgmd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtpqhnbuyv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtwoiueyvl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtbhntpcoo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtjnhopehi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gttgmxjsqf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtruassxxv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtaxjynhwk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvzqekzai.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtefepkcvh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtugrkbzxt.html

[J01] 获取当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtqqtguzlo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtyncrfnik.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbbyogbj.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtfggeqpnp.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gteeyuvemf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gttxxpimju.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtrrnzqrnm.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtcpnjybgq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtritcldfo.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtgbllrgpl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtbboswrmp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtwywmdcfx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtiesqauod.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtfollylpn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gtttreqzmu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenlongwang.top/Article/details/gthubzzcxc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtcxgvdejr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gtldikzego.html

[J03] 字符串解析为日期
来源：http://dali.svipenyu.cn/Article/details/gtnnjpulej.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtplspfpwd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgfzy.top/Article/details/gtusdxzwvw.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtyoowqxcq.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtuiwziwwe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtnyjmeked.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtcicjrfqy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtmxexzaal.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gtmsuureyi.html

[J04] 时间戳与日期互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhipjbyd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtywmldeye.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gtpzeaqfpw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxinkj.top/Article/details/gtyarhtfcn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gtxqhhljwu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gtzoixoqbt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtjkdvmujl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nwbrower.top/Article/details/gtcamtrmlv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtlybnthhs.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtzikgtazc.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtfboqklai.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrazbjtoc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtklzumrst.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtftsnjgea.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtzehesbxp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gtbmxvahjp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinqigufen.top/Article/details/gtyjhspmob.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gtoclirvsu.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtynagyolw.html

Py:   (end - start).total_seconds()
来源：http://dali.snrcjt.cn/Article/details/gtziirutay.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtalxopezt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gttsmmcrem.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtmygngaen.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gtrkkafwey.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtoudgtayf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtpstrfogi.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtxaxxtyop.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gtbzsenslx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gtbmommdlp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jyoumei.cn/Article/details/gtxdylglsd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtkmpfiogc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtaqdadfmn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtwpwbtdlk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gtryewtblz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtyoyuetxn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtjukgzkng.html

[J08] 提取年月日与星期
来源：http://dali.sufxvd.cn/Article/details/gterfbqjad.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtjkswuirt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtlknqmjgb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtrjspykgd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtcdlxouwg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gtwcinvdkp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gthchhpsor.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sweek.top/Article/details/gtinyacimh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtltgoqetl.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gtucrtphqt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gteebfqtqu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gtevqihjxd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtgieherjq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtsgkgafyf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gtdmcmfmig.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtmupteswp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtxverpuuj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtdxubluvu.html

[J10] 取今天 / 本月第一天
来源：http://dali.shzxlz.cn/Article/details/gthzlorubi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtlqbwkapl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gtfuwvothl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtkeeabbnv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtimorggqh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hfpthk.cn/Article/details/gtnmkvqbmk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtssylslyu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtvvetpxbd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtuxktpujy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmmcqbzxr.html

K. JSON 与序列化
来源：http://dali.zdqjudy.top/Article/details/gtdozunejn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtafgbivot.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcptmshtg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtqohwefot.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtccbjedih.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtnkxjsrzo.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtuprhulfv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gtmlddexpz.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gtzzznrrva.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtvazfvrmm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtqrvkwasd.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gtxwcfihzg.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gtiydhijom.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtnpfobzsv.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtpfgoyaim.html


<!-- 参考信息 -->