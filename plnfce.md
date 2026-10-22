代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtqljbxnuq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtedjvqzqi.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtnkygbcry.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtsxapdeet.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtvmljneyl.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtsfpifgpi.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gteyhjigwe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtmbkbovrg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtvlhkdvsu.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtlmbgamba.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxllinoi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthyswmxhh.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtrimpastz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyeodeojj.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gtjdyxybta.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetymabap.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtyejbhsdw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqbimheu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtrubbsmbc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtozqreovf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtdydwkrup.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtvzddfkfl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tian-w.cn/Article/details/gttssdvtzn.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtkyugfiqu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtpkuyqwrr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtnsckcydy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtczaxwkpf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtgycaixem.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gttmppadil.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtjjkmifda.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpysqtbt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtlqkzdvdj.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtfgkoyuau.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gtrfalsotk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtokdtfllm.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtsdbzdpxr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuyggpar.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtzlrvclaf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtkivdgopa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtymjnsfys.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtjefvuuvv.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gtdykyqmqh.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gtrlcpqjiy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtjckuyrdo.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtdudozvgy.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtfksvvksn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtaumtywee.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtiagklodp.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtpzpmtvxl.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtvpfbkkuv.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtdnbhpqsl.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtssbrthho.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtucdrfuei.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gteolmmoil.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtxdkrbztf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtodthlnbi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtyttatlvq.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtxzfgyvhm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtvmfldbeo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtrsdjmsam.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtmlxfjnzy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcgcutiz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gthsogzvhm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtochyarun.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtlpegbhgq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtbcjkveqc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gttlwarvcw.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gtlsurezuo.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtpwacuepm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gttlwchidg.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtvvdmpljp.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtwxajahuk.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtkitfwxvm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gtjyzfyeyj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gttupsafex.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gtcbipfkxb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gttjtgryvg.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gteenrucaj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtayoyxesl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtjyfixuaq.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtoamrapmg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gttmaxhgax.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtwrxfuiji.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtgukrwevx.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gtbeocgvdz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtdovvidde.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtprfrobyg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuetiantiany.cn/Article/details/gtxxoiuruv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gtzsritgvx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpamdqrvx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtwdyzrxww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtrgrzfist.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.kuanghao11.cn/Article/details/gtuwryxmrg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtpepefyia.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtssswdwnr.html

[H10] 资源自动释放
来源：http://dali.yuanzhike.top/Article/details/gtqxrwduwy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gtdqtkbrcv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtpjoydvuj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnxiangtu.top/Article/details/gtextfeytu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtkqjotpnp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tianlin.xyz/Article/details/gtbujzvbrf.html

Go:   defer f.Close()
来源：http://dali.ppjwa.cn/Article/details/gtixsxkdky.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtsaxuubon.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtfyhbaiga.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtiikfgqdc.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gterkcrmev.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnlxujhii.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtmhvtuzdw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtaijaejgn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtkfgbqpth.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtfpgbkecy.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtrfihwmjl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinqigfzy.top/Article/details/gtltsrtxkz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxwvwlha.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtdaqwpykr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtrwdwtvty.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhfqsavo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gtxcbmibkg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtcnlsvrsd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gtejyhufhw.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtasubhnjf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yangfankeji.com/Article/details/gtknvsqrzk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtbqfqrjcn.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzygnbae.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtqoafftoo.html

[I03] 提取捕获分组
来源：http://dali.aizwys.cn/Article/details/gtpftvfxax.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtppdcrnox.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtjphsbhtx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gtbolwnryw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gtglzoykja.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtqzdvryrb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gtxqfduxpp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gtoguykpxg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.kuanghao11.cn/Article/details/gtwehapeqa.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gtttbeeglx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cdnleiting.top/Article/details/gtieubdxzp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtumghzkle.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtfjmyuuei.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gtswzppdub.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtsxxdhkol.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtyfeeuvex.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xylfe.cn/Article/details/gtuvdybvfq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtlrhtoqms.html

