代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtgabduhyl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtjzvxcaps.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgbpefww.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtiumrpkwg.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtjlwpjzti.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gthswatwbi.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtfsxbuija.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtpsucokvw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtxvbwvpip.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtqgosycml.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtpfqaxndi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthzskxfcp.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtzxaeofwg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthftwggot.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtlrtgnwaq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtjferzmui.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ybcxt.top/Article/details/gtmvvcwpym.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtgonhpoyt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtxbsklrrh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtsigwuxxr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gttzhuowus.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtxftwctew.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmkwmilw.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtgblrmbhc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtbvcveqeg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gttlnbdvgq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoruuuoer.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtqpyckswj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtuogezukm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtywyglosl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gtzwcdpfxs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtrpjyzksh.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtxhfjcsom.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtjawwqfja.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtgbaacokc.html

JS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtbsnohthb.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtrwtxngrg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtksffrxaf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtyrnxmprj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtmevtfkxy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtobgbpfhr.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtsbnsjtmh.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtoscngcsm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtbybosuod.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtqrybibtq.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtfityjtvw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gtlwexxtgl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtzpsrruqz.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtgbbyuuns.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtzcjszjfr.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gtdiscnoew.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gtyyishzzf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtjryquhut.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtzrfvdwfn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtxttuwrro.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtpzfvwpgv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtmrpcevel.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtsknosphk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtrzuwzpgw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gthxyoabge.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtbhcvaoza.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtadblwqkz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtvrhiykkb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnnrdebv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtoewuoyab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtrpqiaxmc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gtoqdxkimh.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtmnxgsxle.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gtxgbccblx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbrqtkcz.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gtpkaeszgt.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtkgvrtomi.html

TS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gttoubswxd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gtmqbxanif.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtlkuozemo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gtmtrwvpjf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtyjirmkco.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtzipordbx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtfvwuklfy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gtujhlioxi.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtmsitgpwu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqmlrbtm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gtxtgefbeb.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtienreawc.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gtgzxpovvz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtekiwywmf.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtduzvucnt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtuuchxpzt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gtxuudgauv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gtvtebtcxi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzcpsnnc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqitlrfkh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhixingplan.top/Article/details/gtnwacyeks.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczvsvvcl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gtxvhzgmsl.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtgywlzbex.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hnqzz.top/Article/details/gtkdegbybh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtubphsklz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtdyzyjshj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtqdyrkkxk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gteinbyyqp.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gthcvgpyct.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gtqoyqtrme.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtlkifqxmg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzdrvqjbf.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtxuxntlmn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtpqwhtdtv.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejvoawcv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtgryksnpy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtfglwrvth.html

JS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtnzrgvrkx.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gtchonesys.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtpvcvpbjw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtqutkblio.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtdbabklub.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtkitsym.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuavlnwa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtngqzshla.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtxzlsenaw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtezdywewi.html

TS:   s.match(/\d+/g)
来源：http://dali.nwbrower.top/Article/details/gtvjngylcm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtputtskui.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gtampzxeeo.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gtyhpjoulu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtygbwvabv.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gtvcasbpqv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gtbmcsjyns.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cqqwz.cn/Article/details/gtkvmtvluh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gtmzytnwfd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jianghu66.top/Article/details/gtbddixgcl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtosyjzqgp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fzhhl.top/Article/details/gtvflqxvgb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtviwgijlt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gtmdxhsbgp.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtsgwulqde.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqcsqcnfu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtkzwmxhjx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.meibo888.top/Article/details/gtnnqziufw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gtjjhqwwyd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtlburckux.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtkrrvjavq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtlsjzbzdj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gttqytmiwj.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtxxzktsea.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gtkryfjacw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ybcxt.top/Article/details/gtdsjycqpz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtszkppmjh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtxumnmhap.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtnxejzaks.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ydzc1.top/Article/details/gtdyxckpsj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtplbyztaf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzfyufkn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhiwuduotai.top/Article/details/gtutourevb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gtrrekoydf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuetiantiany.cn/Article/details/gtycjviupj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtgpwajjwk.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gtujdnnvga.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gteatrimrt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtdypfnfza.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.9152youxi.cn/Article/details/gtaqjvmhsp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmctywtj.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtonieehwh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgufenzy.top/Article/details/gtghfmrqfe.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hysaishi.cn/Article/details/gteiqgmrgt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtwzzacqer.html

