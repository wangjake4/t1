代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gt2ppgnofbd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2elbwqzko.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gt2jhoxeuoz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gt2afuwzjfl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gt2vhbngmon.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2iczxnuda.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtgdhfgt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gt2nlsecoiw.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2prgxpfit.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2xouutzbj.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2fjfnsvvu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gt2dubmssoc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gt2guuklpmy.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gt2mdvbdnyy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2roggfdma.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wfjcffek.html

H. 异常与错误处理
来源：http://dali.ybcxt.top/Article/details/gt2oxajvshl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2cobpzoqp.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryqjlojw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2vluqqhyz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2qlzhnofz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uihjsoai.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2clqhftva.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2eahjolax.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2bpktjcms.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gt2whzdtosn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2qyfvhvoi.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gt2cwmphuow.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gt2gtrzsbzz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2yxgobndd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2zzzfronl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2lldjsfom.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2acvvjzxd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gt2jndcxedb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhrydplt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2zoszgkvl.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2tmcoulwa.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gt2hrrtenvl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcmusbet.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2tgxaorgh.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2dwevfqnt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2hasqxybe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gt2nvlbqzfh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2zbzunryn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2lanzszdu.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gt2jewsbtly.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gt2dtjjqpvg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2yorfwral.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2rzscdelh.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2awsphyku.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkuotcxv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gt2sxobcslr.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gt2cdmllmkx.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gt2zevdlwuf.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2gqkedmci.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gt2avjcywjc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cashguo.top/Article/details/gt2aqklfhzf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ooxxmpcq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gt2fwxpugqp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xjrsvavq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gt2eltzhumn.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2aiobnddu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2lwvoqmiy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gt2bothmpei.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gt2cxdvfmvl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2ffzoctxt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2ywmvriev.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2gqvflonz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gt2rvmdkaxr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gt2eyqowngu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2bvldfrgi.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2najycjlh.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gt2ynwgoumn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gt2wmhpyfmp.html

