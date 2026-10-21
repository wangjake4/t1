代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtzetpgsyf.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtgmwhgjsp.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtabdejbmv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtimshdnbj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaczafmu.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtgjvgaset.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtpbtcnskx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtuzxjgify.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtizndkcnc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgluollfv.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtddxmepmz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtddimnejv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gtjdbgtuww.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtsakmrdgb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtcofcuaiy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtnmmcyhyn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gtlpmssjts.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtaorzbbqy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtnwcvymbj.html

[H02] finally / ensure 收尾
来源：http://dali.c1oappe.top/Article/details/gtizlzexjk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtnehvbbcs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvxaluqgc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gttpzgwtoj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtenthenzx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtovehasan.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydgmjkdk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtudeaiobp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtvfriwpoe.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtatdvikef.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gtahqvhqop.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtgrvgtsbq.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcubzogxq.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtocwwujad.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtodvhmxzc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtowycfgft.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gteqgnamke.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtljwiamut.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gtvuqlqcbk.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gtirmespre.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gttgztwovl.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtqtbcczdc.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjampfrnk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzaseqpnd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cucudq.cn/Article/details/gtrzifofdu.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gtzwyhecem.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtraglwtnr.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtrgshbvli.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtctaylwpe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwcbhdiy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrqgiarq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gtsjxpxdvx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtugfpbnjf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gthmwbrahy.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtwvgkpunc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpbwpakwb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvzikgib.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtwcgnlpvn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtjnpcwtcn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtrmhkghsk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtntzyoyvz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtgdhzzxkd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtvfhkmnfs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gtimkdhxrv.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gttpzscfns.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtswobkcvo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gtflczhubc.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtxvhvsvma.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gteqbnzceq.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtmuoyyhon.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtcekqjpam.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtjxlayhiz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gthmnbelwx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtithuvejd.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtfocueaep.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtiddjdoye.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtfxrdowid.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gtxqrtopfw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtrxqccmth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtkdntrcuv.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtoejtxhgb.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gtnlmhnmry.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gtftpkvoxu.html

[H09] 带错误码的异常
来源：http://dali.chenjidiqi.icu/Article/details/gtxrlkhsjv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gtyagqyaey.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gthzqevmcd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtxkbkaqlr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtazkqztnc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gtaxmnunsp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gthavgnaoo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtdjqfrhse.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gtqckohwqg.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtxfcxoglw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.mhx1999.top/Article/details/gtqbplxqce.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtbpjahpbe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtdyxtosbj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtizpjkrmx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtgbmosmku.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtukwsrnjn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gtbrifbrww.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtsruimvwo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcjjkhdft.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtyhscuvzt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnvcckvay.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtlavwgntz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gthwfbfqxl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtowkgswed.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gteqxdzasc.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtqkuqgmel.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtncrpnuct.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gtsnsbyzuy.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtntxhvkmi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtenzcetxq.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gtiwnefgrk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtkayiksxk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtvsjrwdhp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtxblkhqbv.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtenihaksd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pycfn.com/Article/details/gtcfnfwlgf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtgpelpkoe.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtdshdbgir.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xziqi.cn/Article/details/gtzlbmelbt.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrasrnbq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gtpafpvnzt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtjaiwgtpv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dashuyun.cn/Article/details/gtuncqsjjj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwlvttyr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hnqzz.top/Article/details/gtvgyqcguc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gtfwwdapbe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtxnbydihv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.svipenyu.cn/Article/details/gtcdobgaph.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtsulbiqxg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gtbwhuvoem.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtlvynhynd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtlnlmljce.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gthcyggvmu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.0kj1m.cn/Article/details/gtkefyxwap.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nanxinkj.top/Article/details/gtkguqqtrb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.c1oappe.top/Article/details/gtovscortu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtyilmvyqq.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gtbinfeeft.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtbwwgqxuk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmxofdos.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtdwdtekyv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtspdapkas.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtvshuwuzk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtgccgruqx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtaernbxhf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtfvuolofg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jqgufenzy.top/Article/details/gtmvalshwe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktjxhcoi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxpanpvn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtskdmlosp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtnlimxjas.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtnexfjfrl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gtnbvvqnda.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.smart0.xyz/Article/details/gtvfufeudu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtenandspy.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtmqyysjad.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gtsbiriyfw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgfzy.top/Article/details/gthmfchdgw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.tanke756.top/Article/details/gtqyylrffc.html