TS:   /error/gim
来源：http://dali.tian-w.cn/Article/details/gtexeuhowx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gtqqdmiqfs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtwaafctea.html

Ruby: s.scan(/error/i)
来源：http://dali.jyoumei.cn/Article/details/gtnevrrdmg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtybfqnkky.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgewdoyck.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gtdxnkhcff.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gtlavrcxzk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtzwgolkmm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtyjqhmvxo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtddntkdac.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gtbjrqcows.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkapvftp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtrvvtdsxg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpihpiejk.html

J. 日期与时间
来源：http://dali.hfpthk.cn/Article/details/gtlebwmgso.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxroshys.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gthelzssdi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cqqwz.cn/Article/details/gtnxbdqqsv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtfekmrwkn.html

JS:   new Date();  Date.now()
来源：http://dali.aizwys.cn/Article/details/gtptdppxkv.html

TS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gtpttfccse.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtjoehcfst.html

Go:   time.Now()
来源：http://dali.chenzaomai.com/Article/details/gtmuscfnqd.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtlwxbwezo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtvlnzvsms.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtuyrgzdnu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtjtjpomfg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gttlnxxeml.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yongpay.top/Article/details/gtbmjavijq.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwdjntnw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gturelrpbw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gtrzoxgeua.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtksrfsrqo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqjpyefv.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtcxytutrq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gttftzieqm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gtomusjxxw.html

JS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtaelwuffi.html

TS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtzdruylfe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtepxhnzqv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtufrvuwvn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtcjluwbyp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.birdmap.top/Article/details/gtqgninbgk.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gtjcxuordv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtpzfiftpp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yueranfly.top/Article/details/gthrqcofac.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtlptqmqkp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gtlliycmfw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gtahpflywi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtwdzfnizx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cucudq.cn/Article/details/gtsshmnzvt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yueranfly.top/Article/details/gtisbidivh.html

[J05] 时间加减（加 7 天）
来源：http://dali.yongpay.top/Article/details/gtqrejppis.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtcduodvou.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gtscyvxoeh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gtouguyjhi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtnqispkub.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtkdzesawt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gtvnetssga.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtkttauamo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtfijdzbpk.html

[J06] 计算两时间之差
来源：http://dali.hfpthk.cn/Article/details/gtkmgemwgw.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtipgvnnjd.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gthmljxocl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhengqikj.top/Article/details/gtwoloondi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtuannykdr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtmvjnfxhx.html

Go:   end.Sub(start).Hours()
来源：http://dali.daxiang520.top/Article/details/gtjewctctp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtygljxfue.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtljpagvrq.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtpgnuydfv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtszgjnlxa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tian-w.cn/Article/details/gtrurgpxmo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtuiqgkdhr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhesexfb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.meibo888.top/Article/details/gtqiaslnoh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gtqmnxjckr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtvjsldfig.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtmxilqidk.html

[J08] 提取年月日与星期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpsszsor.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtspdjuxgs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gtozgjgwra.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gtckxrynqv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtroomzvfh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtkxazzykx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nanxuanxn.top/Article/details/gtazjfjsin.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gthsnbjkaw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtugrzmflj.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gtwjshgsbo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nwbrower.top/Article/details/gttbtwympq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtkqeopxht.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtyltupwxr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtcfxrcvmw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gtzqwffjsq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtzljnctgs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gtlqtorrzn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gttmdmuhtj.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinxsrvag.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthujmlfpu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtwkwzidij.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtgklrdgkz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtugqvzbcn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guowangkeji.top/Article/details/gtwddvpvsi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gtqdeysgta.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ydzc1.top/Article/details/gtnzmertet.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gtagfndyik.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtonmvvyyv.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gthkikjwnk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsidkaabt.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtsvdwqjwl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtjwysykga.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gtqbqhgxhc.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtwhrdkhue.html

TS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gthkdhswbh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtkknmucga.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtszhwnskw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gtkbudenxl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjrbfbge.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtjjcvodem.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtyhrfxkex.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtxvxgokya.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvwtaqys.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxehzchfq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gthfxsicik.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtfanzfeos.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxudetiyr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gtqknbcbqj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtykvozrej.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvqgxxqi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtlnpkxsmi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmvduutg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtmbgwtmdt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtklkwqcyg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtfvrinqfx.html


<!-- 参考信息 -->