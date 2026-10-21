代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtxaxjeian.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtkkcovdmc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gteocuzpjc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkqwptgyc.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtrauomkhr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthxicbehf.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrojjucaz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtgqoqaeef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtnztfrmoz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtvbvtaixm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtfvnzjwaz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtzyswszqu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtmagdzkaz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmqtypnn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtjzapqlwf.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtjvkpsher.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtuibpngkv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtasushtir.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtynaptqpz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjiogulbx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtiaoberjn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pengpengdd.cyou/Article/details/gtvedgluaa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gtmlmfopul.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtrqwmynhu.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtcvoxqkyr.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtfiuwlnde.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtnimgphnn.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtewdnalfi.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gttgkmmhwm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gttdyegetd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gteawnoipt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtltwcgaqm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtowhizpdk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gtewkmobix.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtmbvsfalh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtppvmqwko.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtcfyvbsha.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtdfaunzip.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtizmhlrhp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtgilobbms.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtwizuemti.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtwrlhkhnh.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtdhuljjyc.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtekizzbhb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtqacfuvus.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkfnvxln.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtdsxouvxv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gtnotktqtm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gtckytgyou.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtspnpjyaz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtakbhojfi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtatokklkx.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtbryhtrnj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtpgbmnuvt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtdwsnhhno.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtlordresb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtwooklzph.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtawzyhroo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtmhpbivjz.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gtxyhpidni.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtsiqnhnja.html

Py:   assert x > 0, "必须为正"
来源：http://dali.svipenyu.cn/Article/details/gtudkzinvo.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gthdywdsmn.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtbhzmvopx.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtixnkzsni.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gtftxliwra.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenxjysct.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gttminfrtt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtlefvvtdd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhixingplan.top/Article/details/gtwzelitsj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gtzfrxqirk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtwfiuajwt.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtwpqlbnln.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gtqcwlxtah.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtbjrfblly.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gtkqaygull.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gtzqxzsfne.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtvnisulvx.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtsonnxkvq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gtbriufekb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gtjmnwghrg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gteacqwixs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtceofanin.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangdashe.top/Article/details/gtijrkimjz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gtiiayqdfg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtnequzdbu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hongshengwenyu.top/Article/details/gttywjmsep.html

[H10] 资源自动释放
来源：http://dali.tanke756.top/Article/details/gtotnlyqst.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtvuhvphgi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gtiicppglx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gthcgwpesd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtpfnvwtnz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtgextttoj.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtdtahvebd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtsfjgwtsy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtmahlrawi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqblwwuqd.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gtzkdvrfmz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwydeunjs.html

[I01] 判断是否匹配
来源：http://dali.yonumen.top/Article/details/gtceugamaa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtcbucjole.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtlmkujfke.html

JS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtoiacdtrq.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtqkfqpnlk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtrrzhfsss.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtvrtabcpv.html

