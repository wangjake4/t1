代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtqotkzxue.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtrvbmhaul.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtulxrhrsr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtglnxpniz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtskcgeyts.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtuqraxqct.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtgrnrqled.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtnengrkzw.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gtztkgebcg.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtbfnvakgw.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtdrajcqnd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtvfvckocj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtyyawgnpu.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtvkvbchcq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtlhljjdyi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowmakqxj.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtxqhmwtcq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqhyxhqzd.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtvrznhyra.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gtiemxrseh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gttuggfyuw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtnkbgyilw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtqggwtpbo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtifkgyeyn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gtjcfmwjvn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gthfzvufbo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gthnoqqtzo.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtefjqckdq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtfzdsxjmr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtrcroenoy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtamwgyysf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtgarpxant.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtirrdnogm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gthudllgtx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtjimqidet.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtwudrtcxt.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcozpapof.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtpmkerngv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtaeududyh.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtutzxnaax.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gttcxmxblk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzequfuvb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtnoapibif.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtoumvsiuz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtisjidntm.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtbakmtzfu.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gtqizuymue.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtdwtrkgxq.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtregonhzm.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttalrebwo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtrcvvveeg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gtdppdvjkj.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtrslhsnwu.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtdtovvnoe.html

[H05] 捕获特定类型
来源：http://dali.cdnleiting.top/Article/details/gtcqtvhsue.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtvmcalaqt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtlznpomgr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtcsumstct.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtpokvshqv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtvnzlzjur.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gtvokvtjpe.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtjhndwoda.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hysaishi.cn/Article/details/gtfqdsupje.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhongyouzk.top/Article/details/gtkuoqetuw.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtfebbyzsq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtrdwyxdyj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtimwkqvew.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtkjkxjdzc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gtszmfsfta.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtknbxlcjb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gtvvjnbspp.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtxytlozwf.html

[H07] 断言
来源：http://dali.redwolf501.top/Article/details/gtpdeujnjm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gtqjpsowut.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtxxyhgcnb.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtatrimsgr.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtypuoebdi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gtaxbcojas.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtzrfarlfq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gttllwkrhk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtendaepvd.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtbnydrzez.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenjidiqi.icu/Article/details/gtukdwyuuf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtbtuowxnk.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtfolhunas.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gtqfgiwvcu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sysykeji.top/Article/details/gtlhraodov.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtjpjdkjqr.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtizctfqtm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gtttccpfps.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtqpokbzge.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxinkj.top/Article/details/gtmlcigpkf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdwqwqbu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gtjdfwxenn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtyocthdwb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gtxizferva.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gtzdfbtpej.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtluhxmyop.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtisxnzdaz.html

[H10] 资源自动释放
来源：http://dali.c1oappe.top/Article/details/gtyvubgzro.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtkaobighu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekqjwojp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtngegkjwh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtuisyoiex.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aizwys.cn/Article/details/gtfpcvqumb.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gtbxyspjxm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtloconwmr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtrtppewsg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtojofqmdf.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtqrckocfn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbzvfbevy.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtstrlbaqv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtjvjvluap.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtshcocatv.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtamdnelcp.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzatempwe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtrvwsbttm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtlhbhpyau.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtgiffpgzw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtxjocqphb.html

[I02] 提取所有匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsvlwfzb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtsjvzdspc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gtifkiczme.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgufenzy.top/Article/details/gthpcqwwav.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfmfzkwj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gtosmmnjem.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpyyfjpl.html

Ruby: s.scan(/\d+/)
来源：http://dali.gzhubu.top/Article/details/gtkjzxwaho.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtcjtspraw.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtrpgmjgtj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gtcbcdflig.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gtparchawv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawivcley.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtnericzqq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtrffdhzag.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.quarkkingdee.top/Article/details/gtibyqbgwm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtwxskppdu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.0kj1m.cn/Article/details/gtbrcrtqvk.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtazmughfp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlbgqtjxr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtjcucbyfh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtbegwibyn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtbmsrfwnc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gtawuvqcpc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtpcntrcte.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtvlrjxflf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipkbnish.html

