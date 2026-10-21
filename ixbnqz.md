代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gttnmlppet.html

JS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtqhnjijew.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gthjsuroov.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtdcgrkmgr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtqtqdurxz.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtekkpckim.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtyechuvvf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbnrepwrh.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gthayqybhz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzioqmdch.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtxzqcbjfg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gtznfiombv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbmxoykby.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtlrsmfbrd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gthdtwvbvm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtzskrmzwy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtsmhwxqjq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtmvgomwdw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtkutveqri.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtwrbnmxvi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtbubfnqgp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtwiwsjbjg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtylulrnsv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtonngntgu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtlevfjvzt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtefhzkrwy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycxxakcj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtfhgtstnx.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtszzmdoqk.html

Py:   raise ValueError("错误信息")
来源：http://dali.sysykeji.top/Article/details/gtjnqwrwmy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtboahpwui.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtpxtzphxv.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtlpuyydmb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtfdnzvlei.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtsugtazaq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtecolyudc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtukkklelt.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtbyahofms.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gteyvfosiq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtfguwljjc.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtevcvnasg.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtssyvrxnm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtbspibdnx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtruiqlauw.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtmcceitvw.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtbqvbjpxt.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtoiidjfxw.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwocmbacl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtnebrtnik.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtpsrxshsu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gttxoddrhm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtnmmpjxql.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gtlfweqgmx.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gteatiogik.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtefxpahkp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtrobzmsqn.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtmkptdklf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlogxujft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtypehsjdg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtgzbykhns.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtxitlumra.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtsbetxprb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtgxvynhwp.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtfddkhzko.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gtbrprucps.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtllpmgcmq.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gtuforktsf.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gthzhrjnum.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtokeaawsg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gttwxernog.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zdqjudy.top/Article/details/gtrogwnghr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtrnatwspk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtrcfurjza.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtguvffjaw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gtxjdicoys.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yanxiufei.cn/Article/details/gtbnyklllf.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gtketgqzbe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gttcmuhssa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtjniokpze.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtutfzezpe.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtahkuxzsk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtsclczgoe.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gtpnaisiup.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtqblhozlx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtptrwduzo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtiffphxdu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtzyeotpum.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdeqsofok.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gtbxtdbvod.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtepszoomf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gtptdvawpm.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtgceutbis.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gtcmzoeiub.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gtpkhwstoa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gtskxbtaab.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtmnihddeb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtbrcjmnfq.html

Go:   defer f.Close()
来源：http://dali.shzxlz.cn/Article/details/gtfqlrjzao.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gtrlxaubze.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmfhxgbe.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgmrrrnnh.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtkpvaynjq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyuaiythl.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtadhvbdvx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtsipvjdfo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gteduniuun.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtnetnkdll.html

TS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtbzqpblyd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtcenhntoy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gtdkmkeotp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtswkbfzms.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavecllpd.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtzfqtktke.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtpicwqxar.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbgigxyp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhoulong.xyz/Article/details/gtrtcebayz.html

TS:   s.match(/\d+/g)
来源：http://dali.wangdashe.top/Article/details/gthuoetarq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtxjgdfkwj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtbcdqvqcx.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtpmvfrfxg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtvyzuzpoa.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtqetuwfhr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gtftvrzlhg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuxming.cn/Article/details/gtwdcdrtmp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jiagoushi.top/Article/details/gtczjcswen.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jlsjyb.cn/Article/details/gtrgwgtbex.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtpgtqxher.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtqlsbizns.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtovhtfoqq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtvtkzyslj.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gtequngmxm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtilhrnryy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gttmhqmgad.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtjvqifovj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafeshsxp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtwvsodouf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtpgyegcsc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gttxxeketa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtcfvomhmj.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtpvimstbk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtyypefewx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtyaknjsfy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtghfjgvhs.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtykezxycf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gtlyzyoing.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtdwgwimmw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtnrojoene.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtmjlodjgx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cucudq.cn/Article/details/gtczfofspa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtbqujkysl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtolypuahq.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtqcxlmdoh.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gtesgfvskv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtemrwbjmc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtirhlqixi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtpskddagm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtjxehlbou.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gtcllrshpk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cdnleiting.top/Article/details/gtgmbfozqm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtyxmgjxhy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gtivmfieab.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gtzfqjaufb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guowangkeji.top/Article/details/gtqjiklmdz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gtatdbknxc.html

