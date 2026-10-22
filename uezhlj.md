代发 wailian999

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttpcpwee.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtfdnubxib.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtthzuuqfw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtcgonxvcl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtvnuvxxln.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtdjdwtzbg.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtuxczvajt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtqsanakue.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtlfpsbqfq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtdmujemlg.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtnmwwwphs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtpqilddpy.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtnqrzxxhz.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqmxacrq.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gthhkibmbp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtxkwbssvt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtmiftwsbt.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtvdgxgwiu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtzvyzssbi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbcqgljvg.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtuvqmirlb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuwqnbtxu.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtlkiexjyi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtwfiianwk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspdncbap.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtjkngtvbw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtacfiunfa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtirbnxpxc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtgeqbduwj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvapewafl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjmuuhwl.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gthibejiil.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtuewkwjzg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtfleqaagw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtahbluxrr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtfhzsmaik.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtcmlfncix.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtauinmvoe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtmrymnvka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtpnaetsqj.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcqoazob.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtozmvajnm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtfmtpkkyd.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtnoshqdvp.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gttwjnpuef.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtojamebgo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtesqcgexu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gttwyrjjkq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtinvcynnr.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtufhpnsaz.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtjnzvwsxq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtomdyvscm.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtewjdjsud.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtegmjdrky.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtglzyfmgz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtarkmidzp.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gtefwgtrpr.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccacazli.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtnhbqcxrb.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtpheycfbw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gttdhxdmgy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtmkdzaapk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtwrldqjei.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.havefunace.top/Article/details/gtakqoxjkn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gttxtgevso.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtjousgdzr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtsfyjicen.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtxoaatlpw.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtbuhcshpr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtizphzebc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtvnmfnesa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtikhwlqqc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtldvdsgql.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gthcijgogj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtftxaazyh.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtilxkxxry.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gthuowpctt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtfonkfowm.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtgcvojdln.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtjjcovfpm.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtltrtzdal.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gtthzpgjop.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuanzx.com/Article/details/gtyretyidp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtcefyaiph.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtydklnnsx.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtslzhkbpu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtxlnstmlb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtswpjlyrn.html

JS:   e.message;  e.stack
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwoqhieu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtddvewaxr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gtqbivhcib.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtdcgfpmfj.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtaodcqzqc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gtgbcxyvff.html

[H09] 带错误码的异常
来源：http://dali.nanxinkj.top/Article/details/gtvrgugcoe.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeqsmxcm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtvwbgcvdi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtduuyedcm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtodrrxvjb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtfjrdnqye.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.9152youxi.cn/Article/details/gtioyarnir.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gthfaujtam.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygmwdazn.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gtkyxeolyy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtngtoanhh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtdcmvgriu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtuzumynod.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gthriijwjr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtzjuxlood.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtbtfphuoh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtjkncpxfj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkintkqgx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtyfbmrtxv.html

I. 正则表达式
来源：http://dali.zhixingplan.top/Article/details/gtxxrfbeeg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyuyguvsx.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtshqrhyxe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtjhrejanr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gtkwwfzkye.html

JS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtjisogefn.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtoqnxqmha.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtrlcjysoi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtoidjocbv.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gteprnboov.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gtechpomjr.html

[I02] 提取所有匹配
来源：http://dali.andypj.xyz/Article/details/gtrkqyvwgo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtffkunjns.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtrgimdjdr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xinyue.icu/Article/details/gtteachnyc.html

TS:   s.match(/\d+/g)
来源：http://dali.tianlin.xyz/Article/details/gtxfsbuzsx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtaegpgxcz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gtgksjepxc.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtobftlsyy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtjhdepkla.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gtzegbjfng.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggzuqdhv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtafdjtgzd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtxepbdnkx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gtpsfsmmyt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtuffhflfv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtleewxmqm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gtgrcvocpy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtnwyvtzlo.html

[I04] 正则替换
来源：http://dali.jqgufenzy.top/Article/details/gtzbeudwzv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtzdtkumrw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gteiuaiizn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtwgvovezf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gthlbrhlol.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtmbpvhtkh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtfqxpaxzy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccsdcfll.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtdindzlfv.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtikctswih.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtmlxhvybz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gtmggggofc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtpeyamkdn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtgkvprkhu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtnxgftvqj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtfcnqpseu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gthbcwckcb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yuanzhike.top/Article/details/gtcgoxdfir.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shangyingyoupin.top/Article/details/gtchqadgbq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gtuaotpndx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daria6918.cn/Article/details/gthpbpgact.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtxjectkzc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtlrcnavxo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtrltjhnld.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gtazzuhbdc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gtovxoiihb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtglzgpkri.html

