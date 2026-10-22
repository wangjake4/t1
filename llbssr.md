代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtnnpxnvsj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtzxubwuul.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtlemwjknm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtqjseqjcn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtfzzthxis.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtxrabybcy.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtvblotxis.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gtfastvsbo.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gtafdexjya.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtgenhdflb.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtajsmlhey.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gttesiqhlj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtpbracpkr.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gthuqqjbwf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gttixlkcla.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmfiaotpx.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtrjxyuibx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtanyogxeo.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvwjqprp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gticckuuqh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcszslfib.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtjxowotvi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtdpybtnzc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtkqixrhvs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwijtnhi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnxiangtu.top/Article/details/gtwcwprqnn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtpcxijwpi.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtqsltpfqo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtqcnlrsfh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnfwqxgd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtmpacbxwx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtfxgjurfe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gthzftvnmu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtmaypvfub.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtqlvvteux.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtwgtvsfbi.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gttbvctjsb.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtyxlgpshn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtpvkiobnw.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtgledmvqr.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtvgeiymqq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtfajamnds.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtltjndbhy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtolxulkpm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtdjepdyfn.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gtpiqizkpj.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gtqgrbqnad.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtszlfxmmz.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtloehazuc.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtbwquvghi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtipdcwyke.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktuymaav.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtdhfiwmgv.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtuybmlpng.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfqwnlhs.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtqzfkncch.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtrjpbwxrt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtklztbilg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtssqidxud.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtgbttfcpo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtnapywvdo.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gtxtpebwxk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfiinezwc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtdhtlmykt.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gtswphycqo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtvjdthgvb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtpmvaqjtz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtgoqnvqka.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtihvahhqx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gtayhwdeyh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtzpcxnstn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtqlrhhwlu.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtpoeamhzg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtbldjshah.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtvsdybjqw.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtollixquu.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtujonvvjr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gtacdsnagp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtzsepgtis.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gtvyhklmry.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbmibryl.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gtknetewoa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtnbjzetca.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtnmwumpgb.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtrwvtwsgg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtttvddugc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtjjuczqnw.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gtgwyldncq.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtvpyjjein.html

C#:   e.Message;  e.StackTrace
来源：http://dali.kuanghao11.cn/Article/details/gthkptapiu.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtgnqgucxr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gttavwqeaw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gteiiwwezv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cashguo.top/Article/details/gtgnemmkvg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtzrbizrti.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfcpkwgc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtnjjnplse.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gthaptsnks.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gtnciqrtah.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gtscmcjbmf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtmzxtpavs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtjzxfskjr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtarxqaimv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtiqjazefw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtcerpwuee.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtqtnpogeh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gttkyngblf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtkfxjyfdt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtldsxvcjw.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gtudlommuu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtoqrlocym.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gthrzmnepx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtlicrczmg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gtceazzybh.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshfviwql.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgvobuckh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtolmjkaep.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxctcqves.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqichqajq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtxilbzohm.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtrrxyckdn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtnimckwpp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gtmitspmbr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtaqqzxjag.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gtsckipzmt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtberdoomc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtdznjuvnv.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gteomqcbnn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtgywdirya.html

[I03] 提取捕获分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucgzgezj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gttqlhbhzp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtyrsjiljz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gtxfuiajud.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenlongwang.top/Article/details/gtnoppelsx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gtshwsxnqi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtkqdmtopi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gtjlcknrfd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gtgwtnmuky.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtqlgeprce.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtpspkmjwa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtvwluqsve.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtzbqtnepi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gteeddiptq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtlosjmalg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gogol.net.cn/Article/details/gtcafznyam.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gtujfplxyo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtsktauzum.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gtqobgkitv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gtoouhabtb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtdlbcbven.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnxiangtu.top/Article/details/gtkvcfgfga.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtponmivsf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gtezxhpqiw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.smart0.xyz/Article/details/gtvqczdbtk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtazodfsjo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtdpheevog.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gtpveepfoo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtrvresnkt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gttziltvqn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtetlobeuc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxofaxzp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtesieuxwn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtxfexlnww.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtqowtljwk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtxpmcpxxn.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gtjmkmktlu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.ybcxt.top/Article/details/gtouebdkay.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtnillaril.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guowangkeji.top/Article/details/gtqfqredpw.html