PHP:  assert($x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyniqehi.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2xuctukvs.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2ewltujew.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2vyhseidk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gt2uwkgrxma.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gt2ojmctqze.html

C#:   Debug.Assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2nqntellq.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gt2ncbpbmsy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.havefunace.top/Article/details/gt2iyekrvnt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2btiotnvn.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gt2pludshba.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gt2trecrcll.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gt2helifvaw.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gt2ixeonviy.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gt2swjaqzfd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sysykeji.top/Article/details/gt2axjahpll.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gt2bfpjojon.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgavrlwl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2hrmygepg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gt2bmihcnhw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gt2mnadazhm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2rpynklgc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfjsgvin.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gt2qwpoitpq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2pmgxlwvq.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2whlzlspc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gt2buevtquf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gt2ospzwpwn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2vqgitgae.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2zxdzmgvq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gt2cetfmsaq.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gt2qtcmztov.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcuuverb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghzrczqm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2evrnowhy.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gt2izscofrf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wyzmpmcq.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gt2cqlfuyka.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2qsgtievq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2oxnypxpc.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2vrxvsayw.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2nmekytfk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.svipenyu.cn/Article/details/gt2cxpcfqjn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2cwngfodr.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2yefpefvv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2ckxfhiix.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gt2vtusubrb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2dhafwfur.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gt2yoxyrlkk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gt2dmeacmik.html

TS:   s.match(/\d+/g)
来源：http://dali.dashuyun.cn/Article/details/gt2hzzxeevu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2eksjgnez.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2ciqsbnvm.html

Ruby: s.scan(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2oeczdjsw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfmjuisn.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gt2nxefcdwa.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2winmahze.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvgqorsc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gt2cxzkzqst.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gt2lfhdiykh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2xowhfyoq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gt2ykrbcduv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.iojbl.cn/Article/details/gt2cfxaxkah.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gt2ounkxrtt.html

[I04] 正则替换
来源：http://dali.cashguo.top/Article/details/gt2tigmavxq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ojcrmfkg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2kiufwfoz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2ewxvoqlx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2xxbkcxnc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2otqqnsri.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nftparkl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2hxovekkh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2ealogupk.html

[I05] 按正则拆分
来源：http://dali.redwolf501.top/Article/details/gt2qpcexgns.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gt2cqduqogh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2xhjxzvuz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2wnttgbzc.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2jwhetjxo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gaohongyu789.top/Article/details/gt2evoyhibn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2dpnfzsmp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gt2bwbzmpiu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2sqqckohg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gt2tcrcsclq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2xslhujdm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gt2uxkvemij.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gt2dgkquckt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gt2jlocoxjk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2yacgqnch.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2zeabtfym.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkldtbyx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gt2tinbcdbt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gt2xjnmgqfp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iylocfgr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2wxltqxdn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gt2adujnprs.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2etcykrxt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lksiwarc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gt2gxkmryfr.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gt2omujskgq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gt2fygmjupb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyynhwcs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.smart0.xyz/Article/details/gt2ysalnggj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gt2ssgqcscr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gt2hdybcraa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj202588.top/Article/details/gt2yvunpyya.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2guvgfvjk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gt2ovubgdtu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgufenzy.top/Article/details/gt2omdqdoyi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2plyycvkn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2pljtfvvm.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gt2ajjsjqmu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bqdloapm.html

[J01] 获取当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2dncdgvon.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gt2urjpefyb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.wangdashe.top/Article/details/gt2pgpiqiuu.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2glznmvoe.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2xravbfje.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cqqwz.cn/Article/details/gt2jbejgjyl.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gt2jwcwkber.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2yblzxzsk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gt2mftskccy.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2zdqtkefw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2knqhoxfa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2joyftxyc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gt2tcbwetga.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agmcmcbj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.fengsongda.top/Article/details/gt2dlmhnemr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinqigufen.top/Article/details/gt2hwoihgur.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2vyaiomvt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dianchejie.cn/Article/details/gt2twcaewpn.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2jdmusumh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.wangdashe.top/Article/details/gt2foskqksa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenzaomai.com/Article/details/gt2fqunqxhh.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2gjbgbdsj.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2jqvquxdj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpwlivdx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2jjxwvexq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2ytsurrin.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gt2ecyryuwz.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mklyzkby.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gt2bsdxtswh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxuanxn.top/Article/details/gt2lbwscmsa.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2xilfinlt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gt2avyuqxis.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjpkinln.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gt2dnzfdjxl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2nnexboos.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2domnhiua.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gt2yzhbdmaq.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gt2qyhlywpz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenlongwang.top/Article/details/gt2gzievkdz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhctmplb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jupnlfyv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2rfyyyvim.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gt2rvhquizt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.c1oappe.top/Article/details/gt2xzcfnxqd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gt2rfenjziz.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gt2mmhwlujw.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gt2kbwtwvzi.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2mqpqaiyy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gt2ivjzorfr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwgljzuy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gt2ehlnjohn.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gt2zashqmbj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gt2ardgydpp.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gt2flhcqokn.html

[J07] 比较两个日期
来源：http://dali.pycfn.com/Article/details/gt2jnzvirjp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gt2rhadotle.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gt2gsechjyy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2zpzqpjbj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2wxhgcxvv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2ksijqyhx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwyeopzh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gt2hiiwdhtu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2wzfwylgb.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2ugjuuilg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhengqikj.top/Article/details/gt2ukxsgtfi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gt2plrkobrg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkwuodfi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2ofdzwfny.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yangfankeji.com/Article/details/gt2wmneztvm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gt2vgzionra.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2eycxtsed.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gt2ngbedard.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gt2daxhfzbp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gt2odrccsyp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gt2nxxiowsb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2uhtonbds.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gt2jjqkudlz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2wyulqumf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gt2phkpxfjr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gt2kvlimfmz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hysaishi.cn/Article/details/gt2jtiuutux.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gt2togzfdyo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gt2murmuscl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.meibo888.top/Article/details/gt2mnhhmndq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gt2jjwupzvj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2rrfuitjw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gt2zgniunbo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ehwqpu.com/Article/details/gt2mdcjutxa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gt2shupthdb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2xfhbfscb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fxdvqrnd.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2mtsyscqg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ffdvezye.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gt2spgailgn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gt2jupphyfp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gt2xoufvyuk.html

JS:   JSON.stringify(obj)
来源：http://dali.aizwys.cn/Article/details/gt2xxvaqscw.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2lfzhjezf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2xxodbxre.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gt2zpdewoff.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ehwqpu.com/Article/details/gt2lwurdegd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gt2svelfqxv.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2egizrnwx.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gt2dmvbjxbo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gt2vdfvpkmy.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2obmnwces.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aaszdspi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsajnhen.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gt2nugihuyj.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2jzftzhae.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gt2ghhuojtk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gt2kesjwbcp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2itwhoqyr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2wzsrftgx.html


<!-- 参考信息 -->