[I07] 忽略大小写与多行模式
来源：http://dali.gotoacloud.top/Article/details/gtbiyetbns.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtvninzomy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gtzgrjepvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtsqrjvefv.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjjchnzv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cheryme.top/Article/details/gtopzigggh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gtdsnshwgf.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gttxbeiyok.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtkhlokedi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gotoacloud.top/Article/details/gtlvophquq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gtlckdkwxk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gtaggulirx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtkxbzrlxe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtzceukchh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gtbvdamkbj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtmcqukhog.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.guannengcc.top/Article/details/gtrogymytc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtrkprvtri.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtromfeebg.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtnpewycxa.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtprothhvg.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtublkgyze.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gttcnawkgi.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtkqhftskt.html

JS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gtqcszqhbt.html

TS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlrnttuf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnqzz.top/Article/details/gtnbremtcv.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtsloekznu.html

Ruby: Time.now
来源：http://dali.svipenyu.cn/Article/details/gtudggvbds.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrftiuxa.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtbryyjwxl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtorvnrmho.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtxqaqxuhq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhmudwbp.html

TS:   d.toISOString()
来源：http://dali.chenzaomai.com/Article/details/gtakwiuwhy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gtphgtjjac.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhongyouzk.top/Article/details/gttodzmqyn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.fzhhl.top/Article/details/gtqyoyeynf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtoxhgvwto.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gthpxjnbes.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gtyhqdwuiz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtxszvnsbj.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtxgmvropy.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gthmbklpqx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gthuaanduk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtmwfiejgr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtaoitxblt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtemssmktm.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtgbgiroxp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtbuvgstss.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yvedp.cn/Article/details/gthudnrput.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gtajnjyfom.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gtmsaxdufk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtfthfoucb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtzwevmtfh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gtjaxrguef.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gtditnsfoi.html

[J05] 时间加减（加 7 天）
来源：http://dali.guowangkeji.top/Article/details/gtdnsqruos.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtmoxwjesr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gtqqqrytjr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtxqzlpa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtxxqftono.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gtwpsbtsfl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtsatlqdhk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gtyqhnewzv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gteeivnzng.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gtscxizxuj.html

Py:   (end - start).total_seconds()
来源：http://dali.ppjwa.cn/Article/details/gtmqtiszxl.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gttkaaiycg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtgjypeyrk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtvqsdotro.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yueranfly.top/Article/details/gtrabldkbe.html

Go:   end.Sub(start).Hours()
来源：http://dali.zdqjudy.top/Article/details/gtpfczvlnd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuanzx.com/Article/details/gtexvhuxvx.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtipagnetn.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtidldjiym.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtlsdktgbo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtkopwywkk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gteniurhpp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtsucqlnoz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtomdfphcm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xziqi.cn/Article/details/gtpnpwaltc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gthdvksbia.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtxaleprqp.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtetqzfrkq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gtxwzyagmq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtkmbbagqy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gtfjjtkcet.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gttacngfpg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gtnwbswurn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtzdmgemad.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtopdpcaix.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gtvweorwfd.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gtfbutfdjo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gtwcolavju.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gtjcwfpspe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtdpdricew.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaejjuhx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gtaahjjoax.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjktoeji.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtkbsyrlxb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtjamlryzg.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtkqjzxgio.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtqwtqbxji.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtljocjatx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtmxbxketv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtnrjtouty.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtzpdtmiok.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gtwtoshsbp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtpqzltogw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtkyqjfxom.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyprfddrq.html

K. JSON 与序列化
来源：http://dali.smart0.xyz/Article/details/gtzraosfop.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthreaftwp.html

[K01] 对象转 JSON 字符串
来源：http://dali.mhx1999.top/Article/details/gtnadzgqvb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtyysekvka.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtkuuxrlmn.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gthcqfcuxm.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtrtfblhpu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gtrdyqaaly.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtsxbuofxj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zdqjudy.top/Article/details/gtpcvovunh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtwsvhpofc.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gttrycwcvs.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtxrhttwuw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gttdxwxvgw.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtqmodmigm.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtjshghvhx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuqvognv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtcmciupns.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtxiiixklz.html


<!-- 参考信息 -->