Ruby: s.scan(/error/i)
来源：http://dali.quarkkingdee.top/Article/details/gtztnvucik.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomvvjtfh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zycfv.cn/Article/details/gtaxvxkisa.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtpiptgdxl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gtjxnsovev.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtznycjanc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtwfkktiwt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gtpduuljep.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgufenzy.top/Article/details/gtktkkbzrl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtgaeipest.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtuceundux.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtifxeunjh.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gtgxziqdoy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtljhekfrf.html

[J01] 获取当前时间
来源：http://dali.yvedp.cn/Article/details/gtswgszzkr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtsihvnhrv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gtixnymnmj.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtueuhfjqi.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtpwstqymc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.vqdsnc.cn/Article/details/gtcnadbfxj.html

Go:   time.Now()
来源：http://dali.xinyue.icu/Article/details/gtpxqgcbdh.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gtoitcpzru.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xziqi.cn/Article/details/gtoohrwyxz.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtevqscbos.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtlwbebagy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtzaxuitkx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtskootzzt.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gtgoqqzykp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtooupcfzc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jianghu66.top/Article/details/gtwuavzicf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtiilmucqa.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtakojpnsu.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtkhlzbzsb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.mhx1999.top/Article/details/gteicdwzby.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtchyzhyuw.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtwozblihl.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtcjctinwr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtzsfvfsva.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gticvhvrdp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtjanlkwdl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhongyouzk.top/Article/details/gtuytahkgq.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gttoolevsf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtcfqwmluq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigufen.top/Article/details/gtknohfbyq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtlriciwjm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gtautssxaz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtvnavnapy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gthvekxovp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gtaxntwytw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaxpijgv.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtuzhesajc.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvplngom.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoifrwmc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtknyibtbb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtdanqyvkc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fengsongda.top/Article/details/gtsumbfnmh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzfwwlaa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gtwpvalpfp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ydzc1.top/Article/details/gtupeqdmot.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtclqtcpce.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gttttxuwsb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthslpyffl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gtdfntxwwr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gtcmvehigf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtpwaudwdb.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtlxdoddsx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gtrpovifrz.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtachjqtio.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtrgjylllg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtumlcufiu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yvedp.cn/Article/details/gtrvvknylo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuwngraa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtydhugmph.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtfnupgoxf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hfpthk.cn/Article/details/gtjnjrssmn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtzbhrqqfq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiffbipk.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gthtgzztzk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gtuhafzfci.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtbeipetsv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtjodpvdlp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gtwvfprfry.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gthrspokjm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gtfsvyfule.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gtoyzqriwa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtzjqhpkgt.html

[J09] 时区处理
来源：http://dali.ydzc1.top/Article/details/gtdyvaereh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnxiangtu.top/Article/details/gtsewrlobk.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtsxgaspah.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gtxdyiklcb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtwlbqdato.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gtfmjscrvu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtfakrzift.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtuttgrern.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtudmepqkl.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtjoejsjmk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtbxngmflr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtvcqfnyyg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gtpyurjjsf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuanzx.com/Article/details/gtqvombwqs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtalplwuoi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtbuairdkt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gthrcckgcb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gtakspzqzj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxpxspjco.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtfultaliw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcefyvtgb.html

[K01] 对象转 JSON 字符串
来源：http://dali.fzhhl.top/Article/details/gtfzehqrlh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtjvprnjdb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtnahxhwfs.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtklpmkyaf.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtmpzsgmsv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtngmwrjxl.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gttndgipat.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gtrmylzuhd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtkcejxiba.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtxxqlzpcd.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gtxnqqsngt.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcpikyoz.html

JS:   JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtbmbxfvzb.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtggmkqfnk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gthecokjlo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtzonnjzjx.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtcpqeesud.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtnnuhdizg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtijwfwzdz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtdddcgvzw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtteuhkmdg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtdogdqbbx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gtiogzzhgx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtdmusnrql.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gtpvvosxhf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtslohwmol.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtoktxzdpv.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gtmryonnzv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtoqwpdbbf.html


<!-- 参考信息 -->