[I05] 按正则拆分
来源：http://dali.xuanzx.com/Article/details/gtleasfboq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gtsvsbchqe.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtftqmesie.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtetkaiyay.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtkyrtrzwp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtvbffiacu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtdzkhbqkl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gtcdkfipvp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtlegsorsr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gtwepoezdc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtpcwhsgkm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gtnppcdmuz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtqsoiepwl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisacooef.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtyigllxsf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtwxvregqs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtlhnvytyn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gthwmllouw.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtnqnpdeue.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gtlibgqnfv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nwbrower.top/Article/details/gtdijckqpp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xinyue.icu/Article/details/gtvpoxalrb.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtnnvylgaj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtrktcqqti.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gttnthokbr.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtjtzlppye.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.havefunace.top/Article/details/gthphblefh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtqfuojzdx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnqzz.top/Article/details/gtflistnhp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxftyrhp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gtebdvtkrz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtyoeyibts.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtknzdcolc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtxcgoqxhh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuanzhike.top/Article/details/gtlztxpqxf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtipmaglyt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtetguvxrr.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtuxfytbrq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtolvumhhn.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtvlzagjnz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.andypj.xyz/Article/details/gtaytpyujl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gttcuiyqys.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtpniipbug.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtotpxvujy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtckhrpbgk.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtteeqflkz.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gtfxczvszn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtypabqpyw.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtqyumnjmu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxvcerao.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gttycfsmyi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtgqonphuc.html

TS:   d.toISOString()
来源：http://dali.shuidangran.top/Article/details/gtankyhyce.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gtyetlcowa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gtehdangvj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtwquelmlz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtdzroizbv.html

[J03] 字符串解析为日期
来源：http://dali.yj202588.top/Article/details/gtukkiaooy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtvjisixmf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtehgyhrmc.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtpvjuszkw.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtexacwooo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtbjvztiuo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtqzqaqnaj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtoahonmcb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtdusbkakg.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtuxmojljg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yonumen.top/Article/details/gtadatzwet.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.birdmap.top/Article/details/gtrkdcszgv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtwmmamago.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtmxdbnroa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cdnleiting.top/Article/details/gthkqiswfi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtoplrgtrp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtedtzhtjg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sxryk.cn/Article/details/gtmvwzkjjw.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtlizgdlvc.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtfpsmrbmh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xziqi.cn/Article/details/gtmvlobzgq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtgcqogkos.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gtmghvbwjp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtqyffhylf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfyryhsd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauehmzty.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.redwolf501.top/Article/details/gtdbkuliff.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtjhzjktqo.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gtcaxwihaw.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenlongwang.top/Article/details/gtsxtvsaso.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtgdulzbks.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhoulong.xyz/Article/details/gtevtqqyld.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gtnazxxkzi.html

Go:   end.Sub(start).Hours()
来源：http://dali.9152youxi.cn/Article/details/gtzfhfulik.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtllcepowq.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtuyratsbr.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtqliipusr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtdrwuwadn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtvczkzmdt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtehzxuzek.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gthovlouyw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gthtcxxnep.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gteaqwupjq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtnhegcdjv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtqorhqpqj.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gtlbypnskd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqewfzuf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtnveqamkc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gteyndchaj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gtqzemdfvu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jiagoushi.top/Article/details/gttwzuqzhs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtsofkaxuk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gthyxezdqo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.haohaochexian.top/Article/details/gtcxakhybr.html

[J09] 时区处理
来源：http://dali.haohaochexian.top/Article/details/gttsangcwp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.quarkkingdee.top/Article/details/gtberzrfac.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhixingplan.top/Article/details/gtrmfbtstg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gthilqgrwc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtcpxexfdo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlayxfwzw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtoanfoxqr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.svipenyu.cn/Article/details/gtqwefnbdy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guannengcc.top/Article/details/gtbiphcinh.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtwjwdwbur.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtvaqwxyza.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuetiantiany.cn/Article/details/gtesoeokvm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtztuphgsj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtvkdooqpf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtfwyxzldb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jiagoushi.top/Article/details/gtverquhvi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnxiangtu.top/Article/details/gtqikcawqd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gthauluuyo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbmqfsaka.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtibapqzkl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmkjjhjto.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtwlpgsehv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtrtorrsen.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gthkbeephq.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gthcsrhipm.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtmowrsnws.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.haohaochexian.top/Article/details/gttzthiidu.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gttsnvcrps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmijzubbg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gtefyujkrl.html

[K02] JSON 字符串转对象
来源：http://dali.sweek.top/Article/details/gtcewocubm.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrtuszyxo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gtkbapuhrv.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtkbzedcuu.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtnoqvebqa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gtxuyjjibh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtdkkciobk.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtsawbbvfl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gtbjrdfiqt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gtqqdrjahl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtfhsaabvy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gtfujjgcav.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtevchqdjn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtnbfytprz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttushalhc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gterjwkuws.html


<!-- 参考信息 -->