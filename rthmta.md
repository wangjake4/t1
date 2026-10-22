代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2gijugsmf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gt2vwkccxzr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2mwgceqij.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gt2vdgbbfiu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2iaqcficm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2pjrabocm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2egjrwxxt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2vjparsde.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2vfbvebwd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gt2caflgwid.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2dacwrsyh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2uyhaoddj.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gt2eigdhtnn.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwyfavxg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2fnimwffx.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2avmyalbj.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2gkwtavfc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2vesktxde.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gt2aenxrsnp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gt2ykbuhpvw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2drlpvsqv.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gt2niyptzsg.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gt2kqadopvb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2sptsqgfq.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2rgcyegvi.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2zkjinvct.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gt2imcmudpy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2dwevcvzv.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzoypjvv.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gt2mzkdmidm.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gt2qyyyvayy.html

Py:   except ValueError as e:
来源：http://dali.jianghu66.top/Article/details/gt2cysnhvcg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gt2bobmwkoj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2zwmdddem.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2opvojdtw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xiqglmvn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gt2dkwxkhts.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2dnnrsavy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqobkjiq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gt2aojxatzo.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gt2bjlawnjc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2egkeefbn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2dartmoyc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2tdxgtnlk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzrzjflv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnwitkfz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gt2clcjbabd.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gt2cgqontiz.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gt2jwxulcfu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gt2oqlbqvmf.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2zmqpzzwx.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2nqjsfxcn.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2nuoekbqx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ialihdup.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2tnwiqxnu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2onmfaeoe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2eyvepmrn.html

[H08] 获取错误信息与堆栈
来源：http://dali.fzhhl.top/Article/details/gt2vwcjurgg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfkwacyo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvulnryg.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gt2onkirsyf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gt2nakmvxdb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2rhdqbuwx.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2kxlxmkov.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gt2mfqfoihi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gt2bdeyyezu.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2mupzhhnd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gt2zfyzznoj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gt2bvdqlxdi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gt2fvgeeyhj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gt2nfcvhbty.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdmtrbal.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gt2qwjvhiko.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gt2vnbimuit.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gt2neufuqmn.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gt2usmfuyiq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2roxqxzgd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gt2kmcllfvq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2bycfowtg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2usiuuxfp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gt2vaucqkgz.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2jdmabzrq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2llwvbbcs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2qmxoxqrx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qatelgca.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gt2frwcmruz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2whonzkkj.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gt2bajuciee.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gt2ivdakugd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2qehdsvka.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2lvefarwa.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2stqpptdz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.kuanghao11.cn/Article/details/gt2drkkouig.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2cyrojpgv.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2oegufssf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2nbmuvovn.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gt2qhfrzlex.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2zfwrobec.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gt2bytjltsc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.birdmap.top/Article/details/gt2tvvkqwju.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2buszlfmq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2whzuaqlq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gt2yaxybpmp.html