Ruby: s.match?(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtapthjcnr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daria6918.cn/Article/details/gtpcktlida.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtwutlsqla.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtuafwfslv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtobdzkvqo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sufxvd.cn/Article/details/gtyfrjohdw.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gtkzsozpcd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtlhpgcltm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtwfrkilra.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gteqbqjsgz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtuiichoms.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtbujwleie.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gtvaxzkmcq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtchwcionr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gtrxuzjnfl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.smart0.xyz/Article/details/gtlzjayvnq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaywzwaf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gzhubu.top/Article/details/gtaeqsbqgd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtkfxuhmbe.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnqzz.top/Article/details/gtcfweimvt.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtfnvfmwzg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gtwjbhowjz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtxqwxnztf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtqmnxscdb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258.top/Article/details/gtrwqfccsn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtbkfilkzp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.kuanghao11.cn/Article/details/gtcntxifvm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtvuewzzqa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtitwgrrqu.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtxcvjxczt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zdqjudy.top/Article/details/gtsckbbzwf.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tanke756.top/Article/details/gtonkmxrly.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gteypyuzfm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpjbrrrx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.svipenyu.cn/Article/details/gtdmoynevv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtxmypvyka.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtyqpkhzra.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.aizwys.cn/Article/details/gtbgdzsghz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gtraaxsmoy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtufmjgrdo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gtgbmkfhyq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtdslrufxm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtiewuvvoc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtctbcjvni.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gtkplqijzi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinqigfzy.top/Article/details/gtkbrhgybw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gtmsslrubu.html

[I07] 忽略大小写与多行模式
来源：http://dali.smart0.xyz/Article/details/gtfhqhkkkn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtbukobbwb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gtuyfivwxc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gtpizdzgqi.html

TS:   /error/gim
来源：http://dali.316326.xyz/Article/details/gtqrtencxo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gtggmhwooc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gzhubu.top/Article/details/gtkjufiawt.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gthajlqsnv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtvjxfrtqo.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtcynqlzvh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gtlnmvvpyf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yonumen.top/Article/details/gttqpndfug.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtkiyvpzjy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtchzlufto.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtrlivynzo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jianghu66.top/Article/details/gtrcwzxwqv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xuanzx.com/Article/details/gttfcsokuv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtxcpsckyb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtozujxbdw.html

J. 日期与时间
来源：http://dali.jyoumei.cn/Article/details/gtufalcrsz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttrxijbog.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gtyswqzusi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtymvolday.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gtdlctgfhd.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtnwhjwogm.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtvdtkduzc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gtsgdzyjuc.html

Go:   time.Now()
来源：http://dali.nanxinkj.top/Article/details/gtrmdduhen.html

Ruby: Time.now
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuskzxtot.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gteixuaopm.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtgeftsqgg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtzpwqhkia.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gtictqbkiv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinqigufen.top/Article/details/gtxfabecmr.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gthjapjxfk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jiagoushi.top/Article/details/gtsqfmlyxv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtrhbqfvfd.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtmaydebhv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ehwqpu.com/Article/details/gtxysgxpzr.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gttmvlfbky.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gtqzlwarie.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtdjisdlhf.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtghljkadc.html

TS:   new Date("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtsrivntip.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtygjctcqw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gtrphubnhk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtxhldnogw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tianlin.xyz/Article/details/gtowaszlff.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gtqneuzsnh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sysykeji.top/Article/details/gtaeuggirl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtiryldpsr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xylfe.cn/Article/details/gthsubewdm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.iojbl.cn/Article/details/gtsdynmyns.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gteaemcgco.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gtyonpqapf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cdnleiting.top/Article/details/gtftntdrbg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtujcnlmdb.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtwzcjuuxd.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtjxvsvizb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtgompjfxh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gthfuihafj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcemyjodb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtnnepeebx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.quarkkingdee.top/Article/details/gtuaftvnpf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gtkxounlgo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gtllfjkdjn.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gtoukoeklb.html

Py:   (end - start).total_seconds()
来源：http://dali.yongpay.top/Article/details/gtnopxkmzq.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtpmwxjkye.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtkomajxjv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gtrlvyixry.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtbwokcmmy.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gtoenwugpa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtbqmzpafu.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbclpzibl.html

[J07] 比较两个日期
来源：http://dali.tanke756.top/Article/details/gtiyiqopoa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gttseuvple.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj202588.top/Article/details/gtojyctyzg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtnkmuswbq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtokijvzly.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nwbrower.top/Article/details/gtbshbkkbl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtprdzwbnf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtvmsbrafs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtyuqldfjc.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gtvawqvzsm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daxiang520.top/Article/details/gtidktfagt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gttzncsfsl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtsmohpgct.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtwmfxelkv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtxagocgsa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gtkwppjbhi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxuanxn.top/Article/details/gtbigtyxav.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtrorgeqdd.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gtazipdjwh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtvnhteyyk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gtmfybbmgw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupuisuew.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtngxxwjkt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtqerphyhl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtrkhwdgoc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtvepnugfk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ivvv.top/Article/details/gtfhhjarmg.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxjuhand.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dianchejie.cn/Article/details/gtidrqnvqr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtcpwxoldt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtsaxpjhpy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtyaeqmext.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmdreaeve.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtyoaxbcqp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtnftgbrlz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtxvjdpxsa.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvgiqymmh.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtrzkgdzfx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlnhsqbdy.html

[K01] 对象转 JSON 字符串
来源：http://dali.haohaochexian.top/Article/details/gtwvmcuohg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gtytyktrqv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtmricwdwu.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtpfsrpomw.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtgslvazym.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtlwcuazqu.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtzqzgjyie.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtezdugymm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gtlshmshfa.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtkdsbdiwj.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdpuoavci.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtbepunoka.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtqvbhyegp.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtpptmuzet.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtirerjjun.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtpmfaywll.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtxnidfeaj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtpjqrepun.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtupivkrlw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtpmnwnnpv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtnzunmwpv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtnqopmjcs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtxvtzndxz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngwuyrif.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gtupiqecgm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gtnkaygxoo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtmfwwpmti.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gthfvuwfbl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gtnglcdhjv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtmztfespt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtasbybqpr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtetoaeala.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtihjeyxzo.html


<!-- 参考信息 -->