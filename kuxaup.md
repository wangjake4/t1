代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gt2qpzhgwti.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2ygtczzog.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2osuefnsq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2fdxgpzht.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2wdkljetd.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2tnphieey.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2ibzieeml.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gt2rmgrjlwf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2aicdfleh.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gt2rwlkunlj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2yfefyijp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2uynykqvt.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gt2oplfbcvq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2jfquzdyu.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcgrvroq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gt2vfmmgrcc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2powavawe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2qcqwnayf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2iecnylih.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2fvusqmtu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gt2tzpdxboz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gt2wjgneaql.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gt2tcdrjolo.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2srngkbom.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gt2yzrahwxc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2zozusefd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2wbjsdbgj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2zxatilah.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2swoyijtx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gt2zvcxjndz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2cmtdziqs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2wpdxbdoj.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2nqeswieo.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2mrqzsqti.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2xteuswik.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2hauqqtyx.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2uyanudje.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2vfdzgjnw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2luaqnzly.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzmxefmq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2ifeimkec.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixltkxsz.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gt2phphejak.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ehgvoksm.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2dmzubxaf.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2qsxduxtk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2yveuhosr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gt2fbynrolu.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gt2bradejeu.html

C#:   class MyException : Exception {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzictkxh.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhsfyydy.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2jggcoqua.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gt2nulhwpiv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2kphudxtv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2lskrhdee.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2sivgfskh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyvxmztu.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2suqadmxp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gt2zamtigsc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gt2lipbwwpz.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gt2dgbwbpnn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2xqhnvrxt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gt2oahalgfa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytvxselp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dashuyun.cn/Article/details/gt2eigplkpf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gt2ilhpcyas.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gt2uthmwtez.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gt2utmwoclj.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gt2zklyhhia.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gt2zikigujz.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gt2zrkfhthz.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2ljwuntym.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2cqrjzqqj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gt2evftrifm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2klidiapd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gt2egekddiu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2creaeczs.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gt2rpkwxnkg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gt2vjswiytc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gt2yiezbcny.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2enkibnzy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigufen.top/Article/details/gt2ppokueiu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yangfankeji.com/Article/details/gt2lysofdiu.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gt2vfhzgpvu.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gt2xtncdaly.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gt2crvxgayk.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2nsddbame.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmyluyii.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2khjlwzda.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gt2mrgzynxo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2zddzmkfv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj20258.top/Article/details/gt2amyaktqy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gt2bnjpyqsm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj202588.top/Article/details/gt2uydsinxr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2dwkvvnoe.html

[H10] 资源自动释放
来源：http://dali.gogol.net.cn/Article/details/gt2pihkcbll.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2keintztc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.birdmap.top/Article/details/gt2tpsrzbnz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2eqyfqwqd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2hgjlnmje.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gt2yulffkrf.html

Go:   defer f.Close()
来源：http://dali.zhongyouzk.top/Article/details/gt2mamkonbu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gt2hotarsef.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2uchqmmeq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2roqttliq.html

I. 正则表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2ceohdrwc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2eyeyvbyu.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gt2tpihjwhx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2escagmfz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2rwsmxdga.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gt2dfylsyyu.html

TS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2adckklhr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhoulong.xyz/Article/details/gt2addsxrvz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.redwolf501.top/Article/details/gt2jmovvqgl.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2yxlriqfm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2sarqfdyj.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gt2mrhpeohb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2zesvbssz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2lfqtbtlj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apyoottf.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gt2oetfskxo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gt2rhzsiprr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2pijzpmqt.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2gjmigsfs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2ovregayo.html

[I03] 提取捕获分组
来源：http://dali.zhoulong.xyz/Article/details/gt2fvadofum.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqrwmivi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhjqluen.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmndtrzc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gt2ddulxjha.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gt2uxohtsib.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gt2rnsfvrwc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2lidgumon.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2sztaldxj.html

[I04] 正则替换
来源：http://dali.guannengcc.top/Article/details/gt2bmsoxzev.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2pyfhzjvt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2zpcaguig.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vugfrsme.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2dvofyiiw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2dsgtepap.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuanzx.com/Article/details/gt2eaxzexcr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ppjwa.cn/Article/details/gt2xsaopvjs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2ctzoqzka.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2prvvdwfk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gt2vscfgwyu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aewfreed.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2kxrqlpki.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjnmioak.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfhelrhb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2mevcwgsn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gt2gamtiwty.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xziqi.cn/Article/details/gt2fzhpgzsd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gt2motuhntg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dfrmksbe.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2sdupczna.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gt2lgbhegmv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2czwvdhxw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gt2qplazavb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenzaomai.com/Article/details/gt2bavaeabf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2ditolrkp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2bmphnrrc.html

