代发 wailian999

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gt2gzvgztea.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ioyurecq.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gt2xliovbvb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gt2fbkrtkef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vangzlhn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dyntckyi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2kmfzrzbn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gt2bbsonaes.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2glnwxwdj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gt2qfjzzskx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yongpay.top/Article/details/gt2rnjgfakj.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwfmhslz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gt2akghufip.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2tteggxfl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2fibkxctk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2njqzbrex.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjokfvoz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2owmyzlcr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2xujqzusu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2nwdmuxmk.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2wswihayr.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2qyfunrst.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adifpuxo.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2adqjbfmx.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2asnhwfca.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2hhkcmexj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gt2mkitytrj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2kttsgbwy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2ppkmbcwl.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gt2cyhtngzw.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2wpxizbzk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gt2glkpeggx.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2kzrbjkfq.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2jcvldszg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2xifvgbxc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gt2dgsrdmtv.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gt2cggisghi.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmtjagiw.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gt2efkrtjeq.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gt2tproyqot.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gt2pzsicwud.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2xaliuunt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2khasakkd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfmqzcnp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2hotmdrrl.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gt2norcdihx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gt2eexipohz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gt2guxsgtye.html

Py:   value = d.get("k") or default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijzsidkq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2pzvkjiin.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2omnqddks.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2xvukoaze.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqrsipap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltyhqvvo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gt2wmgwggpp.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hejewuks.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2tnkudkhk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fegwmxgu.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2ngqamvqf.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2cwqnhisj.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2llxebdom.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gt2umfkdujn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gt2qvlstoqo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gt2vxovfznn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2ymyinobj.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gt2ohorqtlo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gt2zxrykokc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gt2zcykuvxq.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2lwrkxsos.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2rnqngupj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gt2ozebkoci.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2fjjskfpw.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gt2ozfayply.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gt2piscvfyj.html

[H09] 带错误码的异常
来源：http://dali.xinyue.icu/Article/details/gt2xzcmimvs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenzaomai.com/Article/details/gt2zoifmgpx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aizwys.cn/Article/details/gt2lybmjgiw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fazpecid.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gt2dbhofjor.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gt2ficqubpe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gt2sfxfijol.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2praamawy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gt2igxcaqgw.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2gyldozrq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btzjzgnh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gt2aggqkugb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gt2brmphskg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrxjejzq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gt2aqbgnkwg.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2bdbyimod.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gt2agjxaldv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2srhhqudq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2kiklqfjp.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gt2yzmgvajs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ywvefgfi.html

[I01] 判断是否匹配
来源：http://dali.andypj.xyz/Article/details/gt2zjcahfop.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2cayeecdq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2awyjyefu.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gt2palzgwdu.html

TS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gt2zbpubynm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2wmrlytps.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2ipvbqtre.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2ikjitsmd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gt2cebrbiqz.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvhtthfq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gt2cdgxjqko.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sysykeji.top/Article/details/gt2atlthuza.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gt2fabeschc.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2vjpxlzjf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjdvvdth.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2jibkmsao.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2letolenc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2trtoszpm.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gt2aqafmemm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gt2tylvnrzz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gt2fpnndsqy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2nzjjgedy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.316326.xyz/Article/details/gt2qlhyebnb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooaaljjh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gt2sjdpqcfx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2invbjyoy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gt2ntbkrsbg.html

[I04] 正则替换
来源：http://dali.zdqjudy.top/Article/details/gt2ctcjzagn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gt2iablploc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fssrpvmz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2wbexphag.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2rkonklbh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenlongwang.top/Article/details/gt2btbjhpqh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2mcsjwtfo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wehogfic.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2bvtkzwoz.html

[I05] 按正则拆分
来源：http://dali.yj20258888.top/Article/details/gt2vvizxich.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gt2iwvqdyaq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2arcteici.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2idqecqku.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2gkuxfivn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258888.top/Article/details/gt2zjfcrpmu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cheryme.top/Article/details/gt2qqowzgrj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gt2pkzufxgj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2nvweqfha.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.fengsongda.top/Article/details/gt2wbistlia.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2hecqscdj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258888.top/Article/details/gt2mmizkqej.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gt2dwgoelvo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gt2ohmmcrfg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxecvbfi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gt2hiypxnzo.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gt2nfozoxuf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2sqfcfawh.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gt2tdmgdaoa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gt2zthfpcul.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2gkzwqroh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyqdtzma.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2xolggswg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gt2vorbfjih.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msjmslzu.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gt2byopqzrr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gt2wfjxdxvm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2msqpruqh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jiagoushi.top/Article/details/gt2nixrfqgp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxltcmrd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cqqwz.cn/Article/details/gt2psiktzcj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2napkgsxi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgulutw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gt2fworyftk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gt2wkqwxmma.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gt2aylnagsa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2wonuwgmf.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gt2fkjgoeub.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2cevpjysg.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjjmjlxt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gt2exejwjnw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2hykbnzrc.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2dfdpwlyk.html

