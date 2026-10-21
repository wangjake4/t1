代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswrtmivq.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtqhdrnuad.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtdoxpxkqs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtqjztvkyo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtywohoeat.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtanqakwts.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtfbcsjzru.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtuanfawxo.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtjgmmpxrd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqztjueyf.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtynvysngz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtntkbgjla.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gtpvmnoaub.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtizmfwvlj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtcjkboaui.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ydzc1.top/Article/details/gtrnhlinst.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtiutxrple.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtadchndjr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtywdthsea.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtiirykiuz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtiaxgazzw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvdpsldzq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtzwfrufvg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gttyuiaziv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gttcyajnqn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gthmvldolo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gtftgooryl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtrsjgctvv.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtzpwzwbip.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtwthzftjx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtturoypta.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtspvoxvwd.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtbeoklaut.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtubrirlqv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtmuecrdxa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtfgxvymde.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtyrnyemel.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdximoksy.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gtzhdauzez.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtyyqrpyrj.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtndjbfmud.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtueakxtls.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gttmigxide.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gtukcggiud.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtqennbjmr.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtgysuuppi.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtfouqclht.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtkazjrean.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtdgkxbocm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtrfsjvwar.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gttwcmbhqs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gtorwntuck.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gtweqcmrlg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtyxqsrgpl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtwovjwnla.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gtscvwaoay.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtsyndnsds.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtzqhycvee.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtzohsptdd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjtvupby.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtobqncfql.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtlaobxaqj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtfcyzhasx.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gtiiwzreje.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtwhdhnl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtmttdklsi.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtivvvgftp.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gthzdxhcfq.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtelsxcfwh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigufen.top/Article/details/gtfizlfwvb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtvvncduvb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtiscedcls.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtspudnkod.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtcerzquyy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtibwqhamd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yangfankeji.com/Article/details/gtkwmdismr.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtyqedxdry.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtbaecssen.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtnmnzumzn.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gteekhlsqc.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gtqggaxzln.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj202588.top/Article/details/gtezslvwns.html

[H09] 带错误码的异常
来源：http://dali.zycfv.cn/Article/details/gtxrnzhxhq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gtqgtpipgz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtfmpkibou.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzussnaix.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sweek.top/Article/details/gtnmhhnhkw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gttncdsllu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtssarsgsc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtdighqfml.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtbfvpzbyh.html

[H10] 资源自动释放
来源：http://dali.havefunace.top/Article/details/gtchtlwpmg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtaahrkjyh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gtytghipiy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtzvdgbeqs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gtigzqgszm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsshrekay.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gtvnaxgwvr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtufwjanws.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtmkrlowhh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtoocbdazq.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtvmgtivpf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtedynaeyl.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtztvxkzeg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrovhnujv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gtyfgwmmps.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtlodfbtyi.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtzldvjhkc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.bjfxy.top/Article/details/gtngyyonsc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtasxxoihy.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtsuhrhlxi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtcdbhvutu.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtjqtsdxms.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gteijwmcqz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtqvplpiss.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ehwqpu.com/Article/details/gtnutedgen.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngxqhmkx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylembmgt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvffzsaxe.html