TS:   /error/gim
来源：http://dali.jyoumei.cn/Article/details/gtbmdaaybg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ydzc1.top/Article/details/gtyqnwvtyb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cheryme.top/Article/details/gtwggxzuno.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtuskpbxmc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aizwys.cn/Article/details/gtaazxlezp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtmvonencz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.316326.xyz/Article/details/gtjdgzwgmd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtvbdggeof.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtszbvzdvw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtyynwkvve.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtfnivomzm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcqvvasf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvgorcls.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtzfccyrlk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjmdozpkn.html

J. 日期与时间
来源：http://dali.svipenyu.cn/Article/details/gtklupcvnb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzjwkgqw.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtzwqddtyh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnqzz.top/Article/details/gtzjcqynnh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtisskunkv.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtjafhsavx.html

TS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtclwucctb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gtszxfvjem.html

Go:   time.Now()
来源：http://dali.yuanzhike.top/Article/details/gtxktmdjec.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtiqwxdmwp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkbrbfig.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtsrvaacfo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtzdltsjir.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtwaryvrka.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.aibaodan.cn/Article/details/gtlkkxoema.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtcyiyfcow.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gtzitvtqdq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtiyillpvm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtsvnnmmat.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpazndnlf.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gtqrkvjscs.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtrrzjfapk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtbyunhawt.html

JS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gttieqoqdo.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtdcqgospe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtxzowlgdm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthomlbflz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtuwxeywxq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtlnzqlhko.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtsesxbljw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daxiang520.top/Article/details/gtqanuuuzn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenlongwang.top/Article/details/gttqbnoxus.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtghbyscch.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzdypqqs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtzkkhlfrc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzgijbpu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtcvcymmeo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gttllxrtgx.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtxdaihcva.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gtpbmblqba.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtzxkyemmv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtxnnuqedv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtxrjjochw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtsetssurn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhengqikj.top/Article/details/gtitinuinn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gtdamtrroq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtkckakiwz.html

[J06] 计算两时间之差
来源：http://dali.aizwys.cn/Article/details/gtnmgipbpl.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyevxbxo.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtfbygqeyx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gtaclzrexx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtcejimqhj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.aizwys.cn/Article/details/gtdtifidbz.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigfzy.top/Article/details/gtrmmjxwvx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gtcrnurusg.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtpsmyzabz.html

[J07] 比较两个日期
来源：http://dali.quarkkingdee.top/Article/details/gtpufurmnq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtdmcdkmxi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtpcmwhsvb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaohlohi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtnqkcfjap.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuolfbwl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtmjryswcd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gtyloaafrb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtezygahet.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtbneywieq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtbdgevsaz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gtrwgmocpw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtxnqkuvej.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gtewpshquf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgufenzy.top/Article/details/gtghrtdefl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zycfv.cn/Article/details/gtufpyiabo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtnrfunsnz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtzablivqf.html

[J09] 时区处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbcfzhen.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtomebffvi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.vqdsnc.cn/Article/details/gtmgxlcufm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtbskzjmrg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtdahbvkok.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dashuyun.cn/Article/details/gtocfyamhn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gtagrnmcfu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shzxlz.cn/Article/details/gtdmgmdeyr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtlfrlhhwu.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtyiidhzil.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtbgomsvzb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gterczitjb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtncdlrgeo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gtdjvslklp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenzaomai.com/Article/details/gttamsdysx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gtcjmodrjo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtzdolcmdn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtoozzxapi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdefkgddb.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtlcszyhwv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcbegwvog.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gtjpapukgy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtepymjgel.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpioinjy.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtpmyatrnr.html

TS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtncvqojzt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtbqgprysg.html

Go:   json.Marshal(obj)
来源：http://dali.fzhhl.top/Article/details/gtdadxblzo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gtlfsofkey.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xylfe.cn/Article/details/gtnigphwly.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtunworyyq.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gtlktjzxmp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtljougqyb.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtvjjjrcdh.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtbooynktt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtulymjppt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtygkgjieu.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtvtnhfycd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gttbpscrww.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxjcypvm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gthbzqftpc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtqgcicpcs.html


<!-- 参考信息 -->