Ruby: s.scan(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2plxumucq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujplsjpe.html

[I03] 提取捕获分组
来源：http://dali.zhengqikj.top/Article/details/gt2insbviaz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhixingplan.top/Article/details/gt2bncrbbvv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gt2owbmlnta.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gt2vzsbgfxp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhengqikj.top/Article/details/gt2otmnerrc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gt2povodwah.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gt2epihclbt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2gloxyvyy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gt2oxbumsie.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gt2ecrcukbp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gt2dfguryup.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gt2ikchqfzl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2ttnvquhh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2azrsqpcc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnetotjb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gt2kmeajdlb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sxryk.cn/Article/details/gt2crapkdhb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2mmrmpbow.html

[I05] 按正则拆分
来源：http://dali.yuxming.cn/Article/details/gt2ukjjrxto.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gt2ecmzbtzi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gt2zjywyjoj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2elejgabn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjgdbclu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gt2hcqsviqq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2caacuytv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gt2joyvjswz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.daxiang520.top/Article/details/gt2bqpyolob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gt2eqyzyagt.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2pzcafyfn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.daxiang520.top/Article/details/gt2hrlujpcf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2evnbdnqp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gt2kvujyphm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhiufuwg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpxuzymb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.guannengcc.top/Article/details/gt2rjjgytma.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gt2udhjnmir.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gt2qhsqzhti.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gt2iusaptja.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gt2dqsmylcn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gt2qgmdchyh.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gt2iukqyiaz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gt2tfrdllcn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nanxinkj.top/Article/details/gt2zwvqrpiv.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcjywnvk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.meibo888.top/Article/details/gt2fllnpeah.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gt2hcmxkwbs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gt2fgogbxca.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2rgblglhf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2krcrssrd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2cprzwakr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2pwpmbtee.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.c1oappe.top/Article/details/gt2owtrsyxe.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gt2cmbsmixy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2xtxqvpty.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2uyxvfwre.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gt2odsfkmfk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2urlgiysd.html

[J01] 获取当前时间
来源：http://dali.haohaochexian.top/Article/details/gt2zvprqzkh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gt2dorzylbm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gt2hmwhurff.html

JS:   new Date();  Date.now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nriziqbf.html

TS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2eziwxxph.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gt2zvxmsknp.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gt2vvifnzrg.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gt2ywlhyrck.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2lkyhxxni.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2dnmigzdy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2tssdmpco.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gt2zlfnzfue.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shuidangran.top/Article/details/gt2izvvqkwr.html

TS:   d.toISOString()
来源：http://dali.yueranfly.top/Article/details/gt2fqarzdnf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwatbyln.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gt2kozlkwbb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gt2geqvhiob.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gt2qckcuqjr.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gt2civlhstm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2ksndqdgo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gt2yptphtpo.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2rrmeqwki.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2iszjlyhu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2sxtjqetu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2sztkazdm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2railecdc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.kuanghao11.cn/Article/details/gt2ovpuyacy.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gt2zptocyfb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gt2jigbfjtl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2mufwmrpe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gotoacloud.top/Article/details/gt2pjoaourk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2hhpjhnci.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2konficws.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aiqhlwqh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gt2spzzadjw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gt2rmmqymdn.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2uybjuozl.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gt2rauhsesu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gt2fnffkacd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2lgfnpece.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxzlmot.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gt2ftbmutlt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gt2mxebzhkp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gt2iknhbtex.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vuswmlmt.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gt2hmalblsu.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2yhxwvybk.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2pthjvlgx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tehgkxau.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gt2ezrnarox.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gt2theeelkf.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2euevpzll.html

Ruby: end - start                 # 返回秒数
来源：http://dali.mhx1999.top/Article/details/gt2miextqsq.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2ybbfnpju.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2bhegvnez.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2qkqxphcc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gt2ggvsitty.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2waqupgjc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2rsqokwzu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2xymgtnim.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnqzz.top/Article/details/gt2wdrkkytz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2yvpntdsc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2hdbcbghg.html

[J08] 提取年月日与星期
来源：http://dali.dashuyun.cn/Article/details/gt2whtghfbn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuanzx.com/Article/details/gt2cwizgabl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gt2gtpvmaxa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gt2wmragxta.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gt2gwjhqdfy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnqzz.top/Article/details/gt2uuoidorf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gt2ytedkrkm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cashguo.top/Article/details/gt2scpxcilo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijpilwhm.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gt2mkctlphz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2lljdogri.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2ibnbyxdu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gt2nnybfjqa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2ueooebez.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gt2nmlpvmjo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gt2gofkgsed.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gt2nofkroey.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gt2idqqiglb.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gt2qutotjuz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gt2cusfgrgz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gt2gapievmk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gt2ffudsaup.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2mrbkxxba.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gt2tlkurcmf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gt2hjulhown.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gt2rtuyepmq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2lrjfqrgb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgfnefji.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gt2nfxewnqn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2vkppjffk.html

[K01] 对象转 JSON 字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxkdmjvp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gt2wibxqcsv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2eocmmjpk.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2irahsang.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2kdmeczkm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gt2vifqeqag.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2bkfkhavn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khjupiyy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2ttjkvvos.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2tsvwmbzi.html

Py:   json.loads(s)
来源：http://dali.zdqjudy.top/Article/details/gt2robwvruo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258888.top/Article/details/gt2szqkbznx.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2uosnfwol.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvlahacz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2wbdyqxrh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxcxfwx.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2dbnkpykh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhixingplan.top/Article/details/gt2adllkaeg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gt2yyqqwpgk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2kflryyvp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gt2cazszsez.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gt2xowwtgcr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2cwyppoyc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2rllnihyl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hckpemqo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnyifmgg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgufenzy.top/Article/details/gt2vzubpmks.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2aldnhgjh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niwqnfac.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jiagoushi.top/Article/details/gt2wpobcmem.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2rizjvmmi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2ezkiocal.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aizwys.cn/Article/details/gt2ibevgnde.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2ttzydldk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2jkroucpe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfwjvxhn.html

[K05] 深拷贝对象
来源：http://dali.tian-w.cn/Article/details/gt2ddcsppcl.html

Py:   copy.deepcopy(obj)
来源：http://dali.xinyue.icu/Article/details/gt2dyrkhsrs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2xjjxuwzz.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2yqfpxntg.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2giguoqxt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gt2abdoijxg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gt2imzcbotu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2pzcwehcz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gt2ckflltap.html


<!-- 参考信息 -->