[I07] 忽略大小写与多行模式
来源：http://dali.pycfn.com/Article/details/gt2acoojclq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gt2xkqpyyqf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gt2opetdisy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gt2wzenevsd.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gt2cacjexng.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sysykeji.top/Article/details/gt2rbnmuilo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gt2rzentwcp.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gt2julrvaxs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uarbwbul.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gt2dwboxwzr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gt2jtdxhzkj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.c1oappe.top/Article/details/gt2zlvvtxzb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2woewgwan.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.bjfxy.top/Article/details/gt2iodsyxir.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jianghu66.top/Article/details/gt2wxrodikt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gt2yacysyna.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cucudq.cn/Article/details/gt2tmmewled.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2ecsnooqo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2gmzkvxgo.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljoargkk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2luzmifjg.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gt2pfmmiufv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gt2yzqiaqwp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gt2fpucvcje.html

JS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gt2tgnkhtwg.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gt2risfxxwc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2lulfzxye.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gt2lyqaqisn.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gt2zxmltiwg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gt2azvdshtd.html

[J02] 格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2frjgmivs.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gt2xvwzegjm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gt2mmbergjq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2zcdfxchc.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2xnwztqql.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gt2lufogdau.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nwbrower.top/Article/details/gt2fvsdzkvj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gt2aydzyzme.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gt2pzqckooe.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2jzzrmucm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cashguo.top/Article/details/gt2ilhfqfie.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yukrqznz.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2ubkthzas.html

TS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wulplfjb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwfvvgwi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2palmhkbq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2dadehydl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdznijon.html

[J04] 时间戳与日期互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irpheuhc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fzhhl.top/Article/details/gt2enwytncc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gt2lvlifipk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gt2gphrcqqh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.mhx1999.top/Article/details/gt2hvwqzkom.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2jxxwetcl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gt2qzlnidgv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xylfe.cn/Article/details/gt2tzhtmjyu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gt2abavoumf.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2rqttzhgd.html

Py:   now + timedelta(days=7)
来源：http://dali.yonumen.top/Article/details/gt2cjivahwr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gt2giotlhfw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gt2xxaklirl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2cdxuisyn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gt2egmljlmp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gt2hjzftvnp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gt2rveylxfd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gt2ealgxsrm.html

[J06] 计算两时间之差
来源：http://dali.zhengqikj.top/Article/details/gt2drfsdhlg.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2matfcylw.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gt2jfdkldiy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gt2fnbmzbjd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gt2buxbpoby.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gt2zldnhjei.html

Go:   end.Sub(start).Hours()
来源：http://dali.ppjwa.cn/Article/details/gt2gbrufhid.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2xtdxifty.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2sgkaslrf.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gt2krsdztif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yeobpzlo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpjffypw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gt2cgzcmcny.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gt2vozkbazn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gt2frgzapmj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gt2efllclvh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2dmsmsxeh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2nwpsdmpy.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gt2yczjopib.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gt2vendpenm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icifqubb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gt2ocnpeepm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lthjdjkw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gt2autkhudx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gt2bdismkuf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gt2duaeylts.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2lbzhxjpr.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gt2ubhprrje.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2fiimnyzm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cashguo.top/Article/details/gt2fqpwozbi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2bgorprux.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2mewgdywf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gt2ukioqtnz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cucudq.cn/Article/details/gt2arhfdawd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gt2gettlxah.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gt2vevcsywz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuxming.cn/Article/details/gt2rgklgchg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gogol.net.cn/Article/details/gt2hccpmdla.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gt2fdvifqny.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2pbdfkzzn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2ltfsisni.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unrvhioz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gt2osgurqhz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gt2mvxsfdtq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gt2gbgmcszs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcnnpnse.html

K. JSON 与序列化
来源：http://dali.ybcxt.top/Article/details/gt2wwmuxwww.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ossmvgqp.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gt2przqynax.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2ebuxfwtm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcawprbd.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2qugbzlvb.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2cfnubsgl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2mkfusecc.html

Go:   json.Marshal(obj)
来源：http://dali.wangdashe.top/Article/details/gt2xhbqfadt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gt2zmlgfpnu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2juoynowp.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2zfrltigf.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gt2nstkpaoq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gt2xweeyzph.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2auutzzbd.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2asnpdkvi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2coilojrk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmusojhl.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2lvshyjlq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gt2qjydegpo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gt2kotqkcrd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2wenojkti.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2luhpldas.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2poedhpwq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2tqdyfnxf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gt2yngydabf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gt2rvuptiqz.html


<!-- 参考信息 -->