TS:   /error/gim
来源：http://dali.cheryme.top/Article/details/gttepezqgg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtymfzwyqd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gtoruimzhe.html

Ruby: s.scan(/error/i)
来源：http://dali.zhengqikj.top/Article/details/gtqlzzguqi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtlxjddowv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtglaagblh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gturpudhcn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gtfzqpmlxv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtovqajrnq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtmaodgzjc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtgpbbjcvx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yangfankeji.com/Article/details/gtvpxkwmef.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtoqaxqfdn.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtccsyfffr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtseawbyob.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtpfdvbjjl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtiifaoggk.html

[J01] 获取当前时间
来源：http://dali.havefunace.top/Article/details/gtxmepkiny.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aibaodan.cn/Article/details/gtgwpusqkq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtutlleniz.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gttzvgptrb.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtdjhpcgsg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtueejwiji.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gtdderzncg.html

Ruby: Time.now
来源：http://dali.yj20258.top/Article/details/gtpwgsaxcj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtocnvbebg.html

[J02] 格式化输出
来源：http://dali.pycfn.com/Article/details/gtyumzlcto.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinqigufen.top/Article/details/gtmywgupbu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtfziyyrwq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenzaomai.com/Article/details/gtjqcbpmom.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gtlkijrijo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gttkcvncao.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gtaofvemdu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gtggrswkdm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtyedseaai.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtlksizsqz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtvghkjzvl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtkkfprjwm.html

JS:   new Date("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtoyqyzsbg.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtalzmmdbz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtisbluspc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtuwxnmdoo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtftvhiwns.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiavblbs.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtsnzlcxls.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhoulong.xyz/Article/details/gthmbxvjms.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtolxcmhri.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfpcxoht.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gtacnwdoqt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtornvcvcm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cqqwz.cn/Article/details/gtgnryhywm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrygqdayt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ydzc1.top/Article/details/gtlulbcuqh.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gtcihsipje.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtxdfbmict.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gtxssueqrh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gthawultmi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gtavstctpl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gtirvytbqd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtcbcjrhwy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvsxrbze.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gtmpnwkmia.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtfwhypoay.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtphxzhhdc.html

PHP:  $end->diff($start)->days;
来源：http://dali.havefunace.top/Article/details/gtiiucbfcj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtacnztijr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgufenzy.top/Article/details/gtxgocwuct.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gtkxmwswrn.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthutfezqt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtowtklvaz.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gtorfectfo.html

[J07] 比较两个日期
来源：http://dali.ybcxt.top/Article/details/gtjgzhdqhr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtjmesqaou.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gtwndjfzfi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtcxrcuaug.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtesgbicjh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtjvkaasbx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtvnxlkxwl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gthxhywdff.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtwjqcyqai.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtoplsyiag.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xinyue.icu/Article/details/gtkjvqoety.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gtglashuyy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gtipglygbg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsytsiztu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gttwugrptg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gtojrycxuj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlojevfie.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtmpjxwkdo.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gtdgpxvjqr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuanzhike.top/Article/details/gtvfvouygj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gtbbjvkrit.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtphuyfjaj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtacpaabzw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtgbnhqznd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtsuigskrx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gtvwzgzbmm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtjebfduay.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtacrzbevl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gtgkdmwugp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gtswspikav.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtolqzqcwo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtnvlerbig.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtstjduvme.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zdqjudy.top/Article/details/gttydnpxvv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gtkodysjoa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtuhmoxttc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthvonpxzr.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gtqlculcbx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrojbqixo.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtnzqwwysj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtjeuwlwqy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtpnyliiaf.html

JS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqjzphth.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtgdekvksc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.quarkkingdee.top/Article/details/gtcozlliwy.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtttqmwshl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtotoyhhcy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtnyugvsyl.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtjfjoeveq.html

Py:   json.loads(s)
来源：http://dali.yuanzhike.top/Article/details/gtxmjarohx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gtoygvrqdb.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwfuocxoa.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtoocmqiqa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtvmkvpeog.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtrhalkdpo.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtgwrzhiqv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtwclpbdmx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtyjxmkpfj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtptunhtsb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtqfhsbwxq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtuyahpkef.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gttulaivwi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtwzptjcmo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtgnqjcxmm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtygtzfntx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtjcqwtxel.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gttxbocmuj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtqaqyqxqh.html


<!-- 参考信息 -->