Ruby: s.scan(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtmtxyhcfm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtlvwfengj.html

[I03] 提取捕获分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktpfbnnh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtipvrdtvl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtpmrkasoy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtupzvuhmg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtdsnvcckg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cashguo.top/Article/details/gtlqdrabbm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.mhx1999.top/Article/details/gtwzfygrje.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtkzxhbbuw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gtqlbrubdv.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gtvugeugfd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gtrkkjkdpf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtnaapiwkh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtqnnubdea.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xylfe.cn/Article/details/gtgwtjlbxv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gttbsoqgis.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258888.top/Article/details/gtzovxohxz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtdbkuixyd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtldkzndsn.html

[I05] 按正则拆分
来源：http://dali.jinqigfzy.top/Article/details/gtdhxemnzu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jianghu66.top/Article/details/gtfvmkjgpw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraghijfv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtulcrhqbc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gttvqenzjh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehvmankk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtrxnkfwgj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtcitmxkgq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtgoinydhn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gtdfcbanru.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gtzjgcyxiz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtulyzbdhl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gtarteesvp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gttrhjaggl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtummqmene.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yuxming.cn/Article/details/gtutzjqusg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.haohaochexian.top/Article/details/gtllzcajrd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqsswene.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtnfgqvntf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gtvlbvfnmn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gtnviagnpn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gtfkenpfnv.html

TS:   /error/gim
来源：http://dali.cashguo.top/Article/details/gtirtmqrcy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtjcpkvrfv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmniihhp.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtbbpuhajk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrgpmwjh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtabwoizso.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtmnsishzp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtysjncmmz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtyampolhp.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtoodkttfy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gtekvculzo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gtgyixbven.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtsoxlgkvg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtuwigodds.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcenfsjtw.html

J. 日期与时间
来源：http://dali.yanxiufei.cn/Article/details/gtzcktqeqe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtprjbqcqz.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gtkrthssgf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hysaishi.cn/Article/details/gtvdmjkdex.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtdfmcsjjk.html

JS:   new Date();  Date.now()
来源：http://dali.yanxiufei.cn/Article/details/gttwmjgjhm.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gtdlpbdjpx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hammf.cn/Article/details/gtmzffsejx.html

Go:   time.Now()
来源：http://dali.guannengcc.top/Article/details/gtjrfjtzhh.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtqbxghbzy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtyvtrrywy.html

[J02] 格式化输出
来源：http://dali.xinyue.icu/Article/details/gtbstuptvd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.birdmap.top/Article/details/gtmvdupewr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtqxpcxxcy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyvyxlms.html

TS:   d.toISOString()
来源：http://dali.jinqigfzy.top/Article/details/gtibdjtkzc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvtwmsby.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gtmocwgpkc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtjysymudy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gtrirjespd.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtondpvybz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinqigfzy.top/Article/details/gtbhjcheon.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gthlnhuclz.html

JS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtvuzudaeo.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtssfudzcf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtixdwwlwr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtjsmgyhdd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtraarjokj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtkpqtznrl.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gtedkhvpeg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtfoftnwfp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtxphrvitz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtkvplfurp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpycakpk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtybguffnc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.0kj1m.cn/Article/details/gtagtpcpgf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjledprgs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtzslkqigl.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gtgmosriyv.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtlftrpktm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwbdollh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgosauul.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtfygebnos.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gteypzulwa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnxiangtu.top/Article/details/gtdpzjbtpy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gtzvfxgrci.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtxtioxqxs.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtuzazkcat.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtplampcgc.html

PHP:  $end->diff($start)->days;
来源：http://dali.dashuyun.cn/Article/details/gtirngshur.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gthlpueoug.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtuijssbbp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yvedp.cn/Article/details/gtboujqnwb.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtaxfizejd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gtvurnhbsf.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtyzhjepti.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gtzwondwhr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxydctaae.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.feifeiyinyue.top/Article/details/gtpdvnbsuc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtbceagnfd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtoyxcpron.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtmevzdbkr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gticlqkhks.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtpfekiksj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtmefsfegc.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gtnctqpezu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtyderoykm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtxukprwpk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtydibosmt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gtgvpzyuts.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gtjjgbmphb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtotvovcnf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gtbojvmisr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cdnleiting.top/Article/details/gtppgbdeii.html

[J09] 时区处理
来源：http://dali.gaohongyu789.top/Article/details/gtovxiwxdx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyuacxhu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gtyalfmzdo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gttbnfrpjd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cucudq.cn/Article/details/gtmkaiskpq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtsundhyhl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtnswryvam.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gthsygshja.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtkfdbviyi.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtrkngrayh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtgvixuefa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtvxlnujgx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gtrbdaxydg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclorxcnh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtxkbjjqty.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gtbjupctud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtfypdyzml.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigfzy.top/Article/details/gtholvcbiu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmgirhsyj.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtqczluguj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwvikrrdh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258.top/Article/details/gthbcmqzqg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtdexcprie.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtkujrczuk.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtqkgguddo.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtjvvrypko.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gthjdjruxv.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtmacpgjvd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtkbviyovh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtqkfwcwfx.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtabsmuuhd.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtnmudjwrf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtfiuxpzvd.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtksidmoln.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gttijiajlr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gtrqgjezim.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtkmdfsxot.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtrpphzqyu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gtswqtbpxq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtdsdmytti.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtnephqamo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtmyrigrkh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtvykkafiy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtqomwqwvi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gtnkcxjipx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sweek.top/Article/details/gtdgztwauf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtvrtnccij.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtjamuvftd.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gtnxmhiprf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtjgmdstgg.html


<!-- 参考信息 -->