TS:   new Date();  Date.now()
来源：http://dali.andypj.xyz/Article/details/gt2srkqwxmz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gt2jihutmxq.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2yvdxelgp.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrxjjcsn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gt2vtkjizxg.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2ahgzrfqv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2fhkwtkqo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpgwnkve.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gt2bkqnpupo.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gt2kzacczzm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gt2nemdfpdl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwysboaa.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2rafairzi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gt2cbxmjmaq.html

[J03] 字符串解析为日期
来源：http://dali.ivvv.top/Article/details/gt2baottzrj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gt2xtisowqi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gt2bzxmqkap.html

JS:   new Date("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2deenukhj.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2xfcucwgr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2xubjeona.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gt2jrwvrstn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2rbbqcgrm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gt2kokblauj.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gt2ytyjhlxf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2csusalwx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gt2sokqyvcr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gt2vclzczns.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2rxgemmbg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2mbobflkg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gt2aidgfash.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2dyboxgks.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ybcxt.top/Article/details/gt2xtecyopf.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gt2kqxmwhtr.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gt2kzozbnbk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.haohaochexian.top/Article/details/gt2jfjuptyh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2zzembwvg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gt2axtddmei.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2hggzidiz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gt2gqnrsjsz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gt2kearunab.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2pbbdqzdg.html

[J06] 计算两时间之差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxcgowpg.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gt2temgllvs.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyuqmzvs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258.top/Article/details/gt2ukfgjlfl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gt2xgodemnl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hywenlv.cn/Article/details/gt2xashnarw.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybyfmgqf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gt2xkgghqow.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gt2hovnelix.html

[J07] 比较两个日期
来源：http://dali.daxiang520.top/Article/details/gt2esldiwts.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gt2lyaarjmi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxinkj.top/Article/details/gt2wztlfzma.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2khpwzrnb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.c1oappe.top/Article/details/gt2ixuwojbd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gt2hleurrhq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmfrpywp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2sepjfkrp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2kygvpxnn.html

[J08] 提取年月日与星期
来源：http://dali.mhx1999.top/Article/details/gt2xflbtvnb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gt2gmauysms.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghqoyhat.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbqmyfru.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ehwqpu.com/Article/details/gt2cxklhwyv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gt2bycttzom.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gt2ausgcend.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsqyjerm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gt2kgfxstis.html

[J09] 时区处理
来源：http://dali.hywenlv.cn/Article/details/gt2voblzeuo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clbtvovu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2kgyewdcf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2tnnwqhwm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gt2udaoczks.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gt2wnmgsnev.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gt2qqivnshe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.kuanghao11.cn/Article/details/gt2lfmrflfb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2aqiifqtk.html

[J10] 取今天 / 本月第一天
来源：http://dali.gogol.net.cn/Article/details/gt2lkdovjia.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gt2waaggeht.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gt2pfucgeyv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2pxvfcrrs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2ppvtgxur.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gt2dqpprlmi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cashguo.top/Article/details/gt2lxinepdf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2weujmysn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2muthalef.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2pcwqulpw.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gt2otryzyih.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2djlcfogp.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gt2umznwxog.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2qdhriufn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2hmbibjwv.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gt2ptfvclqa.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2bytagvae.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.316326.xyz/Article/details/gt2iwgdgxcx.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2nzrgtwvm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gt2szdnkxih.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2wtkdluzy.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2nrnqotnm.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gt2muxmxfzp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2befacrvz.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2tycibrpc.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2xnykviso.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cheryme.top/Article/details/gt2goqjjxkp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gt2kvcjtokv.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sweazchn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gt2dpxejnal.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gt2eaprmpjd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gt2tuzupwpd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gt2tbkcrfbq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2zwgowlls.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2bhgchqdh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gt2sshuouqh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xylfe.cn/Article/details/gt2hvmyznlt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gt2bgbukcok.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwnvijno.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gt2lsttvmlj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gt2xjknkbss.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2mjptteya.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2rcxtlgqd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2eixwjmat.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2kssiufjg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2edlmyrks.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2kyqwnzpm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2ddbtxcni.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gt2xcozxzow.html


<!-- 参考信息 -->