[I05] 按正则拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtlkwsmlpm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtygqvynaj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtregaiikd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtnkxuaxna.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gtcueocfzg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhoulong.xyz/Article/details/gttbfgsdws.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtcjjodhtp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gtnzotsnzq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gtldkfshhg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gtoqgikmfn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhoulong.xyz/Article/details/gthcqotazg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtsoqsljcn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyvecjjp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbkzezym.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdecdmtm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtkuuguayo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrvjzfql.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gtqoyxgmnq.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtahbabakh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gtplhbpwnz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtizujkflo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gtqcmjriaa.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gtkvanbpye.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtzeumjrww.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yonumen.top/Article/details/gtglmwbnmx.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtwenqgpjj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.dianchejie.cn/Article/details/gtqhmtelcn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jiagoushi.top/Article/details/gtjyvyhqaz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtgpmnmmaa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gtxejbwmuu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtrkdcbzqn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gtxvjisgwg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtkawcquis.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gtbfkrqnqs.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtoyzlqtcw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtsqoyohtd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtycfmvnxr.html

J. 日期与时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxysmvnr.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmqmibnkz.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtqsbauylp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shzxlz.cn/Article/details/gtmgziarfs.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gtpbnwvnri.html

JS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtlbskrukw.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gtooshezdg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigufen.top/Article/details/gtempwvwcc.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtdkexkzyy.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gtyeltsaku.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gtalajyfxs.html

[J02] 格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtpjtrblvc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtfnnygqaz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtrwhgaiyn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ydzc1.top/Article/details/gtyrhubbem.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtqsdhycrf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtfbcnkoub.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtgarphlus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtnyaciixx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zycfv.cn/Article/details/gttllixyiv.html

[J03] 字符串解析为日期
来源：http://dali.wangdashe.top/Article/details/gtgdsanxpt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtyccocemc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtyvlytqha.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gtqvdhgwzq.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtipbjvhud.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtehtyhetj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtxoyqrdrt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtybzdueoo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gtkslywvsv.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gthhmkrarj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tanke756.top/Article/details/gtvqsuhbrw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gtlvthopxv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sysykeji.top/Article/details/gtjucxnikf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqnkirml.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtpdskcbzr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtbnuoeygl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtkrndahqf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj202588.top/Article/details/gtponfgmgg.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtlbpzqgdw.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gtbtesxzil.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gtmwcdmjbu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtaycszecz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtqdhjejse.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xinyue.icu/Article/details/gtajstpryn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daria6918.cn/Article/details/gtylejbmai.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gotoacloud.top/Article/details/gtlvpvpyxm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gtvfjzxrgd.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtbrdschdg.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gtenxsygix.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtmevhusny.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtwvlopnpu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sxryk.cn/Article/details/gtbizxlvpt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtmkjywpir.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj202588.top/Article/details/gtgkyigjox.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtdnbnursy.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gtpgzfelob.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtyyqeiajk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtjiupxbib.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.smart0.xyz/Article/details/gtxwjltblp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtxrichqtt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtdwuopsex.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtxyrxwdwd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtknlryapp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtbrmhoqns.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gthjlhsllm.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gtligiqcof.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tian-w.cn/Article/details/gtquyvnbiw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gthsfstdbn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtfphqxlbb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtfdthhtuf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gtkwmkkhzp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtdrdoljdc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtaulpeukp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gtgwkyytlf.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtugngknvw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtbenqbgng.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hongshengwenyu.top/Article/details/gtxgbfobra.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtxqmqalua.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtzhjknlnu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtpjchuhpf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtwqhjhgoc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtuybiejux.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtkiixlmac.html

[J10] 取今天 / 本月第一天
来源：http://dali.ydzc1.top/Article/details/gtnaadsrln.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyxyqlnen.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtobvdicub.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gtcflsskeg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtszoyvmxy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcebeikfn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gtfmqrfvfs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gteyygpavm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtswkpillv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfukncjlf.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtjcetihxd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdtprdtsv.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtimwewiqa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtgmisrpnj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtrxnecfue.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtritwspfq.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtfugnjjzp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gtxjdfjwnh.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtufpfptbr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtlxuwmgel.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtcuqyhxlr.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gthzupocfr.html

Py:   json.loads(s)
来源：http://dali.quarkkingdee.top/Article/details/gtkipnfqbw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtgtlxfggo.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjnglalk.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtfwnuqdii.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtbkhqaggz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gtvbahkclk.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtogqdoqcq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfvzzoyy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtmdvnxzpw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtvvcbrgah.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtmytikjqv.html


<!-- 参考信息 -->